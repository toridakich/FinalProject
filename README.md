# Rubric-file-structure
File structure for iX Full stack Project 

## Project Setup

### Create Project Via CLI

Navigate to the project file

```bash
cd Rubric-file-structure
cd Admin Panel
```
Create project

```bash
ng new admin-panel
```
Do the same for projects:

Consumer Mobile App

```bash
ionic start consumer-mobile-app
```

Provider Mobile App

```bash
ionic start provider-mobile-app
```

API

Create file structure with server.js located in a folder called api

```bash
mkdir api
cd api 
npm init
```

### Project Structure 

Generate a mark down table similar to the one in root directory of this project. The following website can be used to do https://www.tablesgenerator.com/markdown_tables or edit the Project File Structure.txt file in the root directory

Only files included in this mark down table with be marked!

Ensure that the files included in the mark down table related the sections specified in the table.

Please include the mark down table in the README.md file in the root directory of the project.

### Example of Project Structure 

| PROJECT             | COMPONENT          | FILE NAMES                                                                                                                                                                              |
|---------------------|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Consumer mobile app | Login              | /Users/toridakich/Desktop/iXperience/Rubric-file-structure/consumer-mobile-app/consumer-mobile-app/src/app/home              
| Consumer mobile app | Registration       | /Users/toridakich/Desktop/iXperience/Rubric-file-structure/consumer-mobile-app/consumer-mobile-app/src/app/registration
| Consumer mobile app | User Profile       | /Users/toridakich/Desktop/iXperience/Rubric-file-structure/consumer-mobile-app/consumer-mobile-app/src/app/profile                
| Consumer mobile app | List of Properties | /Users/toridakich/Desktop/iXperience/Rubric-file-structure/consumer-mobile-app/consumer-mobile-app/src/app/property-info     
| Provider mobile app | Login              | /Users/toridakich/Desktop/iXperience/Rubric-file-structure/provider-mobile-app/provider-mobile-app/src/app/home              
| Provider mobile app | Registration       | /Users/toridakich/Desktop/iXperience/Rubric-file-structure/provider-mobile-app/provider-mobile-app/src/app/registration
| Provider mobile app | User Profile       | /Users/toridakich/Desktop/iXperience/Rubric-file-structure/provider-mobile-app/provider-mobile-app/src/app/profile                
| Provider mobile app | List of Properties | /Users/toridakich/Desktop/iXperience/Rubric-file-structure/provider-mobile-app/provider-mobile-app/src/app/property-details
| Provider mobile app | List of Bookings   | /Users/toridakich/Desktop/iXperience/Rubric-file-structure/provider-mobile-app/provider-mobile-app/src/app/booking-requests
| Admin Panel         | Users              | /Users/toridakich/Desktop/iXperience/Rubric-file-structure/admin-panel/admin-panel/src/app/components/user                                  |
| Admin Panel         | Bookings           | /Users/toridakich/Desktop/iXperience/Rubric-file-structure/admin-panel/admin-panel/src/app/components/booking                                 |
| API                 | Users              | /Users/toridakich/Desktop/iXperience/Rubric-file-structure/API/api/src/api/user-routes.js                                                               |
| API                 | Bookings           | /Users/toridakich/Desktop/iXperience/Rubric-file-structure/API/api/src/api/booking-routes.js                                                          |

### Change Git Remote URL

Create new repository on GitHub.

Change the git URL associated with the project 

```bash
git remote set-url origin < new URL of your GitHub project (click 'Clone or download' button on GitHub site to see URL) >
```

Ensure that the git URL has been updated.

```bash
git remote -v
```

