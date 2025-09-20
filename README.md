# CSE-Examination

Instructions:

Fork this repo and clone the fork onto your local computer.

Make sure to create a local branch name examination/midterm-python-exam and accomplish the task given in that branch.

Modify this README.md file to explain your code.

Push the activity back to your forked remote repo.

Ortega, John Vincent Explanation.
    → The program begins with the function normalize_direction(cmd) which takes user input, removes extra spaces, and converts it to lowercase for consistency. In this function, it checks if the input matches common direction commands like "n" or "north" and returns a standardized single-letter code such as 'N'. Similarly, it converts inputs like "s/south", "e/east", and "w/west" into 'S', 'E', and 'W' respectively. If the user types "stop", the function returns 'STOP' to signal the program to end. If the input doesn’t match any expected command, it returns None, marking it as invalid. The main() function starts the GPS tracker at the origin (0, 0) and informs the user of the available commands. The program enters an infinite loop, asking the user to enter a direction each time. Depending on the normalized command, the program updates the coordinates: north increases y, south decreases y, east increases x, and west decreases x. After each valid move, it prints the current position so the user can track their movement. When the user enters 'STOP', the loop ends, and the program shows the final position, also checking whether the user has returned to the origin (0, 0).
