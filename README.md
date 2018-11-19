# Technical-Documentation-page
challenge 4
<style>
@import 'https://fonts.googleapis.com/css?family=Allerta+Stencil';

html,body{
  min-width:290px;
    color: #4d4e53;
    background-color: #ffffff;
		word-wrap: break-word;
    font-family: 'Allerta Stencil', sans-serif;
    line-height: 1.5;
}
#navbar{
  position:fixed;
  min-width:290px;
  top:0px;
  left:0px;
  width:300px;
  height:100%;
  border-right:solid;
	background-color: green;
  border-color:rgba(0,22,22,0.4);
}
header{
  color: black;
	/*
	background-color: green;
	padding-left: 10px;
	border: solid black 1px;
	*/
  font-size: 30px;
  margin:10px;
  text-align:center;
  font-size:1.8em;
  font-weight:thin;
	family-font: AllertaStencil;
}
#main-doc header{
  text-align:left;
  margin:0px;
}
#navbar ul{
  height:88%;
  overflow-y:auto;
  overflow-x:hidden;
}
#navbar li{
  color: black;
	background-color: lightgreen;
  border:1px solid;
  border-bottom-width:0px;
  padding:8px;
  padding-left:45px;
  list-style: none;
  position:relative;
 left:-50px;
  width:100%;
  
}
#navbar a{
  color: #4d4e53;
    text-decoration:none;
    cursor:pointer;
} 
#main-doc{
  position: absolute;
  margin-left:310px;
  padding:20px;
  margin-bottom:110px;
}
section article{
  color: #4d4e53;
  margin:15px;
  font-size:0.96em;
}
section li {
  margin:15px 0px 0px 20px;
}
code{
  display:block;
    text-align: left;
  white-space: pre;
  position: relative;
    word-break: normal;
    word-wrap: normal;
    line-height: 2;
    background-color:#f7f7f7;
  padding:15px;
  margin:10px;
    border-radius:5px;
}
@media only screen and (max-width: 815px) {
    /* For mobile phones: */
  #navbar ul{
  border:1px solid;
    height:207px;
  }
    #navbar{
      background-color:white;
      position:absolute;
      top:0;
      padding:0;
      margin: 0;
      width:100%;
      max-height:275px;
      border:none;
      z-index:1;
      border-bottom:2px solid;
    }
  #main-doc{
    position: relative;
    margin-left:0px;
    margin-top:270px;
  }
  #main-doc section {
/*     padding-top: 240px; */
  }
}
@media only screen and (max-width: 400px) {
  #main-doc{
    margin-left:-10px;
  }
  code{
    margin-left:-20px;
    width:100%;
    padding:15px;
    padding-left:10px;
    padding-right:45px;
    min-width:233px;
  }
}
</style>
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
<nav id="navbar">
  <header>HTML RECAP</header>
  <ul> 
    <a class="nav-link" href="#Introduction" rel="internal"><li>Introduction</li></a>
    <a class="nav-link" href="#What_you_should_already_know" rel="internal"><li>What you should already know</li></a>
    <a class="nav-link" href="#Colour_Elements" rel="internal"><li>Colour Elements</li></a>
    <a class="nav-link" href="#Fonts_&_Text" rel="internal"><li>Fonts & Text</li></a>
    <a class="nav-link" href="#Coding_Units" rel="internal"><li>Coding Units</li></a>
    <a class="nav-link" href="#Paddings_and_Margins" rel="internal"><li>Paddings and Margins</li></a>
    <a class="nav-link" href="#Subtitle_one" rel="internal"><li>Subtitle one</li></a>
    <a class="nav-link" href="#Subtitle_two" rel="internal"><li>Subtitle two</li></a>
    <a class="nav-link" href="#Subtitle_three" rel="internal"><li>Subtitle three</li></a>
    <a class="nav-link" href="#Subtitle_four" rel="internal"><li>Subtitle four</li></a>
    <a class="nav-link" href="#Subtitle_five" rel="internal"><li>Subtitle five</li></a>
    <a class="nav-link" href="#Subtitle_six" rel="internal"><li>Subtitle six</li></a>
    <a class="nav-link" href="#Subtitle_seven" rel="internal"><li>Subtitle seven</li></a>
    <a class="nav-link" href="#contact_us" rel="internal"><li>contact us</li></a>
  </ul>
