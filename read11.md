# ESJ

**EJS (Embedded JavaScript templating) is a simple templating language that lets you generate HTML markup with plain JavaScript**

## Features of ESJ:

- Fast compilation and rendering
- Simple template tags: <% %>
- Custom delimiters (e.g., use <? ?> instead of <% %>)
- Both server JS and browser support
- Static caching of intermediate JavaScript
- Static caching of templates
- Complies with the Express view system


------------------


# Google Books APIs

## Working with volumes

- **Performing a search**
by sending an HTTP GET request to: `https://www.googleapis.com/books/v1/volumes?q=search+terms`
    - parameter: `q`  
    Search for volumes that contain this text string
    
    - special keywords:
     `intitle`  
     Returns results where the text following this keyword is found in the title  
     
     `inauthor`  
     Returns results where the text following this keyword is found in the author  
     
     `inpublisher`  
     Returns results where the text following this keyword is found in the publisher  
     
     `subject`  
     Returns results where the text following this keyword is listed in the category list of the volume  
     
     `isbn`  
     Returns results where the text following this keyword is the ISBN number  
     
     `lccn`  
     Returns results where the text following this keyword is the Library of Congress Control Number  
     
     `oclc`  
     Returns results where the text following this keyword is the Online Computer Library Center number  
     
     
     
     
     
     
     
     
     
