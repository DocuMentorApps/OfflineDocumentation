# Actors
* caregiver
  * client facing healthcare worker
  * care for patients in the patient's home
  * work in areas with, and or without internet service
  
# Use cases

* UC1: Sign in - not sure how we would do this offline - could still have caregiver enter username and password
  and save this info in temp db. then once they
  * Business requirement:
  * Actor: caregiver
  * Flow: Caregiver enters their email and password and is permitted to DocuMentor app. 
  * Why it's a use case:


* UC2: Select active client (patient)
  * Business requirement: 
  * Actor: caregiver
  * Flow: Caregiver selects their current patient from a list of active patients.
  * Why it's a use case:


* UC3: View inactive clients (patients)
  * Business requirement:
  * Actor: caregiver
  * Flow: Caregiver can view a list of their inactive clients.
  * Why it's a use case:


* UC4: Express clock in - online web app requires caregiver to select patient name and then service
                                 before being able to clock in -> how would we do this offline if we can't hit
                                 their db?
                               - possible solution below 
  * Business requirement:
  * Actor: caregiver
  * Flow: Caregiver can enter in their client's name and service performed, then express clock in. After caregiver presses clock 
    in button they are prompted with a summary screen (service, caregiver, time clocked in, blank notes block)
  * Why it's a use case:
  
    
    
* UC5: Express clock out
  * Business requirement:
  * Actor: caregiver
  * Flow: Caregiver presses 'enter note' and can type in an overall note for the visit. Then they are presented with 'clock out' button. They press 'clock     out' and are taken back to home screen.
  * Why it's a use case:


* UC6: Modify note
 * Business requirement: 
 * Actor: caregiver
 * Flow: Caregiver can retype their note then press 'modify note' for the new note to be saved. 
 * Why it's a use case:


* UC7: Add tasks
  * Business requirement: 
  * Actor: caregiver
  * Flow: Caregiver can select a task (Hygiene- bed/sponge bath, Dress - Assist w dressing ....) from a drop down menu to be added to 
  a list of tasks.
  * Why it's a use case:
  
  
  
* UC8: Add goals
  * Business requirement: 
  * Actor: caregiver
  * Flow: Caregiver can select a goal from a drop down menu. Once they select a goal, they are prompted to enter their strategy used, select
  an outcome (succesful, succesful with assistance, unsucessful), enter a note, then save the outcome.
  * Why it's a use case: 
  
  
- should caregivers be able to clock in to scheduled visits? - how would we do this offline?

  
 
 
  