</nav>
<main id="main-doc">
 <section class="main-section" id="Introduction">
	<header>Introduction</header>
  	<article>  
    	<p>So far we have coverd all the basic HTML and CSS Elemlents it would be much beneifit to me and others to have a place to jog your memory quickly across code... how to use it and why.</p>

	  	<p>HTML5 is the code we have been learning, I have been using <a href="https://codepen.io/ojkt/">codepen.io</a>, gitkracken and <a href="https://github.com/OJKT">github</a> to create projects and lesson notes from <a href="https://www.freecodecamp.org/ojkt"> FreeCodeCamp</a> like this documentation page project for revision and practise.</p>	
		</artice>
</section>
<br>
<br>
<hr>
 <section class="main-section" id="What_you_should_already_know">
 <header>What you should already know</header>
	<article>
      <p>This guide assumes you have the following basic background:</p>
			<ul>
				<li>Basic HTML and HTML5</li>
				<li>Basic CSS</li>
				<li>Applied Visual Design</li>
				<li>Applied Accessibility</li>
				<li>Responsive Web Design Principles</li>
				<li>CSS Flexbox</li>
				<li>CSS Grid</li>
		  </ul>
  </artice>
</section>
<hr>
 <section class="main-section" id="Colour_Elements">
  <header>Colour Elements</header>
    <article>
			<p>Because coding is American colour is spelt incorrectly in the color element tag, as shown below you did some code covering the following points during FCC Lessons:</p>
			<ul>
				<li>Style the HTML Body Element</li>
				<li>Inherit Styles from the Body Element</li>
				<li>Prioritize One Style Over Another</li>
				<li>Override Styles in Subsequent CSS</li>
				<li>Override Class Declarations by Styling ID Attributes</li>
				<li>Override Class Declarations with Inline Styles</li>
				<li>Override All Other Styles by using Important</li>
</ul>
			<p>Theese lessons taught you how to prioritise color elements suited to your needs(as well as all other elements)</p>
			<p>The Red Green Blue of and elements colour can be changed (RGB) and the Hue Saturation and Value of the elements colour can be changed too (HSV) border-color:rgba(0,0,0,0.0); as shown here is one way of changing the colour and #000000 is long HEX code and #eee is short hex code. For more infomation on colors <a href="https://www.rapidtables.com/web/color/RGB_Color.html">click here</a>.</p>
		</article>
</section>
<hr>
 <section class="main-section" id="Fonts_&_Text">
    <header>Fonts & Text</header>
    <article> 
			<p><a href"https://fonts.google.com/">Google Fonts</a> is an amazing website for finding free Family fonts to set your code to.</p>
			<p>Here are some other CSS style elements:</p>
			<ul>
				<li><i>Itallics</i>are created using the i in triangular brackets (tb).</li>
				<li>hr its the lines you see segregating parts on this page.</li>
				<li><strong>Bold</strong> is done using Strong in tb.</li>
				<li>font-weight can be changed</li>
				<li>text-align: left, right or center</li>
				<li>color: rgb and hex... and the rest... see above.</li>
				<li>font-size: see coding units</li>
				<li>text-decoration: overline| line-through| underline| underline overline.</li>
				<li>word-wrap: normal|break-word|initial|inherit;</li>
			</ul>
    </article>
    </section>
<hr>
 <section class="main-section" id="Coding_Units">
   <header>Coding Units</header>
  	<i>The four different viewport units are:</i>
		<0l>
			<li>vw: 10vw would be 10% of the viewport's width.</li>
			<li>vh: 3vh would be 3% of the viewport's height.</li>
			<li>vmin: 70vmin would be 70% of the viewport's smaller dimension (height vs. width).</li>
			<li>vmax: 100vmax would be 100% of the viewport's bigger dimension (height vs. width).</li>
		</ol>
