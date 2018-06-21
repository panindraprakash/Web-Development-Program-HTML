# Web-Development-Program-HTML
Basics, DOM Structure, HTML5 elements.

A) Instruction 

1) A sample html document 

    <!DOCTYPE html>                                                 // Defines this document to be HTML5
    <html>                                                         // Root element of an html page
              <head>                                              // Contains meta information about the documents
                           <title>Page Title </title>            // Title for the document
              </head>
              <body>                                            // Element contains visible page content
                           <h1> This is heading </h1>          // h1 defines a large heading
                           <p> This is a paragraph </p>       // p defines a paragraph
              </body>
    </html>

2) html tags - <tagname>content goes here.....</tagname>tagname>

3) html page structure 

<html>
              <head>
                           <title>Page Title </title>
              </head>
              <body>
                           <h1> This is heading </h1>
                           <p> This is a paragraph </p>
              </body>
</html>

B) HTML BASIC
1)     html headings      <h1>to<h6>xa
<h1> defines the most important heading
<h6> defines the least heading

Example  <h1> This is heading 1 </h1>
         <h3> This is heading 2 </h3>
         <h6> This is heading 3 </h6>

2) html paragraphs  <p> tag
example <p> This is a paragraph</p>
        <p> Hello Welcome</p>

3) html links <a> tag
   example <a href="https://hi.com"> This is a link </a>
           href=The links destination is specified in the href attribute

4) html imag      <img> tag
          the source file (src),alternative text (ah),width and height are provided as attributes

   Examplea <img scr = "hello.jps" alt.hero.com"width=104' height="142">

5) html buttons             click <button>
    example  <button> Click Me </button>

6) html list  <ul> tag (Unordered List) or 
              <ol> tag (Ordered /Number List) followed by 
              <li> tag (List Items)

   example   <ul>
                   <li> Coffe </li>
                   <li> Tea   </li>
                   <li> milk  </li>
             </ul>
 tag (

C) HTML ELEMENTS 

                1) (i)  Start tag 
                   (ii) End   tag
                                  example    <p> My First Paragraph </p>

                2) Nested HTML Elements
                                        Html elements can be nested.
                                        All html documents consist of nested html elements.
                                        Example     </DOCTYPE html>
                                                    <html>
                                                             <body>
                                                                    <h1> My first heading <h2>
                                                                    <p> My first paragraph <p>
                                                             </body>
                                                     </html>

                    3) Empty html elements
                                           Html elements with no content are called empty elements. 
                                           <br> is an empty element without a closing tag
                                           Html does not  required empty elements to be closed.
                                           But if you want stricter validation or if you need to make your 
                                           document readable by xml parsens you must close all html elements properly.


D) HTNL ATTRIBUTES

              All html elements can have attributes.
              Attributes provide additional informat about an element.
              Attributes are always specified in the start tag.

 List of attributes

 1) href
          Used is html link tag.
          The links destination is specified in href attributes.
          Example
                   <a href "https://mychoultry.com">This is a link</a>

2) src
        Used in html image tag
        The filename of the image source is specified in the src attribute.
        Example
                <img src="img_grass.jpg">

3) width and height
                     Used in html imag tag.
                     Images in html have a set of size attributes which specifies the width and height of the image
                     Example
                             <img src="img_grass.jpg" width="500" height="600">

4) alt
       Used in html imag tag.
       The value of the attribute can be read by screen readers
       This way someone listening to the webpage eg:a blind person can"hear" the element.
       Example
               <img src="img_grass.jpj" alt="grass need's water">
       Note The "alt" attribute is also useful if the imag does not exist.

5) style
         Used in html paragtaphs and html heading elements
         The style attribute is used to specify the styling of an elements like color,font,size etc.
         Example
                  <p style="color:red">I am a paragraph</p>

6) The lang attribute
                      used in the html tag.
                      The language of the document can be decleared in the <html>tag.
                      Example
                              <!DOCTYPE html>
                              <html lang-"en_us">
                              <head>      </head>
                              <body>      </body>
                              </html>

7) title 
          Used in the html paragraphs,html heading elements and in img element.
          The value of the title attribute will be displayed as a tooltip when you mouse over the paragraph.
          Example
                  <p title="I'm a tooltip">
                  this is a paragraph.
                  </p>






