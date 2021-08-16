# css position & layout

- positions: static/relative/fixed/absolute/sticky
- relative:An element with position: relative; is positioned relative to its normal position:
     {
         posiion:relative;
         left:20px;
         bottom:20px;
     }
- fixed: An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled:
      {
          position:fixed;
          left:0px;
          top:0px;
      }

- absolute
     {
         position:absolute;
         left:20px;
         bottom:20px;
     }

- sticky: a mixture of static and fixed

- zindex:gisplaving infront of an element
         
        h1 {text-align: center;}
        header{
        z-index: 1;
        }
- inline elements:Compared to display: inline, the major difference is that display: inline-block allows to set a width and height on the element.

    header h1{
    color: white;
    border: 2px solid white ;
    padding: 6px 12px;
    display: inline block;
    border-radius: 26px ;
    text-align: center;
}

- white-space: nowrap;
       nav ul{
    white-space: nowrap;
    }
                     white-space is a CSS property that helps control how whitespace and line breaks within an element's text are treated. ... nowrap: Multiple whitespaces are collapsed into one, but the text doesn't wrap to the next line.
- 

    


