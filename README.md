# groupcyoawithstyles

With Github you must publish your work and a public repo and include this content in the

Read.me file 

Also when submitting put your repo link into the comments 

Reviewers must be added as collaborators so they can edit the Read.me and put in their feedback

// Your Names: Elizabeth Trotter, Treece Hillstrom

// Date Revised: 10.20.2023

// Exercise: Group CYOA with Styles

// Brief Description: Created a new website that is a choose your own adventure game with styles. 
Requires: Text to tell the story, Links to options that progress story, 9 pages minumum, at least 3 types of endings, Collaborate with Github, Create a new story with a new flowchart, This is a group grade, One page write up on each group member and what they worked on and what it was like to work with them, Code will be submitted and the doc file for each person, Link to the Repo in the comments

# Peer Reviewed By: George Haddad
# Peer Review Comments: I like the story, it's a little silly. A coupld of things that would have saved you guys a ton of headache is instead of using percents for the image heights you could have used vh as the unit. For example if you make a class like...

# .imageSize {
#   height: 40vh;
# }

# and you put at class on all your images they would ALL be the same height and take up the same amount of space, at least vertically.
# Another thing I would have done is also make the images a little smaller. For every page with buttons I had to scroll down to actually click the buttons.
# Also related to the buttons the only thing that you can actually click is the link text itself, the button boarder isn't clickable. to fix that I would have made # this change (I'm gonna use the button on your inded.html)

# <div>
#   <a class="buttonhover buttonpurple" href="./pages/pg1.html">Click to Start</a>
# </div>
# 
# Now your whole button is clickable.

# The last thing I'd change is more of a nitpick, but I would have one css class for all buttons and have just made IDs or Classes for the colors of the button.
# Other than that you didn't do too bad, the sight functions and has some styling that look nice.
