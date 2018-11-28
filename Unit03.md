---
layout: default
title: "CS408: Advanced Artificial Intelligence"
course_description: "A detailed examination of the concepts and methods of artificial intelligence. Topics include heuristic search procedures for general graphs, game playing strategies, resolution and rule based deduction systems, knowledge representation, and reasoning with uncertainty."
next: ../Unit04
previous: ../Unit02
---
**Unit 3: Logical Agents And Knowledge Representation** <span
id="3"></span> 
*Intelligent agents are supposed to make rational decisions, which are
not just logically reasoned, but optimal as well, given the available
information.  Accordingly, in this unit, we will review the study of
logic and conceptualize the differences between propositional logic,
first-order logic, fuzzy logic, and default logic.  This unit will also
present an overview of common statistical tools used in AI.  In the last
part of this unit, we will try to clarify our definition of knowledge
representation and will discuss its roles based on research conducted at
MIT.*

**Unit 3 Time Advisory**  
This unit should take you 27 hours to complete.  
  
 ☐    Subunit 3.1: 5 hours

☐    Subunit 3.2: 5 hours

☐    Subunit 3.3: 5 hours

☐    Subunit 3.4: 12 hours

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, students will be able to:

-   Define and compare/contrast propositional logic, first-order logic,
    fuzzy logic, and default logic.
-   List the rules of probability and define Bayes’ theorem and Bayesian
    inference.
-   Use probabilistic graphical models.
-   Compare and contrast the hidden Markov model and the Baysian
    network.
-   Define Kaufman filter and decsion theory.
-   Explain what knowledge representation encompasses.
-   Design a simple searching software agent.

