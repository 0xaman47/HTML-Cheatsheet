### Form :
> An HTML form is a section of a document that acts as a container for different types of input elements, such as text fields, passwords, menus, checkboxes, radio buttons, submit buttons, etc.
```
<form> :  Define form document.
<input> : element is used to create interactive controls for web-based forms in order to accept data from the user.
<input type="checkbox" name=? value=?> : Create a checkbox.
<input type="checkbox" name=? value=? checked> : Creates a checkbox which is pre-checked.
<input type="radio" name=? value=?> : Creates a radio button.
<input type="radio" name=? value=? checked> : Creates a radio button which is pre-checked.
<input type="text" name=? size=?> : Creates a one-line text area. Size sets length, in
characters.
<input password> : password
<input file> : select file.
<input type="submit" value=?> : Creates a submit button. Value sets the text in the
submit button.
<input type="image" name=? src=? border=? alt=?> : Creates a submit button using an image.
<input type="reset"> : Creates a reset button
<textarea> : used to create a multi-line plain-text editing control, often used in a form, to collect user inputs like comments or reviews.
<select> :  element represents a control that provides a menu of options to select from.
<select multiple name=? size=?> </select> : Creates a scrolling menu. Size sets the number of menu items visible before user needs to scroll.
<select name=?> </select> : Creates a pulldown menu
<option> : used to define an option in a select list. The<option> elements go inside a <select>, <optgroup>, or <datalist> elements.
<optgroup> : sed to create a grouping of options within a <select> element.
<progress> : displays an indicator showing the degree of completion of a task, typically displayed in the form of a progress bar.
<datalist> : used to give a predefined options for an <input> element. It adds an autocomplete feature to it.
<button> : element represents a clickable button, which can be used in forms or
anywhere a standard button functionality is needed in a document.
<label> : tag is used to specify a label or caption for an <input> element of a form.
```
```
Ex :
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>0xaman47</title>
    <style>
      body{
        background-color: rgb(119, 125, 114);
      } 
    </style>
</head>
<body>
    <form>
        <fieldset>
            <legend>Love Affair</legend>
            <p>
            <b>Personal info :-</b></p>
            <label>
                Selection 
                <select name="Salutation">
                    <option>--None--</option>
                    <option>male</option>
                    <option>female</option>
                    <option>custom</option>
                </select>
            </label>
            <p>
                <label>
                    firstName : <input name="firstName"
                    placeholder="Enter first name"/>
                </label>
            </p>
            <p>    
                <label>
                    lastName : <input name="lastName"
                    placeholder="Enter last name"/>
                </label>
            </p>
            <p>
                <label>Email : <input type="email" name="email"/></label>
            </p>
            <p>
                <label>Date of birth : <input type="date" name="birthDate"/></label>
            </p>
            <p>
                <label>
                    Address :
                    <br>
                    <textarea name="Address" placeholder="Enter your Address"></textarea>
                </label>
            </p>
            <p>
                Intrusted :
                <labe><input type="radio" name="gender" value="Male">yes</label>
                <labe><input type="radio" name="gender" value="female">no</label>
            </p>
            <p>
                <label><input name="terms" type="checkbox" value="tandc" />Accept terms</label>
            </p>
            <pre>
                <button type="submit" > Submit</button>
            </pre>
            <br>
            <div class="taskbar">
               <img src="" alt="">
            </div>
        
            <br>
            <br>
            <p>
                Downloading progress for your profile : 
                <progress value="80" max="100" aria-placeholder="Progress"></progress>
            </p>
        </fieldset>
        <p><i>0xaman47</i></p>
    </form>
    
</body>
<script src="form.js"></script>
</html>
```