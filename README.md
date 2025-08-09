# Hotel-Management-System
Class Dictionary
 * HotelManagement:
   * Description: This is the main class for the hotel management system. It contains the logic for handling guest check-ins, check-outs, and viewing hotel occupancy. It serves as the entry point for the program.
Method Dictionary
 * main(String[] args):
   * Description: The primary method where the program execution begins. It initializes the hotel rooms, displays a menu, and uses a while loop to continuously prompt the user for a choice until they choose to exit.
   * Parameters:
     * args: An array of strings that can be used for command-line arguments (not used in this program).
   * Returns: void. It does not return any value.
 * checkIn():
   * Description: This method handles the process of checking a guest into a room. It prompts for a room number and guest name, and if the room is available, it updates the room status with the guest's name. It provides feedback for success or failure (e.g., invalid room or room already occupied).
   * Parameters: None.
   * Returns: void. It does not return any value.
 * checkOut():
   * Description: This method handles the process of checking a guest out of a room. It prompts for a room number and, if the room is occupied, it changes the room status back to "Empty." It provides feedback for success or failure (e.g., invalid room or room already vacant).
   * Parameters: None.
   * Returns: void. It does not return any value.
 * viewOccupancy():
   * Description: This method displays the current occupancy status of all hotel rooms. It iterates through the rooms array and prints a list showing each room number and whether it is occupied and by whom, or if it is "Empty."
   * Parameters: None.
   * Returns: void. It does not return any value.
Variable Dictionary
 * rooms:
   * Type: private static String[][] (a 2D array of strings).
   * Description: This array acts as the hotel's database. It stores the state of each room.
   * Structure: Each inner array represents a room with two elements:
     * rooms[i][0]: The room number (as a string).
     * rooms[i][1]: The room's status, which can be "Empty" or a guest's name.
 * scanner:
   * Type: private static Scanner.
   * Description: A Scanner object used to read user input from the console (e.g., choices from the menu, room numbers, guest names).
 * i:
   * Type: int.
   * Description: A loop counter variable used in main and viewOccupancy to iterate through the rooms array.
 * choice:
   * Type: int.
   * Description: A variable used in main to store the user's menu selection.
 * roomNumber:
   * Type: int.
   * Description: A variable used in checkIn and checkOut to store the room number entered by the user.
 * guestName:
   * Type: String.
   * Description: A variable used in checkIn to store the name of the guest being checked into a room.
