---


---

<p><a href="https://classroom.github.com/a/WOLOujNU"><img src="https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg" alt="Review Assignment Due Date"></a></p>
<p>Pedro Santos Sandoval<br>
Github: pesantossandoval<br>
<strong>P4 - Campus Navigation Project Using Graph Algorithms</strong></p>
<p><strong>Grade Aiming for:</strong>  A</p>
<hr>
<h3 id="specifications-for-a-c-70"><strong>Specifications for a C (70):</strong></h3>
<ul>
<li>Implemented functionality to:
<ul>
<li>Parse an input file and construct a graph using an  <strong>adjacency map</strong>.</li>
<li>Perform  <strong>Depth First Search (DFS)</strong>  and  <strong>Breadth First Search (BFS)</strong>  on the graph.</li>
<li>Display traversal order for DFS and BFS.</li>
<li>Provide a  <strong>menu system</strong>  to:
<ul>
<li>Loads the campus map (graph) file</li>
<li>Allows user to select starting building</li>
<li>Lets user choose between DFS and BFS</li>
<li>Displays the traversal result</li>
<li>Provides option to exit</li>
</ul>
</li>
</ul>
</li>
<li>Performed basic error checking for input file format, including:
<ul>
<li>Validating that all edges reference buildings listed in the nodes section.</li>
<li>Ensuring edge weights are positive and reasonable.</li>
</ul>
</li>
</ul>
<hr>
<h3 id="specifications-for-a-b-80"><strong>Specifications for a B (80):</strong></h3>
<p>Includes all functionality to get a C, plus:</p>
<ul>
<li>Implemented  <strong>Kruskal’s Algorithm</strong>  to calculate the  <strong>Minimum Spanning Tree (MST)</strong>  of the graph.</li>
<li>Improved error handling:
<ul>
<li>Validate building names (All buildings mentioned in EDGES exist in NODES section)</li>
<li>Verify edge weight validity (check for positive numbers, reasonable times for walking between buildings. For example, the edge weight cannot be 1000 minutes).</li>
</ul>
</li>
</ul>
<hr>
<h3 id="specifications-for-an-a-90"><strong>Specifications for an A (90):</strong></h3>
<p>Includes all functionality to get a B, plus:</p>
<ul>
<li>Implemented  <strong>Dijkstra’s Algorithm</strong>  to find the shortest path between two buildings.
<ul>
<li>Implement Dijkstra’s algorithm for finding the shortest paths between buildings (ask the user for the source and destination and show the time required to from the source to the destination).</li>
<li>Use the Java priority queue for an efficient implement Dijkstra’s algorithm</li>
<li>Store and reconstruct the shortest path along with the distance</li>
</ul>
</li>
</ul>
<hr>
<h3 id="key-features"><strong>Key Features:</strong></h3>
<ol>
<li>
<p><strong>Graph Representation:</strong></p>
<ul>
<li>Used an  <strong>adjacency map</strong>  for efficient representation of the campus map.</li>
</ul>
</li>
<li>
<p><strong>Graph Traversal Algorithms:</strong></p>
<ul>
<li><strong>Depth First Search (DFS):</strong>  Explores as far as possible before backtracking.</li>
<li><strong>Breadth First Search (BFS):</strong>  Explores all neighbors before moving deeper.</li>
</ul>
</li>
<li>
<p><strong>Graph Algorithms:</strong></p>
<ul>
<li><strong>Kruskal’s Algorithm:</strong>  Finds the MST to minimize the total weight of paths connecting all buildings.</li>
<li><strong>Dijkstra’s Algorithm:</strong>  Calculates the shortest path between two buildings and provides detailed directions.</li>
</ul>
</li>
<li>
<p><strong>Error Handling:</strong></p>
<ul>
<li>Validates file format and input.</li>
<li>Handles invalid or case-mismatched building names gracefully.</li>
</ul>
</li>
<li>
<p><strong>Menu:</strong></p>
<ul>
<li>Options to explore the graph using different algorithms.</li>
</ul>
</li>
</ol>
<hr>
<h3 id="instructions"><strong>Instructions:</strong></h3>
<p>-Download the Java files and the docs folder containing the text files.<br>
-Compile and run the EReader Java program from your command line<br>
-If you are unable to read files using Visual Studio Code, use  IntelliJ Idea, or us your terminal built into your computer, or terminal built into Visual Studio Code.</p>
<h3 id="test-instructions"><strong>Test Instructions:</strong></h3>
<p>Program handles Case Sensitivity: Enter building names in various cases (e.g., <code>library</code>, <code>LIBRARY</code>, <code>LiBrArY</code>).</p>
<p><strong>To exit the program:</strong> Enter <code>5 or 0</code> or type <code>exit</code> when asked to <code>Enter Choice:</code></p>
<ol>
<li>
<p><strong>Download Required Files:</strong></p>
<ul>
<li><code>CampusNavigationProject.java</code></li>
<li><code>Graph.java</code></li>
<li><code>DFS.java</code></li>
<li><code>BFS.java</code></li>
<li><code>Kruskal.java</code></li>
<li><code>Dijkstra.java</code></li>
<li>Sample input file:  <code>samplefile.txt</code></li>
</ul>
</li>
<li>
<p><strong>Compile the Program:</strong>  Run the following command in your terminal or IDE:</p>
<p><code>javac CampusNavigationProject.java</code></p>
</li>
<li>
<p><strong>Run the Program:</strong>  Execute the program using the sample file:</p>
<p><code>java CampusNavigationProject samplefile.txt</code></p>
</li>
<li>
<p><strong>Follow the Menu Prompts:</strong></p>
<ul>
<li>
<p><strong>Option 1: DFS Traversal</strong></p>
<ul>
<li>
<p>Enter a starting building:  <code>Library</code>.</p>
</li>
<li>
<p>Output:</p>
<p><code>DFS Traversal from Library: Library → Admin → Lab → Dorm → Cafeteria</code></p>
</li>
</ul>
</li>
<li>
<p><strong>Option 2: BFS Traversal</strong></p>
<ul>
<li>
<p>Enter a starting building: <code>Library</code>.</p>
</li>
<li>
<p>Output:</p>
<p><code>BFS Traversal from Library: Library → Admin → Cafeteria → Lab → Dorm</code></p>
</li>
</ul>
</li>
<li>
<p><strong>Option 3: Kruskal’s MST</strong></p>
<ul>
<li>
<p>Choose option to compute the minimum spanning tree.</p>
</li>
<li>
<p>Output:</p>
<p><code>Minimum Spanning Tree Results: Admin → Lab (1 minute) Library → Cafeteria (2 minutes) Library → Admin (3 minutes) Dorm → Lab (5 minutes)</code></p>
</li>
</ul>
</li>
</ul>
</li>
</ol>
<p>Note: It’s an undirected graph, so my output includes the edge Dorm → Lab (5 minutes) instead of the reverse.Same<br>
result as Lab → Dorm (5 minutes) from the instructions given.</p>
<ul>
<li><strong>Option 4: Dijkstra’s Algorithm</strong>
<ul>
<li>
<p>Enter starting and ending buildings:</p>
<ul>
<li>start: <code>Library</code></li>
<li>end:<code>Dorm</code>.</li>
</ul>
</li>
<li>
<p>Output:</p>
<pre><code>Start building: Library 
End building: Dorm 

Shortest Path Analysis:
Path: Library → Cafeteria → Dorm
Total time: 8 minutes

Detailed directions:
1. Start at Library
2. Walk to Cafeteria (2 minutes)
3. Walk to Dorm (6 minutes)
</code></pre>
</li>
</ul>
</li>
</ul>
<ol start="5">
<li>
<p><strong>Validate Error Handling:</strong></p>
<ul>
<li>Enter invalid building names:   <code>house</code>, the program identifies errors and prompts correctly.</li>
</ul>
</li>
</ol>
<h3 id="references"><strong>References:</strong></h3>
<ul>
<li>Java Documentation:  <a href="https://docs.oracle.com/javase/">https://docs.oracle.com/javase/</a></li>
<li>Zybooks:  <a href="https://learn.zybooks.com/">Code Fragment 14.7.2: Dijkstra’s Algorithm</a></li>
<li><strong>23-Graph-Traversal PDF example file:</strong> Provided as part of course materials for implementing BFS and DFS traversal.</li>
</ul>

