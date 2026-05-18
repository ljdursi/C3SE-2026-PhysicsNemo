# C3SE PhysicsNeMo workshop - Resources

## Cluster

  * Axis: [axis-raplabhackathon.axisportal.io/apps](https://axis-raplabhackathon.axisportal.io/apps)
  * Command to run on curiosity: `/lustre/fs01/bootcamps/scripts/End-to-End-AI-for-Science-v4/physicsnemo-script.sh`

## Code

  * PhysicsNeMo: [github.com/NVIDIA/physicsnemo](https://github.com/NVIDIA/physicsnemo)
    * Docs: [developer.nvidia.com/physicsnemo](https://developer.nvidia.com/physicsnemo)
    * Examples: [github.com/NVIDIA/physicsnemo/tree/main/examples](https://github.com/NVIDIA/physicsnemo/tree/main/examples)
  * This workshop: [Openhackathons-org/End-to-End-AI-for-Science](https://github.com/openhackathons-org/End-to-End-AI-for-Science)

## Slides

## Instructions for Starting the Job

### Log into axis

* Login to [Axis](https://axis-raplabhackathon.axisportal.io/apps) with your Axis (C3S-26) credentials 
* Use Chrome browser or make sure your browser does not block pop ups

### Open a web shell

* Enter your Curiosity credentials
* Click on Curiosity
* Click on “Open web SSH in a new tab”
* You now have a terminal into curiosity

### Get an axis one-time username (this resets every time, you'll need to get a new one if you've used one to log in at all)

* Go back to the Axis console
* Click on “Curiosity cluster” and then Click on “Use a desktop SSH client”
* Enter your Curiosity credentials
* Click on “Connect with SSH client”
* Copy that “Auto-login username” – we’re going to use it in the next step.  Save it somewhere safe

### Start the job

* In the web terminal, rn the command /lustre/fs01/bootcamps/scripts/End-to-End-AI-for-Science-v4/physicsnemo-script.sh (Use tab autocomplete)
* Select "1)  Run End to End AI for Science Bootcamp Material" by typing 1 and hit on the enter key. Please wait for about 10mins for the loading process to complete and follow the on screen

### Connect to the Notebooks

* In your web terminal when everything is completed, you will see a message along the lines of "Please enter the following command into your terminal" - it's a long command that starts with `ssh`. 
* Start a _new_ terminal _on your laptop_ (Terminal.app on Mac, PowerShell on windows, or your favourite terminal on Linux, for example), and paste that ssh command in.
* You can now open a new tab on your browser to https://localhost:9999 to see the Jupyter notebook
