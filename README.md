# u0941152-Project3 Will Graham

## How to Run:
There is a hidden launch.json folder configured for a vscode debugger. This will let any user run the project without the need for a command line. Simply select the problem and parameters desired within a vscode run & debug browser, and hit start. As long as CoppeliaSim is running and required libraries are installed, there shouldn't be any problems

## File Structure
The launch.json folder interacts with the lbr4_trajopt.py script. Based on parameters passed in through the launch.json, different aspects of this script will be run. The lbr4_trajopt.py relies on lbr4_kinematics.py, vrep.py, vrepConst.py, and the lbr4_environment.ttt CoppeliaSim files. The full project can be viewed within the word document and pdf. 