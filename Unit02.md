**Unit 2: Solving Problems By Searching** <span id="2"></span> 
*This unit will teach you how to build and search data structures needed
to create software agents.  We will focus on graph structures and a few
classical graph search algorithms because their understanding is
important for solving many problems that arise in AI.  Graphs enable
logical description of the problems.  A graph search, then, represents
the search for the solutions. We will begin this unit with some basic
graph theory definitions and then learn how to solve some problems with
a graph.  The last section of this unit has a video that will expand the
understanding of the graph structures.*

**Unit 2 Time Advisory**  
This unit should take you 29 hours to complete.  
  
 ☐    Subunit 2.1: 3 hours

☐    Subunit 2.2: 4 hours

☐    Subunit 2.3: 4 hours

☐    Subunit 2.4: 1 hour

☐    Subunit 2.5: 5 hours

☐    Subunit 2.6: 12 hours

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, students will be able to:

-   Define a graph.
-   Define a tree, binary tree, and red-black tree.
-   Define what a minimum spanning tree is.
-   Build by coding binary and red-black trees and skip list.
-   Code the basic algorithms that perform searches on the graph
    structures.
-   Compare and contrast Dijkstra’s algorithm, breadth-first search,
    and  depth-first search.
-   Use graph structures and basic algorithms to encode problems of AI
    reasonably well.

