# Resources for developers

## Getting started
First make sure you have WPIlib and Vscode installed - [instructions](https://docs.wpilib.org/en/latest/docs/getting-started/getting-started-frc-control-system/wpilib-setup.html)

Install [GitHub desktop](https://desktop.github.com/) (even if you want to use git from inside vscode, this is helpful)

A [git tutorial](https://guides.github.com/activities/hello-world/)

Create an account on [github.com](https://github.com) and give your userid to one of the programming mentors to be added to our organization.

## Some particular topics to understand and get code from

* [Getting started with FRC development](https://docs.wpilib.org/en/latest/docs/getting-started/getting-started-frc-control-system/intro.html)
* [Command based programming](https://docs.wpilib.org/en/latest/docs/software/commandbased/index.html) - the basics of programming the bot.
* [Changes to command based programming](https://docs.wpilib.org/en/latest/docs/software/commandbased/command-based-changes.html) - it all changes this year
* [Kinematics and odometry](https://docs.wpilib.org/en/latest/docs/software/kinematics-and-odometry/index.html) - have the robot understand where it is on the field
* [PIDSubsystem](https://docs.wpilib.org/en/latest/docs/software/advanced-control/controllers/pidcontroller.html) - a class to drive a motor to a particular position using a PID
* [Vision](https://docs.wpilib.org/en/latest/docs/software/vision-processing/index.html) - see especially the GRIP and RPi options
* [Trajectory generation](https://docs.wpilib.org/en/latest/docs/software/wpilib-tools/path-planning/wpilib-trajectories/trajectorygeneration.html) - drive the robot smoothly from point A to point B

## Tools and Links

* [Robot builder](https://wpilib.screenstepslive.com/s/4485/m/26402/l/255426-overview-of-robotbuilder) - Use this to bootstrap a new robot
* [WPILib overview](http://wpilib.screenstepslive.com/s/currentCS/m/java/l/599696-what-is-wpilib) - also see the links on the side about using actuators, sensors, CAN devices, etc
* [API Documentation for Phoenix](https://phoenix-documentation.readthedocs.io/en/latest/index.html) - Using the talons
* [API Documentation](https://first.wpi.edu/FRC/roborio/release/docs/java/) - The gory details of all the APIs in WPIlib

## JSON links for robots

These are the "vendordeps" that bring in third party libraries. Use the "manage vendor dependencies" command in vscode, and if you do the online option, paste one of these urls

* [ADIS16448](http://www.maven.highcurrent.io/vendordeps/ADIS16448.json)
* [Phoenix](http://devsite.ctr-electronics.com/maven/release/com/ctre/phoenix/Phoenix-latest.json)
