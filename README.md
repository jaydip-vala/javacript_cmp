# javacript_cmp
# General or basic knowledge of javascript 
    * An Introduction to JavaScript (what is javascript)?
        * The programs in this language are called scripts. They can be written right in a web page’s HTML and run automatically as the page loads.
        * Scripts are provided and executed as plain text. They don’t need special preparation or compilation to run.

    * Why is it called JavaScript?
        * When JavaScript was created, it initially had another name: “LiveScript”
        * Java was very popular at that time, so it was decided that positioning a new language as a “younger brother” of Java would help.

    *  what can't in browser javascript do?
        * JavaScript on a webpage may not read/write arbitrary files on the hard disk, copy them or execute programs. It has no direct access to OS functions.

# How to Write Javascript in Html Document
    * using <script></script> in body
    
#   Datatypes in Javascript   
    * Number - consider number data type ie:(phone number,age)
    * String - consider character ie:(name,address)
    * Boolean - consider true or false 
    * Big int - large number
    * Array - it is collection of element with same datatype
    * Undefined - when value is not define/
    * Null - Empty
    * Object - key : value

# Why use **use strict**
    * _use strict_ indicates that the code is to be executed in strict mode

#  Variabled in Javascript
    * let
    * var
    * const

# Difference between var and let in JavaScript
    var :  var is function scoped 
    let :  let is block scoped 
    ``` 
        let a = 'hello'; // globally scoped
        var b = 'world'; // globally scoped
        console.log(window.a); // undefined
        console.log(window.b); // 'world'
        var a = 'hello';
        var a = 'world'; // No problem, 'hello' is replaced.
        let b = 'hello';
        let b = 'world'; // SyntaxError: Identifier 'b' has already been declared
    ```
# alert, prompt, confirm
    * alert : it  shows a message.
        ``` 
        alert("Hello");
        ```
    * prompt :it shows a message and asking the user to input text
            if User clicked submit then return input text
            if User clicked cancel or ESC then return Null
        ```
            let age = prompt('Age', 100);
            alert(`You are ${age} years old!`);
        ```
    * confirm : it shows a message and waits for the user to press **Ok** or **Cancel**
        ```
            let con = confirm("Are you sure want to delete");
            alert( con );
        ```


        