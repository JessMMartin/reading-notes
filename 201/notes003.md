# HTML Lists, Control Flow with JS, and the CSS Box Model

### 💠 When should you use an unordered list in your HTML document?

<p>When you don't need a specific order or sequence. unordered lists are represented as bullet points.</p>

### 💠 How do you change the bullet style of unordered list items?

<p>By using 'type' and values 'circle 'disc' or 'square</p>

### 💠 Describe two ways you can change the numbers on list items provided by an ordered list?
<p>Either by using 'value' or by using CSS counters.</p>

### 💠Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

<p>Padding is best mates with Content and doesn't know what personal space is and Margin is not so close but is the rich mate as they can give up as much space to Content thats needed, they create some space outside the border of the element, separating it from the other elements on the page because Margin is lowkey jealous of the other mates. </p>

### 💠List and describe the four parts of an HTML elements box as referred to by the box model.

<ul>
    <Li>Content : Text/image
    <li>Padding : Space between the content and the border of the element.
    <li>Boarder : Line that wraps the content and the padding of the element.
    <li>Margin  : Space outside the border of the element, which separates it from other elements on the page.
</ul>

### 💠 What data types can you store inside of an Array?

<p>A collection of the same data type eg. numbers, strings, booleans, or objects.</p>

### 💠Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

<p>It's not valid as it uses curly braces instead of square brackets. Curleys are used for objects, not arrays. </p>

### 💠 List five shorthand operators for assignment in javascript and describe what they do. 
<p><ul>
    <li><p>x += f() : This operator adds the value of the right operand to the value of the left operand and assigns the result to the left operand</p>
    <li><p>x -= f(): Subtraction assignment (-=): This operator subtracts the value of the right operand from the value of the left operand and assigns the result to the left operand. 
    <li><p>x *= f() : Multiplication assignment (*=): This operator multiplies the value of the left operand by the value of the right operand and assigns the result to the left operand.
    <li><p>x /= f() : Division assignment (/=): This operator divides the value of the left operand by the value of the right operand and assigns the result to the left operand. 
    <li><p>x %= f() : Remainder assignment (%=): This operator calculates the remainder of dividing the value of the left operand by the value of the right operand and assigns the result to the left operand.
</ul></p>   

### 💠 Read the code below and evaluate the last expression and explain what the result would be and why.
    let a = 10;
    let b = 'dog';
    let c = false;

    // evaluate this
    (a + c) + b;

<p>a) is a number and c) is a boolean. When a boolean is used in a numeric context, it is converted to a number. If a boolean is false it has a value of 0. Therefore the result of a + c is 10.<br>
</p><p>The second addition operation, (a + c) + b, involves a number (a + c) and a string (b). In JavaScript, when a number is used in a string context, it is converted to a string. Therefore, a + c becomes "10" and the result of (a + c) + b is "10dog".</p><br>

### 💠Describe a real world example of when a conditional statement should be used in a JavaScript program.

<br><p>A conditional statement is a useful feature in JavaScript that allows you to execute different code blocks depending on certain conditions. For instance, if you are making a quiz app that provides feedback to the user according to their answers, you can use a conditional statement. You can use the 'if…else' statement to compare the user’s answer with the correct answer and show a different message based on the result. You can also use the 'switch' statement to evaluate the user’s score and show a different badge or reward based on their performance</p>

### 💠Give an example of when a Loop is useful in JavaScript.

<p>A loop is useful in JavaScript when you want to perform the same task or operation on a set of data, such as an array, an object, or a string . For example:
var numbers = [1, 2, 3, 4, 5];</p>