**3.1 Logic Programming** <span id="3.1"></span> 
-   **Reading: Wikipedia’s “Logic Programming”**
    Link: Wikipedia’s “[Logic
    Programming](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/06/Wikipedia-Logic-Programming.pdf)”
    (PDF)  
        
     Instructions: Read this web page on logic programming. Make sure
    you understand the differences between abductive logic, metalogic,
    constraint logic, concurrent logic, and inductive logic,
    higher-order logic, and linear logic programming.  This reading
    covers subunits 3.1.1-3.1.7.   
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the Wikipedia source article
    [here](http://en.wikipedia.org/wiki/Logic_programming) (HTML).

-   **Lecture: videolectures.net: Alwen Tiu’s “Introduction to Logic:
    Parts 1-3”**
    Link: videolectures.net: Alwen Tiu’s “[Introduction to Logic: Parts
    1-3](http://videolectures.net/ssll09_tiu_intlo/)” (Adobe Flash and
    Windows Media Player)  
        
     Instructions: Watch the first lecture on logic and compare it to
    the reading above.  In this lecture, you will learn about the syntax
    and semantics of propositional logic, boolean functions,
    satisfiability, and binary decision trees.  You will need to know
    the difference between conjunctive and disjunctive normal forms. 
    The first lecture is 56 minutes long. You can also download the
    PowerPoint slides in a PDF format by clicking on the link under “See
    Also.”  
        
     Then, watch the second lecture to learn about first-order logic. 
    Pay particular attention to the examples. This second lecture is 39
    minutes long.   
        
     Finally, watch the third lecture, which presents modal logic.  Make
    sure you know the differences between propositional, first-order,
    and modal logic.  The third lecture is 49 minutes long.  
        
     About the link: Alwen Tiu is a professor at the Australian National
    University.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial- NoDerivatives License
    3.0](http://creativecommons.org/licenses/by-nc-nd/3.0/)(HTML).  It
    is attributed to (John Lloyd).

**3.1.1 Abductive Logic** <span id="3.1.1"></span> 
**3.1.2 Metalogic** <span id="3.1.2"></span> 
**3.1.3 Constraint Logic** <span id="3.1.3"></span> 
**3.1.4 Concurrent Logic** <span id="3.1.4"></span> 
**3.1.5 Inductive Logic** <span id="3.1.5"></span> 
**3.1.6 Higher-Order Logic** <span id="3.1.6"></span> 
**3.1.7 Linear Logic Programming** <span id="3.1.7"></span> 
**3.2 Probabilistic Methods for Uncertain Reasoning** <span
id="3.2"></span> 
**3.2.1 Bayesian Network** <span id="3.2.1"></span> 
-   **Reading: PR-OWL’s “Bayesian Networks”**
    Link: PR-OWL’s “[Bayesian
    Networks](http://www.pr-owl.org/basics/bn.php)” (HTML)  
        
     Instructions: Read the above web page on Bayesian networks.  Focus
    on the definitions it provides and work through the example
    provided.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the web page above.

-   **Lecture: videolectures.net: Christopher Bishop’s “Introduction to
    Bayesian Inference: Part 1”**
    Link: videolectures.net: Christopher Bishop’s “[Introduction to
    Bayesian Inference: Part
    1](http://videolectures.net/mlss09uk_bishop_ibi/)” (Adobe Flash and
    Windows Media Player)  
        
     Instructions: Watch the first part of the video above, which
    discusses Bayesian Inference.  You may wish to work through the
    slides provided on the right-hand side of the screen as Bishop
    lectures.  Focus on learning the rules of probability and
    understanding the terms Bayes' theorem, Bayesian inference,
    probabilistic graphical models.  Make sure you know how factor
    graphs are used.  This lecture is 1 hour and 17 minutes long. You
    can also download the PowerPoint slides in a PDF format by clicking
    on the link under “See Also.”  
        
     About the link: Christopher Bishop works for Microsoft Research.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial- NoDerivatives License
    3.0](http://creativecommons.org/licenses/by-nc-nd/3.0/)(HTML).  It
    is attributed to (Christopher Bishop).

**3.2.2 Hidden Markov Model** <span id="3.2.2"></span> 
-   **Reading: Wikipedia’s “Hidden Markov Model”**
    Link: Wikipedia’s “[Hidden Markov
    Model](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/06/Wikipedia-Hidden-Markov-Model.pdf)”
    (PDF)  
        
     Instructions: Read the linked entry above, which discusses the
    hidden Markov model.  Focus on the 'Description' and 'Architecture'
    sections of the web site.   
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the Wikipedia source article
    [here](http://en.wikipedia.org/wiki/Hidden_Markov_model) (HTML).

**3.2.3 Other Methods for Uncertain Reasoning** <span
id="3.2.3"></span> 
**3.2.3.1 Kalman Filter** <span id="3.2.3.1"></span> 
-   **Reading: Wikipedia’s “Kalman Filter”**
    Link: Wikipedia’s“ [Kalman
    Filter](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/06/Wikipedia-Kalman-Filter.pdf)”
    (PDF)  
        
     Instructions: Read this entry on the Kalman Filter, paying
    attention to the introductory part.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the Wikipedia source article
    [here](http://en.wikipedia.org/wiki/Kalman_filter) (HTML).

**3.2.3.2 Decision Theory** <span id="3.2.3.2"></span> 
-   **Reading: Wikipedia’s “Decision Theory”**
    Link: Wikipedia’s “[Decision
    Theory](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/06/Wikipedia-Decision-Theory.pdf)”
    (PDF)  
        
     Instructions: Read this entry, making sure you understand the
    'Normative and Descriptive Decision Theory' and 'What Kinds of
    Decisions Need a Theory?' sections of the text.    
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  You
    can find the Wikipedia source article
    [here](http://en.wikipedia.org/wiki/Decision_theory) (HTML).

**3.3 Knowledge Representation and Reasoning** <span id="3.3"></span> 
-   **Lecture: videolectures.net: Maurice Pagnucco’s “Knowledge
    Representation and Reasoning: Part 1”**
    Link: videolectures.net: Maurice Pagnucco’s “[Knowledge
    Representation and Reasoning: Part
    1](http://videolectures.net/ssll09_pagnucco_krr/)” (Adobe Flash and
    Windows Media Player)  
        
     Instructions: Watch the first video.  Focus on learning how to
    represent what we know and how to use representation to make
    inferences about that knowledge.  Work carefully through the
    examples included in the lecture.  This lecture is 54 minutes
    long.   
        
     About the link: Maurice Pagnucco is a professor at the School of
    Computer Science and Engineering at University of New South Wales.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial- NoDerivatives License
    3.0](http://creativecommons.org/licenses/by-nc-nd/3.0/)(HTML).  It
    is attributed to (Maurice Pagnucco).

**3.3.1 Discussion on Knowledge Representation** <span
id="3.3.1"></span> 
-   **Reading: MIT: Randall Davis, Howard Shrobe, and Peter Szolovit's
    “What Is a Knowledge Representation?”**
    Link:MIT: Randall Davis, Howard Shrobe, and Peter Szolovit's “[What
    Is a Knowledge
    Representation?](http://groups.csail.mit.edu/medg/ftp/psz/k-rep.html)”
    (HTML)  
        
     Instructions: Read this web page, which presents different views on
    knowledge representation.  This reading covers sections
    3.3.1.1-3.3.1.4. Contrast the reading with your own opinions.   
        
     About the link: The article above is written by Randall Davis,
    Howard Shrobe, and Peter Szolovit, researchers in the field of AIat
    MIT.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the web page above.

**3.3.1.1 Terminology and Perspective** <span id="3.3.1.1"></span> 
**3.3.1.2 What is a Knowledge Representation?** <span
id="3.3.1.2"></span> 
**3.3.1.3 Consequences for Research and Practice** <span
id="3.3.1.3"></span> 
**3.3.1.4 The Goal of Knowledge Representation Research** <span
id="3.3.1.4"></span> 
**3.4 Coding Drills** <span id="3.4"></span> 
-   **Assignment: Artificial Intelligence Center’s “N-Queens Problem
    Demo”**
    Link: Artificial Intelligence Center’s “[N-Queens Problem
    Demo](https://web.archive.org/web/20131006152937/http://www.apl.jhu.edu/~hall/NQueens.html)”
    (JAVA)  
        
     Instructions: Please follow the instructions and solve the
    following problem.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the web page above.


