# Lesson 3 Hovers,transitions and shadows
For Hover 
    It is used to show style or css properties on buttons when we hover on them.
    we generate something which is called as pseudo class.
    syntax:  .b1:hover{
        color:blue;
    }
    so what it does is when i hover on b1 button its text color would be blue no matter what i,ve written in the .b1 class.

For active
    It is used to show style or css properties when we click on a button.
    we generate a pseudo class here as well.
    syntax:   .b1:active{
        color:green
    }
    so what it does is when i click on b1 button it will change its text color to green.

For Transition
    It is used transition the styles of button between idle state,hover and active state smoothly .
    We generate a pseudo class here too.We can choose what we want to transition like background-color,color etc.
    Transition takes two value , first what we want to change and how long it should take to transition.
    synatx:  transition: color 0.15s,background color 0.1s; 

For shadow
    It is used to show a shadow of a button. It takes 4 values.(THEY ARE NOT SEPERATED BY COMMAS)
    Syntax: box-shadow: Horizontal pos.  Vertical pos.  bluriness of the shadow  color
    eg. box-shadow : 5px 5px 5px black;

Opacity: a css property, it takes value betwwen 0-1.
