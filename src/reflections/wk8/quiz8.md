# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
A package.json is a JSON file that exists at the root of a Javascript/Node project. It holds metadata relevant to the project and it is used for managing the project’s dependencies, scripts, version and a whole lot more.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
You need to have the package before you reach the point you want to deploy your application so that there are requirements loaded/determined.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
Web App -You can open our web app by visiting app.logdna.com, or by using the Heroku CLI:
by visiting the Heroku Dashboard, selecting the desired Heroku application, and then choosing LogDNA from the Add-ons menu.

Command Line Interface
LogDNA provides its own command line interface (CLI)
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
By merging
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
You need to make sure that your changes don't occur live. If you have a working app, leave it working and make changes to a branch until you've made sure it is ready for use, then merge.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Prior to deploying.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merge
```
