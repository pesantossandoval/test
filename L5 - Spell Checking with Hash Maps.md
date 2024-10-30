---


---

<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>
<p><a href="https://classroom.github.com/a/9ZqNhCDb"><img src="https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg" alt="Review Assignment Due Date"></a></p>
<p>Pedro Santos Sandoval<br>
L5 - Spell Checking with Hash Maps</p>
<p><strong>Grade Aiming for:</strong>  B (85)</p>
<hr>
<p><strong>Functionality to get a C (75):</strong></p>
<ul>
<li>Implement a hash table to store a dictionary of correctly spelled words.</li>
<li>Use a simple hash function (e.g., ASCII sum modulo table size) for mapping.</li>
<li>Implement collision resolution using separate chaining, where each bucket is an array with an ArrayList to handle collisions.</li>
<li>Add a function to suggest corrections for words with the same first letter and a length ±1 of the input word.</li>
<li>Provide a function to add new words to the dictionary.</li>
<li>Display the current load factor of the hash table.</li>
</ul>
<hr>
<p><strong>Functionality to get a B (85) includes functionality to get a C and:</strong></p>
<ul>
<li>Use a <strong>polynomial hash function</strong> to improve hash distribution.</li>
<li>Replace separate chaining with <strong>binary search trees (BSTs)</strong> in each bucket for more efficient lookups, insertions, and deletions.</li>
<li>Improve word suggestions to include words with the same first <strong>two letters</strong> and a length ±1 of the input word.</li>
<li>Implement a function to <strong>remove words</strong> from the dictionary.</li>
<li>Use a <strong>medium-sized dictionary</strong> (e.g., 172K words) to improve the spell-checking experience.</li>
<li><strong>Example</strong>: If the word “speell” is misspelled, the system may suggest [“spell”, “spelt”] based on similar entries in the dictionary.</li>
</ul>
<hr>
<p><strong>Key Features:</strong></p>
<ul>
<li><strong>Hash Table with Polynomial Hashing</strong>: Uses a polynomial hash function to achieve more uniform distribution.</li>
<li><strong>Binary Search Tree for Collision Resolution</strong>: Each bucket is implemented as a binary search tree to optimize search and insertion times.</li>
<li><strong>Suggestions for Misspelled Words</strong>: Provides suggestions for similar words based on length and initial letters.</li>
<li><strong>Add and Remove Words</strong>: Supports adding and removing words from the dictionary.</li>
<li><strong>Display Load Factor</strong>: Monitors and displays the load factor for efficiency tracking.</li>
<li><strong>Command-Line Interface</strong>: Allows users to input words or text files for spell-checking and view suggestions.</li>
</ul>
<hr>
<p><strong>Brief Explanation:</strong><br>
In this project, I created a spell checker in Java that uses a hash table with binary search trees for collision handling. The program accepts words or text files for spell-checking, and it suggests corrections for misspelled words by matching length and starting letters. The hash table uses a polynomial hash function for better distribution, while the load factor display allows users to observe table usage. Key functionalities include methods to add or remove words from the dictionary and dynamically suggest corrections.</p>
<hr>
<p><strong>Instructions:</strong></p>
<ul>
<li>Download the Java files:  <code>HashTable.java</code>,  <code>Dictionary.java</code>, and  <code>SpellChecker.java</code>.</li>
<li>Also download the dictionary text files:  <code>1k_words.txt</code>  and  <code>172k_words.txt</code>.</li>
<li>Compile and run the  <code>SpellChecker</code>  Java program from your command line.</li>
</ul>
<hr>
<p><strong>Test Instructions:</strong></p>
<ol>
<li>Open Terminal.</li>
<li>Navigate to the directory containing the Java files (<code>cd /path/to/your/java/files</code>).</li>
<li>Compile the code using:<pre class=" language-bash"><code class="prism  language-bash">javac Dictionary.java HashTable.java SpellChecker.java
</code></pre>
</li>
<li>Run the program with:<pre class=" language-bash"><code class="prism  language-bash">java SpellChecker
</code></pre>
</li>
<li></li>
</ol>
<p><strong>Example Run:</strong></p>
<pre class=" language-plaintext"><code class="prism  language-plaintext">Enter file name for the dictionary: 
1k words
Suggestions word: 
cat
Suggestions for 'cat': [came, car, can, care, case, camp, cat, call, card]
Current Load Factor: 0.171
Add word to dictionary: 
bat
Added new word to Dictionary: bat
Current Load Factor after adding 'bat': 0.171
Dictionary contains 'bat': true
Word to remove from the dictionary: 
can
Word 'can' removed: true
Word 'can' still exists after removal: false
</code></pre>
<hr>
<p><strong>References:</strong></p>
<ul>
<li>Java Documentation: <a href="https://docs.oracle.com/javase/">https://docs.oracle.com/javase/</a></li>
</ul>

