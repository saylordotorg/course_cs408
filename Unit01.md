**Unit 1: Intelligent Agents and Problems Of AI** <span id="1"></span> 
*AI is often seen through the autonomous, rational intelligent agents
paradigm, which we will emphasize in this unit.  This unit will begin by
discussing what software agents are and how agents differ from programs
in general.  The unit will then provide a natural taxonomy of autonomous
agents and discusses possibilities for further classification before
presenting those problems in AI that seem to received the most
attention.  The problem of creating intelligence is then broken down
into a number of specific sub-problems, which consist of particular
traits that should be found in an intelligent system.  Note that
different researchers approach the problems of AI from different
perspectives, depending on their respective training, fields of
expertise, and favored tools.*

**Unit 1 Time Advisory**  
This unit should take you 28 hours to complete.  
  
 ☐    Subunit 1.1: 6 hours

☐    Subunit 1.2: 5 hours

☐    Subunit 1.3: 5 hours

☐    Subunit 1.4: 12 hours

**Unit1 Learning Outcomes**  
Upon successful completion of this unit, students will be able to:

-   List various definitions of the term “intelligent agent.”
-   List and define the major problems that AI addresses.
-   Compare and contrast the terms knowledge, representation, and
    reasoning.
-   Define the forms of knowledge representation.
-   Describe why planning is difficult.
-   Explain the basics of learning theory.
-   Describe the difference between deduction and induction.
-   Define the notion of probability and Bayes’ rule.
-   List and define the major approaches AI takes in solving problems.

**1.1 Is It an Agent, or Just a Program?** <span id="1.1"></span> 
-   **Reading: The University of Memphis: Stan Franklin and Art
    Graesser's “Is It an Agent, or Just a Program?: A Taxonomy for
    Autonomous Agents”**
    Link: The University of Memphis: Stan Franklin and Art Graesser’s
    [“Is It an Agent, or Just a
    Program?”](http://www.msci.memphis.edu/~franklin/AgentProg.html)
    (HTML)  
        
     Instructions:  This resource covers subsections 1.1.1-1.1.5.  Read
    the webpage to learn about the advent of software agents.  Memorize
    the definitions of the AIMA, Maes, KidSim, Hayes-Roth, IBM, SodaBot,
    Foner, and Brustoloni Agents.  Make sure you know how to define
    “agency” and work to memorize Franklin's definition of an agent. 
    Read through the examples of the different taxonomies and
    classifications of agents.   
        
     About the link: Stan Franklin and Art Graesser are researchers of
    AI, and professors of computer science and cognitive science at the
    University of Memphis.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the web pages above.

**1.1.1 What is an agent?** <span id="1.1.1"></span> 
**1.1.2 The Essence of Agency** <span id="1.1.2"></span> 
**1.1.3 Agent Classifications** <span id="1.1.3"></span> 
**1.1.4 A Natural Kinds Taxonomy of Agents** <span id="1.1.4"></span> 
**1.1.5 Subagents and Societies of Agents** <span id="1.1.5"></span> 
**1.1.6 John Lloyd on Intelligent Agents** <span id="1.1.6"></span> 
-   **Lecture: videolectures.net: John Lloyd’s “Intelligent Agents: Part
    1”**
    Link: videolectures.net: John Lloyd’s“[Intelligent Agents: Part
    1](http://videolectures.net/ssll09_lloyd_inta/)” (Adobe Flash and
    Windows Media Player)  
        
     Instructions: Watch the first part of this three-part video series
    by John Lloyd.  As he lectures you may wish to work through the
    slides included on the page.  Throughout the lecture, Professor
    Lloyd talks about AIMA agents and presents some pertinent examples. 
    Please compare his thoughts with yours and Franklin's from the
    previous sections.  This lecture is approximately 50 minutes in
    length. You can also download the PowerPoint slides in a PDF format
    by clicking on the link under “See Also.”  
        
     About the link: John Lloyd is a professor at Australian National
    University who shares lectures on videolectures.net.  In the
    lecture, he introduces the basic ideas of agents and describes some
    agent architectures.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial- NoDerivatives License
    3.0](http://creativecommons.org/licenses/by-nc-nd/3.0/)(HTML).  It
    is attributed to (John Lloyd).

**1.1.7 Stan Franklin - A Cognitive Theory of Everything** <span
id="1.1.7"></span> 
-   **Lecture: Google Videos: Stan Franklin’s “A Cognitive Theory of
    Everything”**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**1.2 Overview of AI General Problems** <span id="1.2"></span> 
-   **Reading: Wikipedia’s “Artificial Intelligence: Problems”**
    Link: Wikipedia’s “[Artificial Intelligence:
    Problems](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/06/CS408-1.3-Artificial-Intelligence-Approaches.pdf)”
    (PDF)  
      
        
     Instructions: Read this entry on the general problems arising in
    the field of AI.  After completing this assignment, you should know
    the meaning of terms such as knowledge representation, planning,
    learning, natural language processing, motion and manipulation,
    perception, social intelligence, creativity, and general
    intelligence.  This link covers subsections 1.2.1-1.2.9.  Note that
    sections 1.2.2-1.2.4 have additional resources assigned to them (see
    below) and require extra attention.  
        
     About the link: The article above is an entry from
    en.wikipedia.org, which is a web-based, free-content encyclopedia
    project based on an openly editable model.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/)(HTML).  This
    article is a modified version of an article of the same title
    originally found on Wikipedia.  The Saylor Foundation has
    reformatted the entry and has omitted several of the original
    sections.You can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Artificial_intelligence#Problems)(HTML).  

     

