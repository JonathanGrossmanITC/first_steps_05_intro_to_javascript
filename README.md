# JavaScript Intro  

Welcome to the fifth lesson! In this lesson, you review the HTML and CSS quiz and start learning JavaScript. You will briefly review the quiz questions and answers to reinforce what you learned in the first four lessons. Then, you begin learning about JavaScript.

JavaScript is a programming language used in web developemt. Among the things you can do with JavaScript are write frontend web applications and build servers. In this First Steps program, you learn how to write frontend web pages in JavaScript. In the [ITC Fullstack Program](https://www.itc.tech), students learn more advanced frontend JavaScript techniques, how to build JavaScript frontend we applications using JavaScript libraries and frameworks, and how to write servers in JavaScript.

After learning in this lesson about what JavaScript is, you learn about the different data types in JavaScript. Data types are the format in which data is saved in memory. For instance, JavaScript has data type for strings, numbers, arrays, objects, and more. You need to know what the data types are and when and how to work with them.

Throughout the lesson, you will see examples that demonstrate some of the JavaScript basics and will learn about resources that can guide you through the learning process. 

In this lesson, you learn:  

- Hour 1: [QUIZ HTML and CSS](#quiz-html-and-css)    
- Hour 2: [Intro to Frontend JavaScript](#intro-to-frontend-javascript)   
- Hour 3: [Variables and Data Types](#variables-and-data-types)  

The topics below outline what you learn in the live session. After the live session, you can use this material as a resource for guided self-learning. This document will serve you as a roadmap for gaining repetition with the material that you learn during the live session.   

## [QUIZ HTML and CSS](#quiz-html-and-css)  

Review the quiz answers and discuss HTML and CSS topics. If time permits, some students can volunteer to show their portfolio code and how it looks in the browser.  
## [Intro to Frontend JavaScript](#intro-to-frontend-javascript)   

### What is JavaScript  

- JavaScript is a popular language for web development  
- It is common to use JavaScript to dynamically modify HTML and CSS after the web page loads in order to change what the user sees  
- If you're building a frontend, you're doing it in JavaScript
- [ECMAScript 6 (ES6)](https://262.ecma-international.org/6.0/) is the latest version  
  -- When researching answers online, consider the date of the post, as more recent answers are more likely to contain the most modern syntax  
  -- You are learning what people call "vanilla" JavaScript  
  -- JavaScript frameworks and libraries include React, Angular, Vue, and jQuery  
  -- Although you are not learning in this course frameworks and libraries, know that they exist because it can help you sift through information online when researching answers (in particular, lookout for answers in jQuery, denoted by $ throughout the code, which can look confusingly similar to "vanilla")  
  -- Do not mix and match jQuery with "vanilla" JavaScript  
- JavaScript add functionality to your web page 
- Seeing [examples](https://www.w3schools.com/js/js_examples.asp) is a great way to learn what you can do with JavaScript:  
  -- [Number guessing game](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash)  
  -- [Change HTML content](https://www.w3schools.com/js/tryit.asp?filename=tryjs_intro_inner_html)  
  -- [Change HTML attributes](https://www.w3schools.com/js/tryit.asp?filename=tryjs_intro_lightbulb)  
  -- [Change CSS Style](https://www.w3schools.com/js/tryit.asp?filename=tryjs_intro_style)  
  -- [Hide](https://www.w3schools.com/js/tryit.asp?filename=tryjs_intro_hide) and [show](https://www.w3schools.com/js/tryit.asp?filename=tryjs_intro_show) elements   -- Note that the W3Schools examples use inline styling for CSS (i.e., `style=" . . . "`) and HTML attributes for JavaScript (e.g., `onClick`). While these are okay for showing what JS can do, please do not use this approach in your web applications. Instead, use class-based styling for CSS and pure JavaScript for functionality. It's important you learn how to see the W3Schools examples (and other examples online) and translate them into code that is reusable and easier to maintain.  
  
### Where to Put JavaScript Code  

- When writing JavaScript for frontend, it's best to write your code in a .js file and import it into your HTML file  
- In your project's root folder, you should have a 'js' folder, and inside it you put your JavaScript code inside files with a .js file extension  
- Import it using a `script` tag with the `src` attribute equal to the relative path of the .js file (e.g., `<script src="myScript.js"></script>`)  
- The `script` tag belongs [at the bottom of your `body` tag](https://www.tutorialspoint.com/How-to-use-external-js-files-in-an-HTML-file)    
- It is possible to put `script` tags in the `head` tag, but generally put them in the `body` 
- If you import multiple scripts, [the order matters](https://stackoverflow.com/a/8996905) because `script` tags have access to the information in the `script` tags above it but not below it  
- See the [discussion at the bottom of this link about external JavaScript](https://www.w3schools.com/js/js_whereto.asp)  
- You [also can write JavaScript](https://developer.mozilla.org/en-US/docs/Learn/HTML/Howto/Use_JavaScript_within_a_webpage) code directly inside `script` tags at the bottom of your HTML `body` (or in the `head`), in which case you do not need to set the `src` 
- You can also access JavaScript in HTML tag attributes, like the `onClick` attribute, but it is [bad prcatice to do so](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript#inline_javascript_handlers)     
- You will see [examples online](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript#internal_javascript) where people write JavaScript like this in the `script` tags and HTML tags; however, it's not reusable and it can be more time consuming to maintain  
- You should know how to understand examples online where people write JavaScript like this in the `script` tags and HTML tags and know how to convert that code to an external JavaScript file  

### How JavaScript Interacts With HTML  

- The order in which write your code matters because the browser reads your code [from top to bottom](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript#javascript_running_order)  
  -- You may see errors saying that a variable or function does not exist, and that may be because the object you reference in your code does not yet exist in the browser's memory  
  -- You can write [comments in your code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript#comments); comments are not read by the browser; usually, they are used as notes to developers explaining the code 
-   


## [Variables and Data Types](#variables-and-data-types)   

