### Section content :
>Sectioning Content elements by default define ARIA landmark. These elements are mostly descendant of HTML body element.
```
<header> : intro content about document.
<main> : main content of the document body.
<section> : represent standard section.
<nav> : provide navigation link.
<a href = "link"> : linked 
<article> : self-content composition in a document,page,or site which is independently reusable.
<aside> : sidebar in a content.
<footer> :  information about the author of the section, copyright data or links to related documents.
<address> : provides contact information for a person or people, or for an organization. It must not contain information other than contact information.
```
```
Ex :
<!DOCTYPE html>
<html>
<body>
   <!-- main tag starts here -->
   <h3>HTML Header Tag</h3>
   <hr>
   <article>
      <!-- header tag starts -->
      <header>
         <h3>0xaman47</h3>
         <h3> HTML nav Tag</h3>
         <!-- nav tag starts -->
         <nav>
            <a href="#">Home</a> |
            <a href="#">Interview</a> |
            <a href="#">Languages</a> |
            <a href="#">Data Structure</a> |
            <a href="#">Algorithm</a>
         </nav>
         <!-- nav tag ends -->
      </header>
      <!-- header tag ends -->
   </article>
   <main>
      <!-- HTML section tag is used here -->
      <section>
         <h1>0xaman47: Section 1</h1>
         <p>Content of section </p>
      </section>
      <!-- HTML section tag ends here -->
      <!-- aside tag starts here -->
      <aside>
         <h1>This is heading text in aside Tag</h1>
         <p>This is paragraph text in aside Tag</p>
      </aside>
      <!-- aside tag ends here -->
   </main>
   <!-- main tag ends here -->
   <!--HTML footer tag starts here-->
   <footer>
      <article>
         <!-- address tag starts from here -->
         <address>
            Organization Name: 0xaman47 <br>
            Web Site:
            <a href="https://github.com/0xaman47">
            0xaman47</a><br>
            visit us:<br>
            0xaman47<br>
            A-118, Sector 8, begusarai, <br>
            Bihar (851101)
         </address>
         <!-- address tag ends here -->
      </article>
      <br>
      <a href="https://tetw.org/Love">
         relationship
      </a>|
      <p>@0xaman47, try to do something big</p>
   </footer>
   <!-- footer tag ends here -->
</body>
</html>
```