**1.2.1 Deduction, Reasoning, Problem Solving** <span
id="1.2.1"></span> 
**1.2.2 Knowledge Representation** <span id="1.2.2"></span> 
-   **Lecture: videolectures.net: Maurice Pagnucco’s “Knowledge
    Representation and Reasoning: Part 1”**
    Link: videolectures.net: Maurice Pagnucco’s “[Knowledge
    Representation and Reasoning: Part
    1](http://videolectures.net/ssll09_pagnucco_krr/)” (Adobe Flash and
    Windows Media Player)  
        
     Instructions: Watch the first part of this three-part video series
    by Maurice Pagnucco.  After viewing the lecture, you should be able
    to define the terms knowledge, representation, and reasoning;
    realize the advantages of this approach; and define the forms of
    knowledge representation.  This lecture is approximately 1 hour
    long.   
        
     About the link: Maurice Pagnucco is a professor at the School of
    Computer Science and Engineering at University of New South
    Wales.   
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial- NoDerivatives License
    3.0](http://creativecommons.org/licenses/by-nc-nd/3.0/)(HTML).  It
    is attributed to (Maurice Pagnucco).

**1.2.3 Planning** <span id="1.2.3"></span> 
-   **Lecture: videolectures.net: Jussi Rintanen’s “Planning: Part 1”**
    Link: videolectures.net: Jussi Rintanen’s“[Planning: Part
    1](http://videolectures.net/ssll09_rintanen_aip/)” (Adobe Flash and
    Windows Media Player)  
        
     Instructions: Watch the first part of the video by Jussi Rintanen. 
    You may wish to work through the slides provided on the right-hand
    side of the screen as Professor Rintanen lectures.  After viewing
    the lecture, you should understand why planning can be difficult and
    be able to define the term “transition systems.”  This video is
    about an hour long. You can also download the PowerPoint slides in a
    PDF format by clicking on the link under “See Also.”  
        
     About the link: Jussi Rintanen is a researcher and an associate
    professor at NICTA Canberra Research Laboratory and The Australian
    National University.   
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial- NoDerivatives License
    3.0](http://creativecommons.org/licenses/by-nc-nd/3.0/)(HTML).  It
    is attributed to (Jussi Rintanen).

**1.2.4 Learning** <span id="1.2.4"></span> 
-   **Lecture: videolectures.net: Olivier Bousquet’s “Introduction to
    Learning Theory: Part 1”**
    Link: videolectures.net: Olivier Bousquet’s “[Introduction to
    Learning Theory; part
    1](http://videolectures.net/mlss06au_bousquet_ilt/)” (Adobe Flash
    and Windows Media Player)  
        
     Instructions: Watch Olivier Bousquet’s “Part 1,” working through
    the provided on the right-hand side of the screen as you listen to
    his lecture.  After viewing the lecture, you should have a general
    understanding of “learning theory,” be able to differentiate between
    deduction and induction, and describe, in general terms, the concept
    of probability and Bayes' rule.  This lecture is about 1 hour long.
    You can also download the PowerPoint slides in a PDF format by
    clicking on the link under “See Also.”  
        
     About the link: Olivier Bousquet works at the Max Planck Institute
    for Biological Cybernetics.   
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial- NoDerivatives License
    3.0](http://creativecommons.org/licenses/by-nc-nd/3.0/)(HTML).  It
    is attributed to (Oliver Bousquet).

**1.2.5 Natural Language Processing** <span id="1.2.5"></span> 
**1.2.6 Motion and Manipulation** <span id="1.2.6"></span> 
**1.2.7 Perception** <span id="1.2.7"></span> 
**1.2.8 Social Intelligence** <span id="1.2.8"></span> 
**1.2.9 General Intelligence** <span id="1.2.9"></span> 
**1.3 Approaches to AI** <span id="1.3"></span> 
-   **Reading: Wikipedia’s “Artificial Intelligence: Approaches”**
    Link: Wikipedia’s“[Artificial Inelligence:
    Approaches](http://en.wikipedia.org/wiki/Artificial_intelligence#Approaches)”
    (HTML)  
        
     Instructions: Read this entry on the different paradigms that guide
    AI research and make sure you know the differences between them. 
    This link covers subsections 1.3.1-1.3.4.  
        
     About the link: The article above is an entry from
    en.wikipedia.org, which is a web-based, free-content encyclopedia
    project based on an openly editable model.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/)(HTML).  This
    article is a modified version of an article of the same title
    originally found on Wikipedia.  The Saylor Foundation has
    reformatted the entry and has omitted several of the original
    sections.You can find the original Wikipedia version of this article
    [here](http://en.wikipedia.org/wiki/Artificial_intelligence#Approaches)(HTML).  

      
     

**1.3.1 Cybernetics and Brain Simulation** <span id="1.3.1"></span> 
**1.3.2 Symbolic AI** <span id="1.3.2"></span> 
**1.3.3 Sub-symbolic AI** <span id="1.3.3"></span> 
**1.3.4 Statistical** <span id="1.3.4"></span> 
**1.3.5 Systems with General Intelligence** <span id="1.3.5"></span> 
-   **Lecture: videolectures.net: Michael Thielscher’s "Systems with
    General Intelligence"**
    Link: videolectures.net: Michael Thielscher’s "[Systems with General
    Intelligence](http://videolectures.net/aaai2010_thielscher_sgi/)"
    (Adobe Flash and Windows Media Player)  
        
     Instructions: Watch this video about general problems in AI,
    working through slides provided on the right-hand side of the screen
    as Thielscher lectures.  After watching the video, you should be
    familiar with the chess-as-an-intelligent-system example, understand
    what general game playing is about, and identify the major questions
    with which general AI is concerned.  Do not let yourself get bogged
    down by the details; work for a general understanding of AI.  This
    lecture is 53 minutes long. You can also download the PowerPoint
    slides in a PDF format by clicking on the link under “See Also.”  
        
     About the link: In this video, Michael Thielscher of the School of
    Computer Science and Engineering, University of New South Wales, 
    talks about general intelligence and AI problems, approaches, and
    history.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-NonCommercial- NoDerivatives License
    3.0](http://creativecommons.org/licenses/by-nc-nd/3.0/)(HTML).  It
    is attributed to (Michael Thielscher).

**1.4 Agents in Code** <span id="1.4"></span> 
-   **Assignment: National Taiwan Normal University: Department of
    Computer Science and Information Engineering: Tsung-Che Chiang’s
    “Vacuum Cleaner World”**
     Link: National Taiwan Normal University: Department of Computer
    Science and Information Engineering: Tsung-Che Chiang’s “[Vacuum
    Cleaner
    World](http://web.ntnu.edu.tw/%7Etcchiang/ai/Vacuum%20Cleaner%20World.htm)”
    (HTML)  
        
      Instructions: Please read through the webpage and follow the
    instructions to complete the activity.  
        
      Terms of Use: Please respect the copyright and terms of use
    displayed on the web page above.


