To run the project :-

Windows:

Install virtual environment:

	'pip install virtualenv'
	
Create a virtual environment:

	'virtualenv venv(name_of_venv)'
	
Activate virtual environment

	source venv\Scripts\activate
	
Navigate to the directory

	cd websockets
	
Install the required packages

	pip install -r requirements.txt
	

Run myapp application with:

	uvicorn myapp:app --reload

