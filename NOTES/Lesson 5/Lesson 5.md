# TEXT BASED EXCERCISES.
CSS PROPERTIES:
1.font-style:italic
 It is used to change the text to italic,oblique etc.

2.font-weight:bold
 It is used to change the text to bold.

3.text-align:center
 It is used to set the alignment of the text.

4.font-family:aerial.
 It is used to change the font family of the text .
 The browser by dafault supports some font family like aerial,times new roman,etc For other font family

5.font-size:20px;
 It is used to set the font size.
 
6.Line-height:2px
 It is used to set the line spacing.

7.width:20px
 It is used to set the width of the para(Or the line).

To add a special character or symbol we use html entity.eg for a checkmark we use &#x2713; .

A class can be targeted by multiple styles by using multiple selector ,but the selector that is more specific has higher priority.

We can target all the pars in a code by 
p{
    font-family:aerial;
}
This means that all the paras in the code are gonna have aerial as a font-family no need to write again .We set different css properties.

NOTE: To target a specific word in a line of text we use a text element .
There are many types of text element like storng element(bolds the text by default),u element(undelines the text by default), span element it has no default style etc.
eg<p>
     My name is <span class="n">Sid</span>
  <p>
  .n{
    color:red
    text-decoration:underline
  }

For  adding spaces between words use "margin-left".


