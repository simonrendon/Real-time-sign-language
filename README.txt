**************************
INSTRUCTIONS TO INSTALL
**************************

Requirements:

	Python 3.7.9
	Visual Studio Build Tools 2019 -- C++ build tools
	Webcam
	
	**************************************
	******* THIS IS VERY IMPORTANT *******
	**************************************
	
	These files MUST BE INSTALLED for our project to work correctly.
	We've included a README.txt in the "install" folder. Please read
	and install before proceeding with the project installation.
	
	
	
**************************
Instructions (Windows):
**************************
	Our recommended method is to create a virtualenv to start with a fresh project.
	Run the following command in PowerShell or command prompt (cmd):
		py -3.7 -m venv .venv
		
	After the virtualenv has been created, run the following command:
		.venv\Scripts\activate.bat
		
	Now that we have activated our virtualenv, we must install the required packages.
	Run the following command:
	
		python -m pip install RealTimeObjectDetection-main\Tensorflow\models\research\.
		
		and then run this command after the previous command is finished:
		
		python -m pip install -r requirements.txt
		
	This may take a while depending on your hardware and internet connection.
	This will download over 2GBs of packages. You may see some errors, ignore these.
	After the packages have been downloaded and installed, run the command:
		jupyter lab
		
	This will open up a JupyterLab environment downloaded from the pip packages.
	Navigate inside the RealTimeObjectDetection-main folder and open the RunProgram notebook.
	
	Run all the commands and the program will start.
	