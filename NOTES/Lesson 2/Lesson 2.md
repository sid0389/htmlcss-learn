# Lecture 2 Css properties 
On left side we have css property and on right side we have css value eg. color:red
if we have a code like this 
eg. <style>
    button{ 
        color : red;
        width:20 px;
    }
    </style>
    <button>sub</button>
    <button>tweet</button>
so all the button will have same color and width to style every button differntly we need a HTML attribute called "class".
now we'll label each button with different classname
eg. <style>
    .b1{ 
        color : red;
        width:20 px;
    }
    </style>
    <button class="b1">sub</button>
    <button>tweet</button>
    now only b1 class will have color and width property and while recalling it , it should start with a dot like .b1{css properties}
    
    #2.1
    to convert text in bold font-weight:bold;
    to change space between two buttons eg.margin-left:2px;
