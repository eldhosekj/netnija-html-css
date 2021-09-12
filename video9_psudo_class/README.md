# pseudo classes
- style elements when they are in a particular state: hover,focus, first child
-  section.join p:: letter{
   font-style: 1.5em;
}

- nav li a:hover{
    text-decoration: underline;
    background-color: pink;
    padding: 3px;
}
                    =>using hover tag, can do text underline and color while mouse come over the text
}
- .images li:hover{
    position: relative;
    top: -4px ;
}
                   =>using hover tag, can do a sligt
                   movement of image,hile mouse come over the image
- form input:focus{
    border: 4px dashed blue;
    outline: none;
}
                   =>using focus tag, can do a dashed outline

- form input:valid {
    border: 4px solid green;
}
                  =>using valid child class,can create green ouline for valid email and all
- nav li:first-child{
    border: 3px solid orangered;
}
                  =>using first child class,can create border fo the elements
- article p::first-line{
    font-size: 1.2em ;
    font-weight: bold;
}
                 =>use to style the fist line of the paragraph
- section.join p::first-letter{
    font-size: 1.5em;
}
                 =>use to style the fist letter of the paragraph
- section.join p::selection{
    background-color: red;
    color:green;
}
                =>we can set the backgound color while selecting a text
p::after{
    content: '...';
}
               =>we can add dots at the paragraph ending
               