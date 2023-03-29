### Document Tag :
>This section involves tags which are used to describe the HTML document by giving an overview of what it includes.
```
<--....--> : comment here
<!DOCTYPE html> : Browser(live server).
<html> : Create HTML document.
<head> : Set tittle and Other info whose isn't display.
<meta> : Define meta data.
<title> : Puts name of Document
<style> : Style info(CSS) for a document.
<link> : Link other language like CSS,js e.t.c.
<body> : Sets of Visual properties of documents.
```
```
Ex : <!--Browser-->
<!DOCTYPE html>
<!--HTML Document-->
<html>
<!-- head tag starts here -->
<head>
   <!-- title tag -->
   <title>Title goes here </title>
  
   <!-- link tag  -->
   <link rel="stylesheet" 
         type="text/css" 
         href="style.css">
  
   <!-- meta tag starts -->
   <meta name="keywords"
         content="Meta Tags, Metadata" />
   <!-- meta tag ends -->
  
   <!-- style tag starts here -->
   <style>
      #first {
      font-family: Castellar;
      background-color: green;
      color: white;
      }
      .second {
      text-align: center;
      background-color: white;
      font-size: 30px;
      color: red;
      }
   </style>
   <!-- style tag ends here -->
</head>
<!-- head tag ends here -->
<!-- Body tag start here -->
<body>
    
   <p id="first">Hello 0xaman47.</p>
   <p class="second">Welcome to HTML world</p>
</body>
<!-- Body tag end here -->
</html>
```
