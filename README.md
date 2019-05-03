# RoboDog
VREP Simulation of a Dancing Robot Dog
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <div class="header">
        <h1 style="text-align:center">Sourabh Pardeshi - Intelligent Robotics Project Report - 801081931</h1>
    </div>
   
<div class="text_content">
    <h1>Simulation of a Dancing Dog Robot in VREP</h1>
    <p>
        <h3>Summary:</h3>
            The main objective of this project was to simulate the robot shown in above video in VREP using the
            techniques from the Modern Robotics textbook. In this project i have studied the Forward Kinematics
            & Inverse Kinematics for the robot.
        <h3>Description:</h3>
            For the robot style i have imported a stl of the Spot the robot dog by Boston Dynamics. The script RoboDog
            is the main script that generates body movements & controls another non-threaded script which is in charge
            of generating the walking movement. Since, VREP's simulation class automatically retrieves the updated
            co-ordinates of the robot tips/end-effectors and generates the trajectory and path, i have modified the
            MoveBody and BodyTarget scripts to replicate the motion of the robot doing somewhat of a Moonwalk.
        <h3>Results:</h3>
            The graph of the robot's movement and the calculation timings are in the screenshot video.
    </p>
    <video width="320" height="200" controls preload> 
    <source src="./RoboDog_Large.mp4"></source> 
    <source src="./RoboDog_Large.webm"></source> 
    </video>
</div>
    </div>

</body>
</html>
