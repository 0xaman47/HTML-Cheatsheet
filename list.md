### List :
>Lists can be either numerical, alphabetic, bullet, or other symbols. You can specify list type and list items in HTML for the clean document. There are three list types in HTML
* Unordered list: Used to group a set of related items in no particular order.

* Ordered list: Used to group a set of 
related items in a specific order.

* Description list: Used to display name/value pairs such as terms and definitions.
```
<ul> : unordered list
<ol> : ordered list
<li> : represent item in a list
<dl> : description list
<dd> : used in conjunction with to describe a term/name in a description list.
<dt> : element is used in conjunction with to specifies a term in a description or definition list.
```
```
Ex : 
<!DOCTYPE html>
<html>
<head>
   <title>0xaman47</title>
</head>
<body>
   <h2>Welcome To Learning HTMl</h2>
   <h5>Unordered List</h5>
   <!-- Unordered List -->
   <ul>
      <li>Data Structures & Algorithm</li>
      <li>Web Technology</li>
      <li>Aptitude & Logical Reasoning</li>
      <li>Programming Languages</li>
   </ul>
   <h5>Ordered List</h5>
   <!-- Ordered List -->
   <ol>
      <li>Array</li>
      <li>Linked List</li>
      <li>Stacks</li>
      <li>Queues</li>
      <li>Trees</li>
      <li>Graphs</li>
   </ol>
   <h5> </h5>
   <h5>Description List</h5>
   <!-- Description List -->
   <dl>
      <dt>Courses:</dt>
      <dd>100 </dd>
      <dt> Quizzes:</dt>
      <dd> 500 </dd>
      <dt> Interview Experiences:</dt>
      <dd>1000 </dd>
   </dl>
</body>
</html>
```