**2.1 Graphs** <span id="2.1"></span> 
**2.1.1 Graph Definition** <span id="2.1.1"></span> 
-   **Reading: planetmath.org: Cameron McLeman’s “Graph"**
    Link: planetmath.org: Cameron McLeman’s
    “[Graph](https://resources.saylor.org/archived/wp-content/uploads/2012/06/Graph.pdf)”
    (PDF)  
        
     Instructions: Study the definition of a graph from this section and
    draw some examples of your own.   
        
     About the link: planetmath.org is a mathematics encyclopedia with
    entries written and reviewed by members.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/).  It is
    attributed to Planetmath.org and the original version can be found
    [here](http://planetmath.org/encyclopedia/Adjacent.html) (HTML).

**2.1.2 Binary Tree** <span id="2.1.2"></span> 
-   **Reading: planetmath.org: Yann Lamontagne’s “Binary Tree"**
    Link: planetmath.org: Yann Lamontagne’s “[Binary
    Tree](https://resources.saylor.org/archived/wp-content/uploads/2012/06/CS408-2.1.2-Binary-Trees.pdf)”
    (PDF)  
        
     Instructions: Make sure you know how a binary tree differs from a
    regular tree after the reading this section.  
        
     About the link: planetmath.org is a mathematics encyclopedia with
    entries written and reviewed by members.  
                              
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/)(HTML). It is
    attributed to Planetmath.org and the original version can be
    found [here](http://planetmath.org/?method=l2h&from=objects&name=BinaryTree&op=getobj)(HTML).

**2.1.3 Example Problem: Minimum Spanning Tree** <span
id="2.1.3"></span> 
-   **Reading: planetmath.org: Cameron McLeman’s “Minimum Spanning
    Tree"**
    Link: planetmath.org:Cameron McLeman’s “[Minimum Spanning
    Tree](https://resources.saylor.org/archived/wp-content/uploads/2012/06/CS408-2.1.3-Minimum-Spanning-Tree.pdf)”
    (PDF)  
        
     Instructions: Read about minimum spanning trees and try to figure
    out how Prim's algorithm works; the solution can be found at
    brpreiss.com's link “[Prim's
    Algorithm](http://www.brpreiss.com/books/opus4/html/page577.html).”
    (HTML)  Before you check the solution, try to solve problem
    yourself.  After you have solved the problem (or if you have spent a
    couple of hours working on it, and are stumped!), study the
    solution.   
        
     About the link: planetmath.org is a mathematics encyclopedia with
    entries written and reviewed by members.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/).  It is
    attributed to Planetmath.org and the original version can be found
    [here](http://planetmath.org/?method=l2h&from=objects&id=2710&op=getobj). 

**2.2 Tree Search Algorithms** <span id="2.2"></span> 
**2.2.1 Binary Search Trees** <span id="2.2.1"></span> 
-   **Reading: The University of Auckland in New Zealand: John Morris’s
    “Binary Search Tree"**
    Link: The University of Auckland in New Zealand: John Morris’s
    “[Binary Search
    Tree](https://resources.saylor.org/archived/wp-content/uploads/2012/06/CS408-2.2.1-Binary-Trees.pdf)”
    (PDF)  
        
     Instructions: Read the article to learn how to build and search
    binary trees.  
        
     About the link: This link is provided by John Morris, a professor
    in the Electrical and Computer Engineering Department at the
    University of Auckland in New Zealand.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of John Morris, and can be viewed in its original
    form
    [here](http://www.cs.auckland.ac.nz/~jmor159/PLDS210/niemann/s_bin.htm). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.  

**2.2.2 Red-Black Trees** <span id="2.2.2"></span> 
-   **Reading: The University of Auckland in New Zealand: John Morris’s
    “Red-Black Trees"**
    Link: The University of Auckland in New Zealand: John Morris’s
    “[Red-Black
    Trees](https://resources.saylor.org/archived/wp-content/uploads/2012/06/CS408-2.2.2-Red-BlackTrees.pdf)”
    (PDF)  
        
     Instructions: Please read the linked material above.  After reading
    this section, you should know how a binary tree differs from a
    red-black tree and understand the basics of building and searching
    red-black trees.   
        
     About the link: This link is provided by John Morris, a professor
    in the Electrical and Computer Engineering Department at University
    of Auckland in New Zealand.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of John Morris, and can be viewed in its original
    form
    [here](http://www.cs.auckland.ac.nz/~jmor159/PLDS210/niemann/s_rbt.htm). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.  

**2.2.3 Skip List** <span id="2.2.3"></span> 
-   **Reading: The University of Auckland in New Zealand: John Morris’s
    “Skip Lists"**
    Link: The University ofAuckland in New Zealand: John Morris’s “[Skip
    List](https://resources.saylor.org/archived/wp-content/uploads/2012/06/CS408-2.2.3-Skiplists.pdf)”
    (PDF)  
        
     Instructions: Please learn how to build and search a skip list by
    reading the linked material.  
        
     About the link: This link is provided by John Morris, a professor
    in the Electrical and Computer Engineering Department at University
    of Auckland in New Zealand.  
        
     Terms of Use: The linked material above has been reposted by the
    kind permission of John Morris and can be viewed in its original
    form
    [here](http://www.cs.auckland.ac.nz/~jmor159/PLDS210/niemann/s_skl.htm). 
    Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.  

**2.3 Common Search Techniques with Graphs** <span id="2.3"></span> 
**2.3.1 Depth-first Search** <span id="2.3.1"></span> 
-   **Reading: Wikipedia’s “Depth-First Search"**
    Link: Wikipedia’s “[Depth-First
    Search](https://resources.saylor.org/archived/wp-content/uploads/2012/06/CS408-2.2.1-Binary-Trees.pdf)”
    (PDF)  
        
     Instructions: Read this entry to learn how depth-first search
    works.  Be sure to study the example included.   
        
     About the link: en.wikipedia.org is a web-based, free-content
    encyclopedia project based on an openly editable model.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/)(HTML).  You can
    find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Depth-first_search)(HTML).

**2.3.2 Breadth-First Search** <span id="2.3.2"></span> 
-   **Reading: Wikipedia’s “Breadth-First Search"**
    Link: Wikipedia’s “[Breadth-First
    Search](https://resources.saylor.org/archived/wp-content/uploads/2012/06/CS408-2.3.2-BreadthFirstSearch.pdf)”
    (PDF)  
        
     Instructions: Read this section and make sure you know the
    differences between depth-first and breadth-first search
    algorithms.   
        
     About the link: en.wikipedia.org is a web-based, free-content
    encyclopedia.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/)(HTML).  You can
    find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Breadth-first_search)(HTML).

**2.3.3 Dijkstra's Algorithm** <span id="2.3.3"></span> 
-   **Reading: Wikipedia’s “Dijkstra's Algorithm"**
    Link: Wikipedia’s “[Dijkstra's
    Algorithm](https://resources.saylor.org/archived/wp-content/uploads/2012/06/CS408-2.3.2-Dijkstras-algorithm.pdf)”
    (PDF)  
        
     Instructions: Read this entry to learn how Dijkstra's algorithm
    works.  Please work through the example included in this entry.  
        
     About the link: en.wikipedia.org is a web-based, free-content
    encyclopedia.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/)(HTML).  You can
    find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Dijkstra's_algorithm)(HTML).

**2.4 Search Algorithms in General** <span id="2.4"></span> 
-   **Reading: Wikipedia’s “Search Algorithm”**
    Link: Wikipedia’s “[Search
    Algorithm](https://resources.saylor.org/archived/wp-content/uploads/2012/06/Wikipedia-Search-Algorithm.pdf)”
    (PDF)  
        
     Instructions: Read the entry linked above for an overview of search
    techniques.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the Wikipedia source article
    [here](http://en.wikipedia.org/wiki/Search_algorithm) (HTML).

**2.5 Basic Notions in Graph Theory** <span id="2.5"></span> 
-   **Lecture: videolectures.net: Zoubin Ghahramani’s “Graphical Models:
    Parts 1-3”**
    Link: videolectures.net: Zoubin Ghahramani’s “[Graphical Models:
    Parts 1-3](http://videolectures.net/mlss07_ghahramani_grafm/)”
    (Adobe Flash and Windows Media Player)  
        
     Instructions: Watch this three-part video on graph theory to
    develop a better understanding of how to use graphs in AI.  After
    viewing the first part, you should know about directed, undirected,
    and factor graphs, conditional independence, d-separation, and plate
    notation.  The second part will teach you about inference in
    graphical models, key ideas in belief propagation, and the junction
    tree algorithm. Watch the third part for fun, trying to follow along
    as much as possible.  The first lecture is 53 minutes; the second is
    58 minutes; and the third is 1 hour and 18 minutes. You can also
    download the PowerPoint slides in a PDF format by clicking on the
    link under “See Also.”  
        
     About the link: Zoubin Ghahramani is Professor of Information
    Engineering at Department of Engineering, University of Cambridge. 
    His research interests include Bayesian approaches to machine
    learning, artificial intelligence, statistics, information
    retrieval, bioinformatics, and computational motor control.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial- NoDerivatives License
    3.0](http://creativecommons.org/licenses/by-nc-nd/3.0/)(HTML).  It
    is attributed to (Zoubin Ghahramani).

**2.6 Graph Examples in Code** <span id="2.6"></span> 
-   **Assignment: Artificial Intelligence Center’s “Route Finding
    Agent”**
    Link: Artificial Intelligence Center’s [“Route Finding
    Agent”](https://code.google.com/p/aima-java/source/browse/trunk/aima-gui/src/main/java/aima/gui/applications/search/map/RouteFindingAgentApp.java?r=1088)
    (JAVA)  
        
     Instructions: Create a route-finding agent given the environment in
    the form of a graph.  One possible solution can be found via the
    link above, under the “Route Finding Agent” section.  Study the
    solution code after you have already solved the problem, or if you
    have spent a substantial amount of time and are stuck (this problem
    could take you up to 12 hours to solve!)  
        
     About the link: The code provided by the link is a Java
    implementation of search algorithms from Norvig And Russell's
    "Artificial Intelligence - A Modern Approach,” 3rd Edition.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the web page above.


