# Actors
* caregiver
  * client facing healthcare worker
  * care for patients in the patient's home
  * work in areas with, and or without internet service

* Use case 1: Sign in - not sure how we would do this offline - could still have caregiver enter username and password
  and save this info in temp db. then once they
  * Actor: caregiver
  * Caregiver enters their email and password and is permitted to DocuMentor app. 

* Use case 2: Select active client (patient)
  * Actor: caregiver
  * Caregiver selects their current patient from a list of active patients.

* Use case 3: View inactive clients (patients)
  * Actor: caregiver
  * Caregiver can view a list of their inactive clients.

* Use case 4: Express clock in - online web app requires caregiver to select patient name and then service
                                 before being able to clock in -> how would we do this offline if we can't hit
                                 their db?
                               - possible solution below 
  * Actor: caregiver
  * Caregiver can enter in their client's name and service performed, then express clock in. After caregiver presses clock 
    in button they are prompted with a summary screen (service, caregiver, time clocked in, blank notes block)
      
* Use case 5: Express clock out 
  * Actor: caregiver
  * Caregiver presses 'enter note', then is presented with 'clock out' button.

* Use case 6: Add tasks
  * Actor: caregiver
  * Caregiver can select a task (Hygiene- bed/sponge bath, Dress - Assist w dressing ....) from a drop down menu to be added to 
  a list of tasks.
  
* Use case 7: Add goals
  * Actor: caregiver
  * Caregiver can select a goal from a drop down menu. Once they select a goal, they are prompted to enter their strategy used, select
  an outcome (succesful, succesful with assistance, unsucessful), enter a note, then save the outcome.
  


  
 
 
  
