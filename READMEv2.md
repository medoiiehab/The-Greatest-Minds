# the greatest minds

### second source is w3schools especially the HOW TO link (https://www.w3schools.com/howto/default.asp)
 ### the getBoundingClientReact source https://developer.mozilla.org/en-US/docs/Web/API/Element/getBoundingClientRect.
 ### the get attribute source (helped in the syntax alot and know when to use it) - https://developer.mozilla.org/en-US/docs/Web/API/Element/getAttribute

## I added new things like the photos and used w3.css library as it was a quick study , This is inspired by my passion toward science and scientists.
### so newton was first because he made a new branch and opened the door to bigger questions to answer.
### then einstien, stephen hawkings and neil degrasse tyson (I know there are more smarter people who made bigger diffrences in the world than tyson, but he is the livin' one) other people who should make it to the list and I may make a top 10 (for myself to see and brag about, even though I am a beginner)

##  the process of what I made 
### the nav bar list is made by making a list element and then making an anchor element(link) and then making the name of the link by the datanav(the nav part is replacable) and then making the link by fetching the ID and then make it as a variable and then add it to a '#' hashtag after that we append the anchor to the list and then we make a doc fragment to improve the performance (as it runs in  the background) then appending the lists to it and then appending the fragment to the NAVBAR. 

### then we removed the class that is there (youractiveclass) And yes I changed it because it wasn't working for some reason from your-active-class just to prepare for the getBoundingClientRect() part where I tested my screen saw the coordination and then added it in an if conditional (so what excatly happened is that I said get the variable where it fetched all of the sections and then made a loop for a function to happen that stated that if the the viewpoint is <this> this means the numbers, where the client is seeing it that way then add the class here and then when they don't see it,  remove the class (it became easier to know how to make the code after I removed the other class because it was working always,,,really thankful for the tutor's instructions).) 

## and the smooth scrolling (thx to tutor who gave me a clue on how to do it) I made it inside the loop while the navbar is being made. also just made a mediaquery to the css to make it responsive to the mobile phones according to the guidelines


# how to modify it 

### the constant name are:
### navSection(which fetchs all of the section elements (used for navigation bar and navigating in general))
### navID(which gets the ID of the parent where the dynamic nav bar exists)
### fragmentDoc (makes a fragmented document(helps in performance))
### makeList (makes a LI element) and the make link( makes anchor)
### function makingNavBarList (used to make the list that is also called as the top navigation bar)
### function removeCLass(used to remove a class)
### parameter viewedNow (means that whatever is viewed on the screen at the moment)