HyperText Markup Language
HTML uses Hypertext to connect web pages to another
HTML has opening and closing tabs and everything else comes in between 
HTML has head tabs that give information about the page
The body tab is part of the page that everybody sees
inside the body tab- h1 tab for header
                  then P tab for paragraph 
open with Live server 
Style tab 
  font size/ color/ background color. some design 
or put in the main.css tab

Markup validation service: to check errors in page 
The head stores meta information: under the head tab:
                                  meta charset="UTF-8"
DOCTYPE html at the very beginning 
Lang= "en" attribute

for the icon on the header: 
  head then we use link tab:
            rel= icon   href=nameoftheimage.png  type="image/x-icon"
hr= horizontal rule = horizontal lines


1- in the body paragraph:

to emphasize a word: use em/  or strong
br for another line: 
    &nbsp for more space 

    copy rights in the bottom of the page:
      &lt;&lt;&lt; &copy; Adem Khelifi &gt;&gt;&gt;
 Adem is <abbr title="Best Student Ever">BSE</abbr></BR> Abbreviation

 to add an address ( it will seem like an address):
  use address tab

 
  2-Lists:
   Type of Lists: 
      ordered lists:
      ol  
      li- item 1
      li- item 2
      li- item 3
      
      
      unordered lists:
      ul 
      li- item
      
      
      description lists
      
      li tab 
      dt tab - the item
      dd    the description of that item

3- working with links: 

    title  : A title of the Link
    anker    a tab href: the link.     >the abbreviation or any sentence to click on<

    changing the color of the links:
          we can do them in the css file. 
          a{  color:}
          a:visited{} 

      download link:
      a{ href="file/image.png" download>the word<

      let's say we're working in a second page and we want to go back to home page:
      a tab :href"/">go back to home page< 

4- working with Images: 

  img src="Amalfi-Italy.webp" alt="Italy">
    I will get a suggestions of pictures downloaded to choose from. 
      
    <img src="Amalfi-Italy.webp" alt="Italy"
                title= "I want to visit italy" width="200" height="150">
      working with the size: modify the height and the width of the pictures. 
      addition to that:
      if we want the picture to load when we get closer to the picture we add loading="lazy"
      if not and its default parameter loading="eager"

      title of the picture below the picture we use: figcaption tab

      figure

          put all the information about the picture in between 
          

      figure


 5- Semantic Tags: 
 grouping of links:
     nav tab:
                links
      nav tab

      Header tab: for the headers in the page.
      main tab for the informations/ divide parts of main by section tab
      footer in the end (copyrights)


      tip: 
          aside:
              details  
                  <summary> guess <mark> where I'm going <mark> this summer <summary>
                  p tab  oh to France!.
              details 
            aside


6- Adding tables: 
    
     <table>
            <tr>

                <td>
                    <time datetime="8:00">8am</time>
                    <time  datetime="11:00">11am </time>
                    
                <td>eat lunch</td>

                </td>



            </tr>



        </table>


        for the header of the table:
          th: inside the tr tabs

          <caption> the one title of the table

          we can add semantic tags for the table: theader/ tbody/tfooter 
          doesn't change the look but it organizes things

          td tab column span:"x">information< 

7- Forms:
      <h2>Contact me</h2>
        
            <form action="about.html" method="get">
                <p>
                    <label for="FirstName">First name</label>
                    <input type="text" name="FirstName" id="FirstName" 
                    placeholder="Maria" autocomplete="on" required>


                </p>
                <p>
                    <label for="LastName">Last name</label>
                    <input type="text" name="LastName" id="LastName" 
                    placeholder="Josito" autocomplete="on" required>
                add pattern tab for the input type ( digits for example) [0-9]



