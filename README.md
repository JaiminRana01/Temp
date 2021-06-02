#Project Description

In this project, we are developing a Virtual Assistant system for desktops that is aiming towards the fast and easy daily life usage, helping users to the fullest. 

Features of the project:
→ Launching apps with facial recognition security
→ Sending mails through voice commands
→ Make yourself up to date with top news, weather forecast etc.
→ Opening websites and getting information about specific topics.

#Requirements:

1.Python 3.9
2.Microsoft Visual C++ redistributable (latest supported version)

#Installation:

###Step 1: Clone Repository
Clone repo using this link:
```
https://github.com/JaiminRana01/VirtualAssistant-AIProject.git
```

Packages:
Opencv-contrib-python
Pyaudio 
Microsoft Visual C++ redistributable (latest supported version)

To remove:
Auto face recog (5)
Tensorflow
keras

###Step 2: Set up the virtual environment.
To install libraries required for this project, you have to set up a new virtual environment.

Steps to install virtual environment module and set up a new virtual environment:

1.Open the terminal.
2.Installing the virtualenv package with pip:
``` 
pip install virtualenv
```
3.Creating a virtual environment:
Go to your project’s directory and run venv:
```
python -m venv env
```
4.Activating a virtual environment:
```
.\env\Scripts\activate
```
You can confirm you’re in the virtual environment by checking the location of your Python interpreter, it should point to the env directory.
where python

###Step 3: Installing Packages
You need to install all the required packages for this project. There is a requirements.txt present in the project directory which consists of all the required package names and their version. You have to install all the packages using this command:

```
pip install -r requirements.txt
```

You can check if all the packages are installed or not by this command:

```
pip list
```

##Usage:
Run the main.py file from the project’s directory.
At first, The assistant will ask you to input Your Name and Email Address. Type in the information and you’re good to go.

Then, it will show “say something...”. Mic will be turned on and you can give voice commands now.

1.Launch Apps
2.Send Email
3.Giving latest News
It will show and tell the latest news of today’s date as a voice output.
Voice command: News
4.Giving information about weather forecast:
it will show and tell the weather forecast as a voice output.
Voice command: weather in <city>
5.Getting information from Wikipedia:
When a user wants to search for anything, it will read the first 500 characters from the Wikipedia page and return them as a string in a well organized way.
Voice command: tell me about <topic>
6.Open any website:
It will open a website in your default browser according to voice input.
Voice command: open <website domain>

