
## Documentation
This documentation contains a set of guidelines to help you during contribution and
a set of rules that is requested to be followed. We are happy and thankful to welcome all the legit 
contributions from anyone willing to improve/add new implementations to this project



## Pre Requisites
- Download and install the latest version of Git (https://git-scm.com/downloads)
- Create a GitHub account
- Download the latest version of Android Studio. Check for updates if any to avoid any issue 
  during gradle build.
## Setting up the Project
1) Star this repository
 2) Fork this repository
 3) Clone your forked repository
	git clone https://github.com/<your_username>/Samarpan.git
	(Place the screenshot)
 4) Use this link to clone this repository inside you local machine in the android studio IDE  
 	a) Open up android studio  
	b) Click get from version control  
	c) Paste the link to clone the repo
5) The repository is cloned in your local machine.
## Instructions to follow while contributing to SAMARPAN
Follow proper naming convention

1) Naming convention of the layout files: While creating a layout or a fragment file it should follow the following naming convention:
					  "type of user(user/NGO)""__""what is that page for""_""if fragment mention fragment"
					   for eg user_login_fragment, ngo_dashboard.

2)Naming convention of the kotlin files: All the files where the backbone of the application would be coded will have a similar naming 
				         convention as the layout
					 "type of user(user/NGO)""what is that page for""if fragment mention fragment"
					  for eg userLoginFragment, ngoDashboard.

3) Defining views:The variable defining views or used for view binding should follow this convention:
                 "type of view""page it belongs to""Purpose of the view"
		  for eg btnUserSignUp.

4) Theme color: Theme color has been defined inside colors.xml(put link) with proper naming convention
                Use the theme color in the entire application according to the wireframe design provided.

5) Defining Strings: All the elements inside the xml file under android:text="" should not be harcoded text. Define all the text inside strings.xml
		     with proper naming convention:
		     all the name inside a string elements should be like this ""(ask hitesh the format and add it like above)
## Guidelines for raising a new issue
Comment on any existing issue raised by maintainers or raise an issue

 All the issues should follow a set of rules 
  1) Each issue should have an appropriate and short title like "Bug in user authentication"
  2) Each issue should have appropriate tag associated with it.
  3) Be specific with the changes you want to implement through the issue 
  4) Whenever a participant raises an issue, by default it would be assigned to that participant due to obvious reasons.
  5) Attach a screenshot/clip if applicable
## Contributing to the project
1) Start working on the issue once the maintainers have reviewed the issue 
 2) Create a new branch inside android studio before working on any changes
    the branch created should have the following convention. 
    "your name/username""related work"
     for eg"xyzUserRegistration"(Add the screenshot)
 3) Perform the necessary changes or updation
 	a)Make sure anything you do is only related to what issue you are working on 
	b)Ensure that your changes apply to all screensizes
	c)Comments make the code easier to examine so make sure to comment wherever needed
	d)Before committing perform the necessary testing and check the working on the emulator or a device
	e)Make a small clip or take screenshots before and after making changes.

 4) Track your changes 
     git add .
 5) Commit all the changes.
	a)The commit message should be relevant and short.(usually title of pull request) 
	b)Make sure to condense your changes into a single commit(add the screenshot for commit button)
 6) Push the committed changes in your feature branch to your remote repo.


## Guidelines for raising a pull request
1)To create a pull request, click on compare and pull requests. Please ensure you compare your feature branch to the desired branch of the repo you are suppose to make a PR to.(Add the screen shot)  
2)Each pull request should have appropriate and short title 
3)The description should be ellaborate explaining the changes with proper screenshots or the clip of the test done on device/emulator  
4)Look out for possible merge conflicts.  
5)Please be patient enough. The project maintainers/mentors would review it as per their schedule. Please do not start putting comments like "Please check this" etc.
## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

