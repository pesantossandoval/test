---


---

<p>Pedro Santos Sandoval<br>
L4 - Practice with Stacks</p>
<p><strong>Grade Aiming for:</strong>  A + Extra Credit</p>
<hr>
<h3 id="instructions-for-assignment">Instructions for Assignment:</h3>
<p><strong>Functionality to get a C (75):</strong></p>
<ul>
<li><strong>Insert text at the current cursor position:</strong>  The editor allows users to insert text at the position of the cursor.</li>
<li><strong>Delete text (a specified number of characters) at the current cursor position:</strong>  Users can delete characters starting from the current cursor position.</li>
<li><strong>Move the cursor to a specified position:</strong>  Users can move the cursor to any valid position in the text.</li>
<li><strong>Use a StringBuilder to store and manipulate the text content:</strong>  The text content is managed using a  <code>StringBuilder</code>  for efficient manipulation.</li>
<li><strong>Implement a simple command-line interface:</strong>  The editor provides a command-line interface to interact with the user.</li>
<li><strong>Include undo and redo functionality:</strong>  Two stacks are implemented to manage undo and redo operations.</li>
</ul>
<p><strong>Expected Methods:</strong></p>
<ul>
<li><code>insert(String text)</code></li>
<li><code>delete(int length)</code></li>
<li><code>moveCursor(int position)</code></li>
<li><code>getContent()</code>  - Get the contents of the text buffer (String)</li>
<li><code>getCursorPosition()</code></li>
<li><code>undo()</code></li>
<li><code>redo()</code></li>
</ul>
<hr>
<p><strong>Functionality to get a B (85):</strong></p>
<ul>
<li><strong>Add text search functionality:</strong>  Users can search for occurrences of a given text string within the document.</li>
<li><strong>Return a list of positions where the text was found:</strong>  The editor returns the positions of all occurrences found.</li>
<li><strong>Implement a replace function:</strong>  Users can replace all occurrences of a search term with a specified replacement text.</li>
</ul>
<p><strong>Methods:</strong></p>
<ul>
<li><code>searchText(String searchTerm)</code></li>
<li><code>replaceText(String searchTerm, String replacement)</code></li>
</ul>
<hr>
<p><strong>Functionality to get an A (95):</strong></p>
<ul>
<li>
<p><strong>Implement file I/O operations:</strong></p>
<ul>
<li><strong>Open a file and load its content into the editor:</strong>  Users can open a text file and load its contents into the editor.</li>
<li><strong>Save the current content to a file:</strong>  The editor can save its content back to the current file.</li>
<li><strong>Save the current content to a new file (Save As):</strong>  Users can save their current document to a new file with a specified name.</li>
</ul>
</li>
<li>
<p><strong>Copy and paste operations:</strong></p>
<ul>
<li>Users can copy text from the document and paste it at a specified position.</li>
</ul>
</li>
</ul>
<p><strong>Methods:</strong></p>
<ul>
<li><code>openFile(String filePath)</code></li>
<li><code>saveFile()</code></li>
<li><code>saveFileAs(String filePath)</code></li>
<li><code>copy(int start, int end)</code></li>
<li><code>paste(int position)</code></li>
</ul>
<hr>
<p><strong>Extra Credit:</strong></p>
<ul>
<li><strong>Implement a word wrap feature:</strong>  Automatically wrap text at a specified length to improve readability.</li>
</ul>
<hr>
<h3 id="error-handling-and-code-quality">Error Handling and Code Quality:</h3>
<ul>
<li>Proper file I/O handling with exceptions.</li>
<li>Readable and organized code with appropriate comments.</li>
<li>Handling of edge cases, such as invalid cursor positions and file operations.</li>
</ul>
<hr>
<h3 id="key-features">Key Features:</h3>
<ul>
<li><strong>Text manipulation:</strong>  Insert, delete, move, and replace text.</li>
<li><strong>Search functionality:</strong>  Search for and find text occurrences.</li>
<li><strong>File operations:</strong>  Open, save, and save as new files.</li>
<li><strong>Undo and redo:</strong>  Manage changes made during the editing process.</li>
<li><strong>Copy and paste:</strong>  Efficiently manage text within the document.</li>
<li><strong>Word wrap:</strong>  Automatically format text to fit within specified widths.</li>
</ul>
<hr>
<h3 id="brief-explanation">Brief Explanation:</h3>
<p>In this project, I will develop a text editor in Java that allows users to manipulate text through a command-line interface. The editor will provide essential functionalities such as inserting, deleting, and replacing text, along with managing cursor movements. Additionally, file operations will enable users to load and save documents, ensuring a comprehensive editing experience. The implementation will focus on utilizing data structures like stacks for undo/redo functionality and will incorporate error handling for a robust user experience.</p>
<hr>
<h3 id="instructions">Instructions:</h3>
<ol>
<li>
<p>Download the Java files or clone them from GITHUB.<br>
Files include the following:</p>
<ul>
<li><code>TextEditor.java</code></li>
<li><code>EditAction.java</code></li>
<li><code>README.md</code></li>
</ul>
</li>
<li>
<p>Compile and run the program from the command line.</p>
</li>
<li>
<p>To run the program, use the command:</p>
<p>bash</p>
<p>Copy code</p>
<p><code>java TextEditor</code></p>
</li>
</ol>
<h3 id="test-instructions">Test Instructions:</h3>
<ol>
<li>
<p>Open Terminal.</p>
</li>
<li>
<p>Navigate to the directory containing your Java files (<code>cd /path/to/your/java/files</code>).</p>
</li>
<li>
<p>Compile the program:</p>
<p>bash</p>
<p>Copy code</p>
<p><code>javac TextEditor.java</code></p>
</li>
<li>
<p>Run the program:</p>
<p>bash</p>
<p>Copy code</p>
<p><code>java TextEditor</code></p>
</li>
</ol>
<hr>
<h3 id="references">References:</h3>
<ul>
<li>Java Documentation:  <a href="https://docs.oracle.com/javase/">https://docs.oracle.com/javase/</a></li>
<li>Java Stack Documentation:  <a href="https://docs.oracle.com/javase/8/docs/api/java/util/Stack.html">https://docs.oracle.com/javase/8/docs/api/java/util/Stack.html</a></li>
<li>StringBuilder Documentation:  <a href="https://docs.oracle.com/javase/8/docs/api/java/lang/StringBuilder.html">https://docs.oracle.com/javase/8/docs/api/java/lang/StringBuilder.html</a></li>
</ul>

