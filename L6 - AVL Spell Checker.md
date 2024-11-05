---


---

<blockquote>
<h1 id="l6---avl-spell-checker">L6 - AVL Spell Checker</h1>
</blockquote>
<p><strong>Author</strong>: Pedro Santos Sandoval<br>
<strong>Grade Aiming For</strong>: A (95)</p>
<h2 id="overview">Overview</h2>
<p>This project is a dictionary and spell-checking tool implemented using an AVL tree data structure. It allows users to insert, search, and retrieve word suggestions based on prefix matches and spelling correction for misspelled words. The AVL tree maintains balance through rotations to ensure efficient operations.</p>
<hr>
<h2 id="features">Features</h2>
<h3 id="functionality-to-get-a-c-75">Functionality to Get a C (75)</h3>
<ul>
<li><strong>Dictionary Creation with AVL Tree</strong>: Implements a dictionary using an AVL tree, allowing efficient insertions and searches while maintaining balance.</li>
<li><strong>Insert and Search Operations</strong>: Supports the insertion of words and searches for confirming if specific words exist.</li>
<li><strong>Basic Rotation for Tree Balance</strong>: Includes left, right, left-right, and right-left rotations to keep the tree balanced.</li>
</ul>
<h3 id="functionality-to-get-a-b-85">Functionality to Get a B (85)</h3>
<ul>
<li><strong>Prefix-Based Autocomplete Suggestions</strong>: Provides word suggestions for a given prefix using efficient tree traversal.</li>
<li><strong>File Input</strong>: Allows the user to load words from a small dictionary file to populate the AVL tree dynamically.</li>
<li><strong>Efficient Traversal</strong>: Uses recursive traversal to collect all words matching a given prefix while minimizing time complexity.</li>
</ul>
<h3 id="functionality-to-get-an-a-95">Functionality to Get an A (95)</h3>
<ul>
<li><strong>Levenshtein Distance-Based Spell-Checking</strong>: Implements spell-checking with the Levenshtein distance algorithm, suggesting the closest matching words for misspellings.</li>
<li><strong>Extended Dictionary</strong>: Allows loading a larger dictionary file to improve the spell-checking experience.</li>
<li><strong>Dynamic Suggestions Based on Similarity</strong>: Ranks corrections based on their edit distance to the misspelled word, ensuring the most relevant suggestions.</li>
</ul>
<hr>
<h2 id="brief-explanation">Brief Explanation</h2>
<p>This project is a spell-checking application in Java that utilizes an AVL tree to maintain a dictionary of words with high efficiency. The AVL tree is a self-balancing binary search tree that keeps operations like insertion and search efficient by maintaining a balanced structure through rotations. This balance is particularly beneficial for handling large dictionaries, ensuring quick access to any word in the tree. The tool supports functions to add new words, verify word existence, and provide suggestions based on a prefix. It makes it practical for autocomplete functionality where rapid access to possible word completions is essential.</p>
<p>The spell-checking feature further enhances the tool’s utility by using the Levenshtein distance algorithm to suggest corrections for misspelled words. This algorithm calculates the minimum number of edits required to transform one word into another, allowing the program to recommend relevant corrections for common misspellings. Users can interact with the application through a command-line interface, which can load dictionaries from text files, perform spell checks, and view suggestions. Overall, this project combines efficient data management with intuitive features, creating a responsive and robust spell-checking tool well-suited for larger datasets.</p>
<h2 id="key-components">Key Components</h2>
<ol>
<li><strong>AVL Tree with Balance Operations</strong>: The AVL tree structure uses rotations to maintain balance during insertions, enhancing search efficiency.</li>
<li><strong>Prefix-Based Autocomplete</strong>: Offers autocomplete functionality by traversing the AVL tree and collecting words with the given prefix.</li>
<li><strong>Levenshtein Distance for Spell-Checking</strong>: Uses the Levenshtein distance algorithm to suggest corrections for misspelled words, prioritizing suggestions by similarity.</li>
<li><strong>User Interface</strong>: Provides an interactive CLI allowing users to load files, check spelling, get suggestions, and exit the program.</li>
<li><strong>File Handling</strong>: Supports loading dictionary words from small and mid-sized text files.</li>
</ol>
<hr>
<h2 id="instructions">Instructions</h2>
<h3 id="setup">Setup</h3>
<ol>
<li>
<p><strong>Download the following files</strong>:</p>
<ul>
<li><code>AVLTreeString.java</code></li>
<li><code>LevenshteinDistanceCalculator.java</code></li>
<li>Dictionary files (<code>1k words.txt</code>  and  <code>172k words.txt</code>) to be used for testing.</li>
</ul>
</li>
<li>
<p><strong>Open Terminal</strong>:</p>
<ul>
<li>Open a terminal or command prompt to run the program.</li>
</ul>
</li>
<li>
<p><strong>Navigate to Project Directory</strong>:</p>
<ul>
<li>Use the <code>cd</code> command to navigate to the directory where the compiled <code>.class</code> files are located.</li>
</ul>
<pre class=" language-bash"><code class="prism  language-bash"><span class="token function">cd</span> /path/to/your/project
</code></pre>
</li>
<li>
<p><strong>Compile the Code</strong>:</p>
<p><code>javac AVLTreeString.java LevenshteinDistanceCalculator.java</code></p>
</li>
<li>
<p><strong>Run the Program</strong>:</p>
<p><code>java AVLTreeString</code></p>
</li>
</ol>
<h2 id="example-run">Example Run</h2>
<p>Enter file name for the dictionary:<br>
1k words</p>
<p>Choose an option:<br>
1 - Prefix Search<br>
2 - Spell-Check<br>
3 - Exit Program<br>
Enter your choice: 1</p>
<p>Enter a prefix to search (type ‘exit’ to quit program):<br>
app<br>
Suggestions for prefix ‘app’: [apple, application, appraise]</p>
<p>Choose an option:<br>
1 - Prefix Search<br>
2 - Spell-Check<br>
3 - Exit Program<br>
Enter your choice: 2</p>
<p>Enter a word to check spelling and get suggestions (type ‘exit’ to quit program):<br>
cas<br>
Suggestions for ‘cas’: [cat, car]</p>
<p>Choose an option:<br>
1 - Prefix Search<br>
2 - Spell-Check<br>
3 - Exit Program<br>
Enter your choice: 3</p>
<p>Exit Program</p>
<hr>
<h2 id="references">References</h2>
<ul>
<li>Java Documentation:  <a href="https://docs.oracle.com/middleware/1213/coherence/java-reference/com/tangosol/util/Tree.html">https://docs.oracle.com/javase/avl</a></li>
<li>Levenshtein Distance Algorithm: Based on the GeeksforGeeks implementation  <a href="https://www.geeksforgeeks.org/levenshtein-distance-between-two-strings-in-java-using-recursion/">Levenshtein Distance</a></li>
<li>AVLTreeIntgerExercise.java given by Professor: Alark Joshi</li>
</ul>
<hr>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p> <p><a href="https://classroom.github.com/a/9ZqNhCDb"><img src="https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg" alt="Review Assignment Due Date"></a></p>

