## Purpose of this "Web Application"
This project aims to provide a visual dashboard for relationships with other teams within an organization. It can show how you feel your relationship with their team is as a combination of your relationship with each respective sub-team. You can also enter a trend indicator to show how your relationship is changing at the moment, and a description for further explanation for each sub-team.
## Usage
### How to use
The data in `data.json` is sample data to demonstrate the functionality of this dashboard. In order to change it to fit your own needs, you will need to alter `data.json` using the same structure currently in use.
#### Fields in `data.json`
- `subteams`: Where you enter the sub-team objects under a team.
- `name`: The name of the team or sub-team.
- `relationship`: How the relationship with that team is. Entered on a 0-4 scale, with 0 being the worst and 4 being the best.
- `trend`: How the relationship is changing/trending. Entered on a -2-2 scale, with -2 being the worst, 0 being neutral, and 2 being the best.
- `description`: More information about that team, potentially including details about why the relationship is the way it is, as well as what can be done to improve it.
### Files
There are various files that are part of this project. Here is an overview of what each one does:
- `README.md`: The file you're looking at!
- `index.html`: This is the file that your web browser uses to actually render the dashboard. It contains the html as well as the javascript to look at the data.
- `data.json`: This is where you enter the data about the various teams and sub-teams. As a user of this program, this is where you should be spending most/all of your time.
- `bootstrap.bundle.min.js`: Part of the bootstrap framework used to create the dashboard. Learn more [here](https://getbootstrap.com/).
- `bootstrap.min.css`: Part of the bootstrap framework used to create the dashboard. Learn more [here](https://getbootstrap.com/).
- `custom-style.css`: Custom styles to override some of the bootstrap framework to customize the dashboard to fit NBCUniversal's style.
