# Environment Setup

* Install prerequisites
  ## For MacOS
  * Install Homebrew if not already installed
        * type the following command into your terminal: $ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
        * enter your mac password (used to sign in to your device) when prompted
        * verify installation with: $ brew doctor
              * if installed, output should be: Your system is ready to brew.
              * if you "see zsh: command not found: brew" type the following into your terminal and then restart terminal: 
                $ echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
                $ eval "$(/opt/homebrew/bin/brew shellenv)"                      
   * Install Ruby
      1. install rbenv
        * type the following commands into your terminal
              * $ brew install rbenv
              * $ rbenv init
              * $ echo 'eval "$(rbenv init - )"' >> ~/.zshrc
              * $ restart your terminal for changes to take effect
      2. install ruby
        * type the following commands into your terminal: 
              * $ rbenv install 3.1.2
              * $ rbenv global 3.1.2
    * Install Rails
         * $ gem install rails
    * Install PostgreSQL
         * $ brew install postgresql
    * Install node js
         * $ brew install node
    * Install yarn
         * $ npm install --global yarn
    * Install babel
         * $ brew install babel
   
    ## For Windows
    
   
   
   


  
  
