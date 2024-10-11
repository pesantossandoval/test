---


---

<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.<br>
<a href="https://classroom.github.com/a/cjFfkCyh"><br>
<img src="https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg" alt="Review Assignment Due Date"></a></p>
</blockquote>
<p>Pedro Santos Sandoval<br>
P2-Binary Expression Tree Evaluation</p>
<p><strong>Grade Aiming for:</strong>  A + Extra Credit</p>
<p><strong>Functionality to get a C (75):</strong></p>
<ul>
<li>Implement a  <code>Node</code>  class to represent nodes in the binary tree.</li>
<li>Create a method to build the expression tree from a fully parenthesized input string.</li>
<li>Develop a method to evaluate the expression tree and return the result.</li>
<li>In the main method, prompt the user for input, build the tree, and show the evaluation result.</li>
<li>Example input:  <code>((5+3)*(4-2))</code>  should display  <code>16</code>.</li>
</ul>
<p><strong>Functionality to get a B (85) includes functionality to get a C and:</strong></p>
<ul>
<li>Implement a method to display the tree structure of the expression tree.</li>
<li>Add support for exponentiation (<code>^</code>) operator.</li>
<li>Add support for decimal numbers in expressions.</li>
<li>Implement error handling for invalid input expressions.</li>
<li>Develop a simple command-line interface that allows users to enter expressions and see results.</li>
<li>Example input:  <code>((5.5+3.2)*(4-2.7))</code>  should display  <code>11.31</code>.</li>
</ul>
<p><strong>Functionality to get an A (95) includes functionality to get a B and:</strong></p>
<ul>
<li>Add support for variables in expressions (e.g.,  <code>x1</code>,  <code>x2</code>,  <code>x3</code>).</li>
<li>Implement a method to update variable values interactively (i.e., prompt the user for values of variables after they input an expression).</li>
<li>Add support for unary operators (e.g., negation, such as  <code>-x</code>).</li>
<li>Add support for mathematical functions (e.g.,  <code>sin</code>,  <code>cos</code>,  <code>log</code>).</li>
<li>Example input:  <code>((x1+3)*(x2-2))</code>  should display the tree structure, prompt the user for values of  <code>x1</code>  and  <code>x2</code>, and evaluate the expression. For  <code>x1=5</code>  and  <code>x2=10</code>, the result should be  <code>64</code>.</li>
</ul>
<p><strong>Additional Points/Extra Credit (2 points each):</strong></p>
<ul>
<li>Create a command-line interface for batch processing of expressions.</li>
<li>Support for saving and loading expression trees from/to files.</li>
</ul>
<p><strong>Key Features:</strong></p>
<ul>
<li>Build the expression tree from user input (fully parenthesized arithmetic expression).</li>
<li>Evaluate the expression and display the result.</li>
<li>Display the tree structure.</li>
<li>Support for decimal numbers and the exponentiation operator.</li>
<li>Support for variables in expressions (e.g.,  <code>x1</code>,  <code>x2</code>) and interactive updating of their values.</li>
<li>Handle unary operators like negation.</li>
<li>Add support for mathematical functions (<code>sin</code>,  <code>cos</code>,  <code>log</code>).</li>
<li>Handle invalid input and show appropriate error messages.</li>
<li>Simple command-line interface for user interaction.</li>
</ul>
<p><strong>Brief Explanation:</strong><br>
In this project, I implemented a binary expression tree to evaluate fully parenthesized arithmetic expressions, supporting various operations like variables and mathematical functions. The tree will handle complex expressions, including exponentiation, decimals, and variable inputs. To achieve an A, I added support for unary operators and functions like  <code>sin</code>,  <code>cos</code>, and  <code>log</code>. When evaluating expressions with variables, the program will prompt users to enter the values, and it will display the tree structure for better visualization. Error handling ensures the program guides users with clear messages when invalid input is provided.</p>
<p>For  extra credit, the program includes:</p>
<ul>
<li>A  command-line interface for batch processing  of expressions, allowing users to input a file with multiple expressions to be evaluated one by one.</li>
<li>Support for saving and loading expression trees  to/from files, giving users the flexibility to save their last expression tree</li>
</ul>
<p><strong>Instructions:</strong><br>
-Download the Java files and the docs folder containing the text files.<br>
-Compile and run the EReader Java program from your command line<br>
-If you are unable to read files using Visual Studio Code, use  IntelliJ Idea, or us your terminal built into your computer, or terminal built into Visual Studio Code.</p>
<p><strong>Test Instructions:</strong></p>
<ol>
<li>
<p>Open Terminal.</p>
</li>
<li>
<p><code>cd /path/to/your/java/files</code>.</p>
</li>
<li>
<p>Compile the code using:<br>
<code>javac Node.java</code></p>
</li>
<li>
<p>Run the program with:<br>
<code>java Node</code></p>
</li>
<li>
<p>Enter expressions in fully parenthesized format and observe the results (including variables and functions)</p>
<p>Example: (sin(x1+1)) + (sin(x2+1)) or ((5+3)*(4-2))</p>
<p>For Sin,Cos, Log if you are doing any form of operators you need to put them in () like the example , but if you are doing by its self, its ok to input sin(x1)</p>
</li>
<li>
<p>There is a file named ‘batch1.txt’ that has the following numbers for testing, the code only reads those batches expressions in the file and prints out tree with answer to the expression:<br>
((5+3)*(4-2))<br>
(x1+2)^3<br>
cos(0)<br>
(sin(3.1416/2))<br>
5 +</p>
</li>
</ol>
<p><strong>References:</strong></p>
<ul>
<li>Java Documentation:  <a href="https://docs.oracle.com/javase/">https://docs.oracle.com/javase/</a></li>
<li>Project requirements and structure based on professor guidance.</li>
</ul>

