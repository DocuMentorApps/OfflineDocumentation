# Environment Setup

## Install prerequisites
  ### For MacOS
  1. Install Homebrew if not already installed
  * Type the following command into your terminal: $ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  * Enter your mac password (used to sign in to your device) when prompted
  * Verify installation with: $ brew doctor
     * if installed, output should be: Your system is ready to brew.
     * if you "see zsh: command not found: brew" type the following into your terminal and then restart terminal: 
       * $ echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
       * $ eval "$(/opt/homebrew/bin/brew shellenv)"    
       
  2. Install Ruby
  * Install rbenv
     * Type the following commands into your terminal:
       * $ brew install rbenv
       * $ rbenv init
       * $ echo 'eval "$(rbenv init - )"' >> ~/.zshrc
       * $ restart your terminal for changes to take effect
   * Install ruby
     * Type the following commands into your terminal: 
       * $ rbenv install 2.7.5
       * $ rbenv global 2.7.5

   3. Install shared-mime-info: $ brew install shared-mime-info
 
   4. Install Rails: $ gem install rails -v 6.1.3
   
   5. Install PostgreSQL: $ brew install postgresql
   
   6. Install node js: $ brew install node

   7. Install yarn: $ npm install --global yarn
   
   8. Install babel: $ brew install babel
 
   ### For Windows
   
   
   ## Clone the repo
   * In your terminal: git clone https://github.com/ahuelhorst/documentor.git
   * **This repo is currently private as it is a clone of DocuMentor's documentor repo**

   ## Set up PostgreSQL db
   * Start postgres server (via brew on mac): brew services start postgresql@14
   * Log in: psql -U <username>
   * Create a new database: create database <dbname>
  
   ## Set up project
   * In your cloned repo:
      * Run $ bundle install 
      * Run $ bin/setup
      * Create a .env file in the root of the project following the .env.example file
            * **This is where you will specify postgres username, password, access keys etc.
      * To set up tables run: rails db:migrate
      * To populate tables with test data run:  rails dev:prime
  
  
  

  
 
  
  
  
   
    
   
   
   


  
  
