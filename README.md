# CSCE361Project

### This program is no longer connected to the database, but it will open if you run it in Visual Studio
#### The files in this repository are the source files released from the original repository, due to the original repository being private.

<br />
Project Topic: Voting System


Capstone Project Group 3: Isaac Baysinger, Noah Hudson, Arielle Monson, Brady Smith

## How to use our program
There are several roles with increasing privileges. These roles will determine how a user interacts with the program. 
### User Role
- As a standard user, you have access to the basic functionality of the voting system. Once the app is open you will be asked to either login to your existing account or to create a new account. 
- After you have logged in, you will be met with our home page where you have a few different options. 
  - If you already know what candidates/issues you would like to vote for, you can go ahead and click the button to Vote Now. 
    -   This is only accessible from the home page
  - If you would like more information on either candidates or issues, follow the respective link under the vote button to find parties and bios for candidates or descriptions of the issues being voted on in the current election. 
    - This is only accessible from the home page
  - If you would like to see how you have voted previously, click on the My Votes tab at the top of the page. From this page you will be able to use the dropdown menu to select any previous election to view your past votes. 
  - If you would like to see the results of a previous election (results for the current election will be available when voting closes), you'll want to click on the Results tab at the top of the screen and use the dropdown to select the past election you are looking for. 
- Aside from the voting ballot page, every other page can be accessed at any time
  - You can only vote once per election 
- Be sure to logout when you are done using the application using the logout tab in the upper righthand corner
### Administrator Role
- Same access and navigation as Users
- Additional access to the Admin tab (found to the left of the logout tab)
  -  Site Admins are able to see who voted in a certain election, but not how a voter voted
  -  Site Admins can add a new election, as well as candidates, issues, positions, and parties associated with an election under their respective options in the admin tab
### Developer Role
- Same access and navigation as Administrators
- Additional access to the Admin tab
  - Developers are able to edit user accounts and roles, see how votes were cast for Issues and Elections, and edit what roles are available under the respective Admin tab options