</section>
<hr>
 <section class="main-section" id="Paddings_and_Margins">
	
 <header>Paddings and Margins</header>
 <article>
      <p>
				Clockwise notation for padding: 10px 20px 10px 20px;
				These four values work like a clock: top, right, bottom, left, and will produce the exact same result as using the side-specific padding instructions.
      </p>
			<p>
				margin: 10px 20px 10px 20px;
These four values work like a clock: top, right, bottom, left, and will produce the exact same result as using the side-specific margin instructions.
			</p>
			<hr>
    </article>
    </section>
 <section class="main-section" id="Subtitle_one">
    <header>Subtitle one</header>
    <article>
     <p> When you declare a variable outside of any function, it is called a global variable, because it is available to any other code in the current document. When you declare a variable within a function, it is called a local variable, because it is available only within that function.</p>

<p>JavaScript before ECMAScript 2015 does not have block statement scope; rather, a variable declared within a block is local to the function (or global scope) that the block resides within. For example the following code will log 5, because the scope of x is the function (or global context) within which x is declared, not the block, which in this case is an if statement.</p>
<code>if (true) {
  var x = 5;
}
console.log(x);  // 5</code>
      <p>This behavior changes, when using the let declaration introduced in ECMAScript 2015.</p>

<code>if (true) {
  let y = 5;
}
console.log(y);  
// ReferenceError: y is not defined</code>
    </article>
    </section>
<hr>
 <section class="main-section" id="Subtitle_two">
    <header>Subtitle two</header>
    <article>
<p>Global variables are in fact properties of the global object. In web pages the global object is window, so you can set and access global variables using the window.variable syntax.</p>

<p>Consequently, you can access global variables declared in one window or frame from another window or frame by specifying the window or frame name. For example, if a variable called phoneNumber is declared in a document, you can refer to this variable from an iframe as parent.phoneNumber.</p>
    </article>
    </section>
<hr>
 <section class="main-section" id="Subtitle_three">
    <header>Subtitle three</header>
    <article>
<p>You can create a read-only, named constant with the const keyword. The syntax of a constant identifier is the same as for a variable identifier: it must start with a letter, underscore or dollar sign and can contain alphabetic, numeric, or underscore characters.</p>

      <code>const PI = 3.14;</code>
<p>A constant cannot change value through assignment or be re-declared while the script is running. It has to be initialized to a value.</p>

<p>The scope rules for constants are the same as those for let block scope variables. If the const keyword is omitted, the identifier is assumed to represent a variable.</p>

<p>You cannot declare a constant with the same name as a function or variable in the same scope. For example:</p>

<code>// THIS WILL CAUSE AN ERROR
function f() {};
const f = 5;
// THIS WILL CAUSE AN ERROR ALSO
function f() {
  const g = 5;
  var g;
  //statements
}</code>
However, object attributes are not protected, so the following statement is executed without problems.
<code>const MY_OBJECT = {"key": "value"};
MY_OBJECT.key = "otherValue";</code>
    </article>
    </section>
<hr>
 <section class="main-section" id="Subtitle_four">
    <header>Subtitle four</header>
    <article>
      <p>The latest ECMAScript standard defines seven data types:</p>
      <li><p>Six data types that are primitives:</p>
<ul>
  <li>Boolean. true and false.</li>
<li>null. A special keyword denoting a null value. Because JavaScript is case-sensitive, null is not the same as Null, NULL, or any other variant.</li>
  <li>undefined. A top-level property whose value is undefined.</li>
<li>Number. 42 or 3.14159.</li>
  <li>String. "Howdy"</li>
        <li>Symbol (new in ECMAScript 2015). A data type whose instances are unique and immutable.</li></ul>
      <li>and Object</li>
