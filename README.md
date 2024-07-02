# "Schakelboekje" application
The purpose of this code is to develop a prototype for the "schakelboekje" application. This application aims to modernize and replace the current "schakelboekje" process with a dynamic system. 
This system will enable superusers to communicate switch states to end-users in real-time. 
Additionally, the application will assist users by providing functionality to calculate feeder sections that need to be shut down for maintenance work.  
## How to run locally
### The code
This code repository consists of three html files:

index.html: Contains the application interface for standard users (visual purposes only).  
editor-login-page.html: Provides functionality for superusers to change switch states.  
login.html: Implements a login page to transition from the standard application to the superuser interface (username and password: "delijn").    
  
To run the application:

Clone the GitHub repository to your preferred code editor.  
Once cloned, open the index.html file and run the code.  
The application will launch in your default internet browser.  

### Sample data
Currently, the code makes use of files stored in this Github repository. These files are currently being accessed using an URL in the code.  
For example: https://raw.githubusercontent.com/XanderPeeters/Schakelboekje/master/Voedingen-stadsplan.geojson  
We use these files to load in the geojson data about the switches or the feeders and to show them on the map.  
All the data that is being accessed by the code can be found in the "Sample data.zip" folder.    
It is not necessary to download this zip-folder. The github repository is public and the sample data is directly accesible by the code.  
