## Car Update System

A simple sequence diagram implementation for a car record update 

![practical_7/image( Update Car Use Case)/image.png](<image( Update Car Use Case)/image.png>)

This system allows desk officers to update car details by entering a car plate number. The system validates the input, retrieves the car information, and allows modifications to be saved.


### Basic Flow

1. Desk Officer types the car plate number.

2. System checks if the number is in the right format.

3. System looks for the car record.

4. System shows the car details on the screen.

5. Desk Officer changes the details if needed.

6. System saves the updated car information.

7. System shows a success message.

### What if the car is not found?

At step 3, if the car can’t be found, the system shows an error message.

### Parts of the system

1. **Desk Officer** : The person entering and updating the car info.

2. **FormValidateCar** : Checks if the car plate number is correct.

3. **UpdateCarControl** : The main part that controls the update process.

4. **Car** : The data about each car stored in the system.