Although these data types are a relatively small amount, they enable you to perform useful functions with your applications. Objects and functions are the other fundamental elements in the language. You can think of objects as named containers for values, and functions as procedures that your application can perform.
    </article>
    </section>
<hr>
 <section class="main-section" id="Subtitle_five">
    <header>Subtitle five</header>
    <article>
Use the if statement to execute a statement if a logical condition is true. Use the optional else clause to execute a statement if the condition is false. An if statement looks as follows:

<code>if (condition) {
  statement_1;
} else {
  statement_2;
}</code>
condition can be any expression that evaluates to true or false. See Boolean for an explanation of what evaluates to true and false. If condition evaluates to true, statement_1 is executed; otherwise, statement_2 is executed. statement_1 and statement_2 can be any statement, including further nested if statements.
<p>
You may also compound the statements using else if to have multiple conditions tested in sequence, as follows:
      </p>
<code>if (condition_1) {
  statement_1;
} else if (condition_2) {
  statement_2;
} else if (condition_n) {
  statement_n;
} else {
  statement_last;
} </code>
In the case of multiple conditions only the first logical condition which evaluates to true will be executed. To execute multiple statements, group them within a block statement ({ ... }) . In general, it's good practice to always use block statements, especially when nesting if statements:

<code>if (condition) {
  statement_1_runs_if_condition_is_true;
  statement_2_runs_if_condition_is_true;
} else {
  statement_3_runs_if_condition_is_false;
  statement_4_runs_if_condition_is_false;
}</code>
It is advisable to not use simple assignments in a conditional expression, because the assignment can be confused with equality when glancing over the code. For example, do not use the following code:
<code>if (x = y) {
  /* statements here */
}</code>
If you need to use an assignment in a conditional expression, a common practice is to put additional parentheses around the assignment. For example:

<code>if ((x = y)) {
  /* statements here */
}</code>
    </article>
    </section>
<hr>
 <section class="main-section" id="Subtitle_six">
    <header>Subtitle six</header>
    <article>
A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

<code>while (condition)
  statement</code>
If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

<p>The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops and control is passed to the statement following while.</p>

      <p>To execute multiple statements, use a block statement ({ ... }) to group those statements.</p>

Example:

      <p>The following while loop iterates as long as n is less than three:</p>

<code>var n = 0;
var x = 0;
while (n < 3) {
  n++;
  x += n;
}</code>
<p>With each iteration, the loop increments n and adds that value to x. Therefore, x and n take on the following values:</p>

<li>After the first pass: n = 1 and x = 1</li>
<li>After the second pass: n = 2 and x = 3</li>
<li>After the third pass: n = 3 and x = 6</li>
 <p>After completing the third pass, the condition n &lt 3 is no longer true, so the loop terminates.</p>
    </article>
    </section>
<hr>
 <section class="main-section" id="Subtitle_seven">
    <header>Subtitle seven</header>
    <article> 
A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

      <li>The name of the function.</li>
      <li>A list of arguments to the function, enclosed in parentheses and separated by commas.</li>
      <li>The JavaScript statements that define the function, enclosed in curly brackets, { }.</li>
      <p>For example, the following code defines a simple function named square:</P>

<code>function square(number) {
  return number * number;
}</code>
<p>The function square takes one argument, called number. The function consists of one statement that says to return the argument of the function (that is, number) multiplied by itself. The return statement specifies the value returned by the function.
    </p>
    <code>return number * number;</code>
<p>Primitive parameters (such as a number) are passed to functions by value; the value is passed to the function, but if the function changes the value of the parameter, this change is not reflected globally or in the calling function.</p>
    </article>
    </section>
<hr>
 <section class="main-section" id="contact_us">
    <header>contact us</header>
    <article>
      <li>&copy Copyright 2018, OJKT STYLES <a href="https://www.facebook.com/Active-Boardom-1433050133615965/?ref=br_tf" target="_blank">contact us</a>
    </article>
    </section>
</main>
