           # myhexapod_robot
     Assignment2.
     Group 3(1)
     members: Pov Punleu      e20180817
              Saporn Punnara  e20180897
              Seng Seakmeng   e20180945
              Song Satyarak   e20181005
In order to run this, we need to follow the step in the following:
  1. create a folder and name it anything you like. (for ros workspace)
  2. in that folder, create a folder called "src". (the name of this folder must be "src")
  3. in "src" folder, create a ros pakage named myhexapod_decription by typing the command in terminal : roscreate-pkg myhexapod_decription urdf
  4. copy all the files and folders (in "myhexpod_robot" folder that you've downloaded) and past them in the ros pakage "myhexapod_description" folder
  5. in the first folder, let create ros workspace by typing command in teminal: catkin_make
  6. after creating ros workspace, in the first folder you'll see all the three folder: build devel src
  
  7. let source the file by typing command in terminal: source devel/seup.bash
  8. launch "move it assistant" by typing in terminal: roslaunch moveit_
  9. set up "assistant" by typing in the terminal: roslaunch moveit_setup_assistant setup_ass
  10. after this finish, a new window "moveit assistanta' will pop up.
  11. choose "create new Moveit configuration pakage and browse the "myhexapod_description.urdf" file in pakage "myhexapod_description/urdf"
  12. afer browse your file, click load file and continue your work with "moveit assistant". (for more detail let's visit the video: https://youtu.be/IS3JIV45rh0)
  13. after generate your pakage in "moveit assistant", let source the file again by typing command in terminal: source devel/seup.bash
  14. launch the new pakage (that you've just generate from moveit assistan). Typing command: roslaunch "name of pakage" demo.launch
  15. finaly, the rvis window will pop up. enjoy with your robot.

