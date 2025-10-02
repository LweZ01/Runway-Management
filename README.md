Inside the .zip you'll find the code, the executable, and a User Manual on Spanish but i'm adding the translation here.

# Runway-Management

**USER MANUAL - RUNWAY MANAGEMENT SYSTEM**

**EXECUTION INSTRUCTIONS**
Simply double-click the executable file to start the program.

**USAGE INSTRUCTIONS**
When running the program, the following menu will appear:
`=== RUNWAY MANAGEMENT V1.0 ===`
`1. Show status of all runways`
`2. Change segment status`
`3. Add a new runway`
`4. Delete an existing runway`
`5. Exit`
`Select an option:`

**Option 1: SHOW STATUS OF ALL RUNWAYS**
*Description:* Shows the current status of all registered runways.

*Steps:*
1. Select option 1.
2. The program will display the status of each runway and its segments.
3. *Required condition:* The runway and segment must exist.

*Example:*
`Runway 1: L L O`
`Runway 2: O L L`

**Option 2: CHANGE SEGMENT STATUS**
*Required condition:* The runway and segment must exist.

*Steps:*
1. Select option 2.
2. Enter the runway number (1 to N).
3. Enter the segment number (1 to M).
4. Enter the new status (L = Free, O = Occupied, M = Maintenance).
5. The program will update the status of the selected segment.

*Example:*
`Enter runway number (1 to 2): 1`
`Enter segment number (1 to 3): 2`
`Enter new status (L = Free, O = Occupied, M = Maintenance): O`
`Status updated.`

**Option 3: ADD A NEW RUNWAY**
*Required condition:* The maximum number of runways must not have been reached.

*Steps:*
1. Select option 3.
2. Enter the length of the new runway (number of segments).
3. The program will initialize the runway with all segments set to Free status.

*Example:*
`Enter the length of the new runway (number of segments): 3`
`Runway added successfully.`

**Option 4: DELETE AN EXISTING RUNWAY**
*Required condition:* The runway must exist.

*Steps:*
1. Select option 4.
2. Enter the number of the runway to delete (1 to N).
3. The program will delete the selected runway and reorganize the remaining ones.

*Example:*
`Enter the runway number to delete (1 to 2): 1`
`Runway deleted successfully.`

**Option 5: EXIT**
*Description:* Terminates the program.
*Steps:*
1. Select option 5.
2. The program will free the used memory and close.
