# "Schakelboekje" application
The purpose of this code is to develop a prototype for the "schakelboekje" application. This application aims to modernize and replace the current "schakelboekje" process with a dynamic system. 
This system will enable superusers to communicate switch states to end-users in real-time. 
Additionally, the application will assist users by providing functionality to calculate feeder sections that need to be shut down for maintenance work.  
## How to run locally
### The code
This code repository consists of three html files:

- `index.html`: Contains the application interface for standard users.  
- `editor-login-page.html`: Provides functionality for superusers to change switch states.  
- `login.html`: Implements a login page to transition from the standard application to the superuser interface (username and password: "delijn").    
  
To run the application:

1. Clone the GitHub repository to your preferred code editor.  
2. Once cloned, open the index.html file and run the code.  
3. The application will launch in your default internet browser.  

### Sample data
The code currently accesses files from this GitHub repository using URLs within the code. For instance:

Example URL: https://raw.githubusercontent.com/XanderPeeters/Schakelboekje/master/Voedingen-stadsplan.geojson  
These files, such as geojson data for switches or feeders, are utilized to display information on the map within the application.

All the necessary data for the application is located in the [Sample data.zip](Sample%20data.zip) folder. It's important to note that downloading this zip folder is not required. The GitHub repository containing the sample data is publicly accessible, allowing the code to access this data directly.
