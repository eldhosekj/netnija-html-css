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
    nav{
    position: sticky;
    }

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
- Width and Maximum width
The difference is following. width keeps the size of the object stable. Lets say you put width: 700px for an image. ... At the same time, when you set max-width:700px it will re-size up to 700px but when the screen goes smaller and the images doesn't fit in the screen it will automatically re-size it to fit the screen
  maximum width=>
    nav ul{
    max-width: 1200px;
    }
- width=>
   .banner img{
    width: 100%;
    }
- Box sizing:The CSS box-sizing property allows us to include the padding and border in an element's total width and height.
          main{   
          box-sizing: border-box;
          }

    


