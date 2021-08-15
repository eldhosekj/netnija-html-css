class and selectors:

- <p ciass="error">rrwertetertyyyeyyyy</p>//
.error{
    color: crimson;
}
                 =>used for adding red color for a particular paragraph

- <p class="success feedback">rrwertetertyyyeyyyy</p>//
 p.success.feedback{
    border: 1px dashed brown;
}
              =>used for adding green color and dashed border for a particular paragraph


-  <div id="content">//(parent)
  #content{
    background-color: cornflowerblue;
    padding: 20px;
}
               =>replaces an element with a generated value. Objects inserted using the content property are anonymous replaced elements.

- a[href*=".in"]{ =>using achor tag and* to edit the links with its last text


## INHERIT

- 
div{
    color: lawngreen;
    border: lightseagreen;
    margin: 40px;
    font-weight: bold;
}
p{
    border: inherit;
    margin: inherit;
}


