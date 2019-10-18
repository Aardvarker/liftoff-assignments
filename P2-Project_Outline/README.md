# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview
“DataAccess”, as I am provisionally titling this program, will provide a simply webpage where users can enter their street(within St Louis City), and will be provided with a list of all St Louis City services on their street in the last 30 days;possibly last week...  Although something comparable is possible by searching a massive annual csv file the city provides, no other access is readily available.  I intend to do so by communicating with the city API.  I have already applied for access, and received an access key granting me GET privileges.  If this MVP works, it could lead to more advanced info, such as visualizing activity by area.  Are low income or run-down areas being neglected, exacerbating circumstances?  Etc.  At present, I am keeping features limited.

### Features
Enter Street:  User will be able to go to a URL, and enter their street.
	*Display Data:  System will access city API, search for relevant data, and display it.
	*User Login: Store user emails with user streets and zips.
   *Daily email with activity on those streets and in those zips.
  *run query by day for all days withen goal of 30 day window...  Possibly give user option on time frame(Note, this is necessary because API does not allow address in GET request
### Technologies
Python
Css/HTML/Javascript(Maybe fiddle around some with Angular?)
LAMP stack or similar... maybe learn something new...

### What I'll Have to Learn
API communication
response marshalling
better web design:  MY HTML/Javascript is horrid
scheduling/email creation
(I would like to learn a good way to display info graphically, but that may be beyond the scope of this MVP)
### Project Tracker
https://trello.com/b/PvJh9nXc/dataaccess
