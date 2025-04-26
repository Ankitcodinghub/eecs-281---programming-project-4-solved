# eecs-281---programming-project-4-solved
**TO GET THIS SOLUTION VISIT:** [EECS 281 – Programming Project 4 Solved](https://www.ankitcodinghub.com/product/eecs-281-programming-project-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;76498&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EECS 281 –  Programming Project 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
<strong>Among Us </strong>

<h1>Overview</h1>
You are playing the popular multiplayer murder mystery game <a href="http://www.innersloth.com/gameAmongUs.php"><em>Among U</em></a>​&nbsp;&nbsp;&nbsp;&nbsp; <a href="http://www.innersloth.com/gameAmongUs.php"><em>s</em></a><sup>1</sup>, in which there are one or more impostors among a group of crewmates on a spaceship. The impostors’ goal is to sabotage the spaceship by killing all their crewmates before the crew finishes their tasks; the crewmates win by either completing their tasks or ejecting the impostors out of the spaceship before they can kill everyone. Impostors have access to an underground vent network that allows them to quickly move across the spaceship without detection. If a crewmate dies, they become a “ghost”; ghosts can still complete their tasks, and they can travel without restriction throughout the map. In this project, you will be playing the roles of both an Impostor (Part A) and a ghost Crewmate (Parts B and C) to identify efficient routes through the spaceship that will help you win the game.

&nbsp;

In Impostor mode (Part A), you’ll be setting up the vent network to travel quickly between rooms. You need to make sure that you can access any room from any other room. However, excavating is expensive, so you also want to minimize the total distance of the network.

&nbsp;

In Ghost mode (Parts B and C), you can move freely across the map, and you want to finish your tasks as quickly as possible to win. You can fly through walls, and you want to find the optimal path to finish all your tasks and end at the first task you did. You may assume that there is one task per room to be completed.

&nbsp;

<strong>To be clear: these scenarios are separate; the program will create a plan for one or the other, but not both in the same run (though you may find that algorithms from one mode help with another mode). </strong>

&nbsp;

<strong>In this project, your output does not need to be exactly the same as ours to be correct. As long as it provides a valid answer, and follows the rules for formatting output, it can be in a different order and still be correct. </strong>

&nbsp;

<h1>Project Goals</h1>
<ul>
<li>Understand and implement MST algorithms. Be able to determine whether Prim’s or Kruskal’s is more efficient for a particular scenario.</li>
<li>Understand and implement a Branch and Bound algorithm. Develop a fast and effective bounding algorithm.</li>
<li>Explore various heuristic approaches to achieving a nearly-optimal solution as fast as possible. ○ Do some web searching for “TSP heuristics”, don’t choose one worse than O(n​<sup>2</sup><sup>​</sup>).</li>
<li>Use a visualization tool to help with debugging.</li>
</ul>
&nbsp;

<sup>1</sup>

<h1>Map Input</h1>
On startup, your program, amongus​ ,​ reads input from standard input (cin) describing the locations of the rooms. The map is a grid with the decontamination zone on the bottom left quadrant (see ‘Path Rules’). You will be given a list of M rooms with associated integer coordinates (x, y). Rooms are identified by integer indices which correspond to the order in which they are read in (the first room location corresponds to location 0, the second room location to location 1, etc.). For parts B and C you always start in the 0th room.

&nbsp;

Formally, the input will be formatted in this manner: The first line will contain a single number denoting the number of rooms on the map. That will be followed by a list of integer x/y, coordinates in the form: x​ y.​ You may assume that the input will always be well-formed (it will always conform to this format and you do not need to error check). There may be additional blank lines at the end of the file (but nowhere else).

&nbsp;

Sample:

5

6 1

2 3

-5 -4

-1 6

0 -1

&nbsp;

The above sample can be visualized as in the figure below, where the numbers shown are the room indices that starts at the 0-th room, and the blue line indicates the decontamination border (for more details, see the ‘Path Rules’ section) which separates the outer area from the lab: room 2 is in the lab, 4 is in decontamination, and the rest are in the outer area.

&nbsp;

&nbsp;

&nbsp;

<strong>There is more than one way to represent this configuration internally in your program, and this will affect your runtime. Choose your data structures wisely! </strong>

<strong>&nbsp;</strong>

<strong>For Part A, there will always be at least two points.&nbsp; For Parts B and C, there will always be at least 3. </strong>

&nbsp;

<h1>Path Rules</h1>
&nbsp;

<h2>Distance</h2>
2

We represent the paths you take as a set of pairs of points or as a sequence of points. Your calculations should use <a href="https://en.wikipedia.org/wiki/Euclidean_distance"><strong>Euclidean distanc</strong></a>​ <a href="https://en.wikipedia.org/wiki/Euclidean_distance"><strong>e</strong></a><a href="https://en.wikipedia.org/wiki/Euclidean_distance">,</a><u>​</u> and you should represent your distances as doubles.

&nbsp;

To connect rooms in Part A, you must only move between rooms in the same area. In order to reach rooms in the lab from the outer area (or vice-versa), you must first pass through a decontamination room.

&nbsp;

In Parts B and C, you are now a ghost (a minor inconvenience), and can fly directly from room to room. You move along the line segments that connect rooms. <em>Please</em>​<em> be very careful with rounding errors in your distance calculations; the autograder will allow you a 0.01 margin of error to account for rounding, but you should avoid rounding at intermediate steps. </em>

&nbsp;

<h2>The Lab</h2>
There is a lab that is located in the <strong>bottom left quadrant</strong>​&nbsp;&nbsp;&nbsp;&nbsp; of the map. When first embarking on your journey (in​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Part A), you can travel using vents between different locations in the outer area. The lab is only accessible through <strong>decontamination</strong>​&nbsp;&nbsp;&nbsp;&nbsp; , which consists of the negative portions of the x and y axes, including the origin (0,​ 0).&nbsp; In Part A, you may only enter and exit the lab by passing through a location in decontamination.&nbsp; For example, you are not allowed to travel directly from (-5, -4) to (6, 1).&nbsp; You must first travel from (-5, -4) to (0, -1), and then from (0, -1) to (6, 1).

<strong>&nbsp;</strong>

<strong>For the sake of simplicity, assume two outer area locations that “cross” the lab can be connected by a direct path. The example below shows two validly connected outer area rooms, at locations A and B. </strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>In this example, there is a direct path from A to B, by using vents. </strong>

&nbsp;

When you are a ghost (in Parts B and C), you can fly directly from locations in the lab to locations in the outer area, and vice versa; in other words, you may ignore decontamination.

<sup>2</sup> “Path,” in this project, can be understood as a route between two locations.​

&nbsp;

<h2>Other</h2>
Important: For parts B and C, you always start at the 0-th room location.

&nbsp;

You are also <strong>not</strong>​ allowed to ‘wrap around the edges of the world’ (you <strong>cannot</strong>​ go above the top of the map to arrive at the bottom).

<strong>&nbsp;</strong>

<h1>Command Line Input</h1>
Your program, amongus,​ should take the following case-sensitive command line options:​

&nbsp;

<ul>
<li>-m, –mode &lt;MODE&gt;</li>
</ul>
This command line option must be specified, if it is not, print a useful error message to standard error

(cerr) and exit(1). MODE​ is a required argument. Set the program mode to MODE​ .​ MODE​ must be one of MST,​ FASTTSP​ ,​ or OPTTSP​ .​ The MODE​ corresponds to the algorithm amongus​ ​runs (and therefore what it outputs).

<ul>
<li>-h, –help</li>
</ul>
Print a short description of this program and its arguments and exit(0).

&nbsp;

Valid examples of how to execute the program:

./amongus –mode MST &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (OK, but you must type the input by hand)

./amongus -h &lt; inputFile.txt &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (OK, -h happens before we realize there’s no -m)

./amongus -m OPTTSP &lt; inputFile.txt (OK, reads from a file on disk)

./amongus -m BLAH &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (BAD mode following -m)

&nbsp;

Remember that when we redirect input, it does not affect the command line. Redirecting input just sends the file contents to cin. You should not have to modify your code to allow this to work; the operating system will handle it.

&nbsp;

<strong>We will not be specifically error-checking your command-line handling, however we expect that your program conforms with the default behavior of </strong><strong>getopt_long()</strong>​ <strong>.</strong>​<strong> Incorrect command-line handling may lead to a variety of difficult-to-diagnose problems.</strong>

<strong>&nbsp;</strong>

<h1>Algorithms</h1>
Your program should run <strong>one</strong>​<strong> and only one</strong> of the following modes at runtime depending on the mode​ option for that particular program call. We divide it into ‘parts’ for your convenience, though <em>you</em>​<em> may find that elements and algorithms of some parts can help with others</em>​.

&nbsp;

<h2>Part A – MST mode</h2>
&nbsp;

<h3>Description</h3>
This mode will devise a vent system that connects every room location while minimizing the total distance of vents needed.

&nbsp;

When the program is run in the MST​ mode, it should calculate and print out an MST connecting all of the room locations. You may use any MST algorithm to connect all the locations. <em>Hint</em>​ ​: Unless you want to implement both and compare, think about the nature of the graph (how many vertices and edges does it have?). You are free to adapt code from the lecture slides to fit this project, but you will want to carefully think about the data structures <em>necessary</em>​ to do each part (storing unnecessary data can go over memory limits). Your program must always generate one valid MST for each input.

&nbsp;

Remember that in this part, you must respect the boundary between the lab and the outer area. . Your MST cannot connect a room in the lab to one in the outer area, without passing through a room in decontamination.

&nbsp;

<h3>Output Format (for Part A only)</h3>
For the MST​ mode, you should print the total weight of the MST you generate by itself on a line; this weight is the sum of the weights of all edges in your MST (in terms of Euclidean distance). You should then print all edges in the MST. All output should be printed to standard output (cout).

&nbsp;

The output should be of the format: weight node node node node

……

&nbsp;

The nodes are the room location numbers corresponding to the vertices of the MST and a pair of nodes on a given line of the output describes an edge in the MST from the first node to the second. To be clear, the weight should be formatted as a double (2​ decimal point precision is enough – see Appendix A),​ and the node numbers should all be integer values when printed. For example, given the example input file above, your MST mode output might be:

&nbsp;

19.02

0 1

2 4

1 3

1 4

&nbsp;

You should also always print the pairs of vertices that describe an edge such that the index on the left has a smaller integer value than the index on the right. In other words:

<ul>
<li>2</li>
</ul>
is a possible valid edge of output, but

<ul>
<li>1</li>
</ul>
is not.

&nbsp;

<strong>If it is not possible to construct an MST</strong> for the rooms (i.e. if there are rooms in both the outer area and in the lab, with no decontamination rooms), your program should print the message “Cannot​ construct MST” to cerr​ and ​ exit(1)​ .​

&nbsp;

&nbsp;

&nbsp;

<h2>Parts B &amp; C (FASTTSP &amp; OPTTSP mode)</h2>
&nbsp;

<h3>Description (for both Parts B and C)</h3>
In this mode, you will figure out how to travel to every room and then return to your starting location. The route will always start at room index 0, visit every other room exactly once, and return to the starting point. Your job will thus be to solve the TSP (Traveling Salesperson Problem) and choose paths to room locations so as to minimize the total distance travelled. Euclidean (straight-line) distance is used here again to compute distances between rooms. Because you are now a ghost, you no longer have to worry about decontaminating; you can go from any room to any other.

&nbsp;

For FASTTSP mode, you do <strong>not</strong>​ need to produce an optimal TSP tour, but your solution should be close to optimal. Because your FASTTSP algorithm does not need to be perfectly optimal, we expect it to run much faster than finding a perfect optimal solution. Do some online searching for “TSP heuristics”. There are several types, some easier to implement, some with better path lengths, some both.

&nbsp;

For OPTTSP mode, you must find an <strong>optimal</strong>​ solution to the TSP (the actual minimum Euclidean distance necessary). More on the differences between OPTTSP and FASTTSP modes will be discussed later.

&nbsp;

For <strong>both</strong>​ methods:​

&nbsp;

You must start the tour from the 0-th room location (your starting location).

&nbsp;

You must visit every room exactly once (there’s no point in returning to a place already checked), and at the end of the tour, you <strong>must return back to the 0-th location</strong>​ .​

&nbsp;

The length of a tour is defined as the sum of all pairwise distances travelled – that is, the sum of the lengths of all paths taken (using Euclidean distance).

&nbsp;

Your program must print the indices of the locations in an order such that the length of this tour is as small as possible. More details about how to accomplish this are listed below.

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<h3>Output Format (for both Parts B and C)</h3>
You should begin your output by printing the overall length of your tour on a line. On the next line, output the nodes in the order in which you visit them. The initial node should be the starting location index and the last node should be the location number directly before returning back to the 0-th location. The nodes in your tour should be printed such that they are separated by a single space. There can be a space after the last location listed. All output should be printed to standard output (cout​ ).​

&nbsp;

For example, if given the input file above, your program could produce:

&nbsp;

31.64

0 4 2 3 1

&nbsp;

or

&nbsp;

31.64

0 1 3 2 4

&nbsp;

<h3>Part B Only Description</h3>
In the case where we have a large number of possible rooms to visit, finding an optimal method for visiting all of them may be too slow, and you may grow old and die before completing your task. You can use <em>heuristics</em>​ instead to find nearly-optimal tours. A heuristic is a problem-solving method (an algorithm) that can produce a good answer that is not necessarily the best answer. For example, you can skip a branch speculatively rather than waiting to know for a fact that it can be skipped. There are many other simple heuristic techniques, such as starting with a random tour and trying to improve it by small changes.

&nbsp;

You should be able to produce a solution to the Traveling Salesperson Problem (TSP) that is as close as possible to the optimal tour length <strong>(</strong>​ <strong>though it does not need to be optimal)</strong>.​ In the best case, your produced tour length will equal the optimal tour length.

&nbsp;

You are allowed to use any combination of algorithms for this section that we have covered in class, including the MST algorithm you wrote for Part A.

&nbsp;

You will need to be creative when designing your algorithms for this section. You are free to implement any other algorithm you choose, so long as it meets the time and memory constraints. <strong>However</strong>​ ,​ you should not use any advanced algorithms or formulas (such as Simulated Annealing, Genetic Algorithms and Tabu search – they are too slow) that are significantly different from what has been covered in class. Instead, creatively combine the algorithms that you already know and come up with concise optimizations. Your heuristic will very likely be greedy in some way, but there are different ways to be greedy!

&nbsp;

<h3>Part C Only Description</h3>
To find an optimal tour, you could start with the brute force method of exhaustive enumeration that evaluates every tour and picks a smallest tour. By structuring this enumeration in a clever way, you could determine that some branches of the search cannot lead to optimal solutions. For example, you could compute <em>lower</em>​<em> bounds</em> on the length of any full tour that can be found in a given branch. If such a lower bound exceeds the cost of a full solution you have found previously, you can skip this branch as hopeless. If implemented correctly, such a <strong>branch-and-bound</strong> method should <strong>always</strong>​ produce an optimal solution. It will not scale as well as sorting or searching algorithms do for other problems, but it should be usable with a small number of locations. Clever optimizations (identifying hopeless branches of search early) can make your algorithm <em>a</em>​<em> hundred times</em> faster. Drawing TSP tours on paper and solving small location configurations to optimality by hand should be very useful. <strong>Remember</strong>​<strong> that there is a tradeoff between the time it takes to run your bounding function and the number of branches that bound lets you prune. </strong>

<strong>&nbsp;</strong>

<strong>MAKE SURE that you use the version of </strong><strong>genPerms()</strong>​<strong> presented in either the “Project 4 Tutorial” or the “Backtracking BB TSP” lecture slides. The one presented earlier in the semester, in the “Stacks and Queues” lecture slides is much slower. </strong>

&nbsp;

Given an input set of <em>N</em>​ locations defined by integer coordinates, your job is to produce an optimal tour using branch-and-bound algorithms. Your program should <strong>always</strong>​ produce the shortest possible tour as a solution, even if computing that solution is time-consuming. You will be given a 35-second cpu time limit to generate your solution. If your program does not produce a valid solution, it will fail the test case. Your solution will also be judged by time and space budgets as per previous projects.

<strong>&nbsp;</strong>

<h1>Libraries and Restrictions</h1>
We highly encourage the use of the STL for this project, with the exception of several prohibited features. Do not use:

<ul>
<li>The C++11 regular expressions library</li>
<li>The STL thread/atomics libraries (which spoil runtime measurements) ● Shared or unique pointers.</li>
<li>Other libraries (e.g., boost, pthreads, etc).</li>
</ul>
<h1>Testing and Debugging</h1>
Part of this project is to prepare several test files that will expose defects in buggy solutions – your own or someone else’s. As this should be useful for testing and debugging your programs, we recommend that you <strong>first </strong>try​ to catch a few of our intentionally-buggy solutions with your test files, before completing your solution. The autograder will also tell you if one of your own test files exposes bugs in your solution.

Each test that you submit should consist of an input file. When we run your test files on one of intentionally-buggy project solutions, we compare the output to that of a correct project solution. If the outputs differ, the test file is said to expose that bug.

&nbsp;

Test files should be named test-n-MODE.txt​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; where 1 &lt;= n &lt;= 10. The autograder’s buggy solutions will run your test files in the specified MODE​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .&nbsp; The mode must be ​&nbsp; MST​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; , ​ FASTTSP​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; , or ​ OPTTSP​&nbsp;&nbsp;&nbsp; .​

&nbsp;

Your test files may have no more than 10 coordinates in any one file. You may submit up to 10 test files

(though it is possible to get full credit with fewer test files). The tests the autograder runs on your solution are <strong>NOT</strong> limited to 10 coordinates in a file; your solution should not impose any size limits (as long as sufficient system memory is available).

<h1>Submitting to the Autograder</h1>
Do all of your work (with all needed source code files, as well as test files) in some directory other than your home directory. This will be your “submit directory”. Before you turn in your code, be sure that:

<ul>
<li>Every source code and header file contains the following project identifier in a comment at the top of the file:</li>
<li>// Project Identifier: 9​ B734EC0C043C5A836EA0EBE4BEFEA164490B2C7</li>
<li>The Makefile​ must also have this identifier (in the first TODO block)​</li>
<li>You have deleted all .o files and your executable(s). Typing ‘make clean​ ’ shall accomplish this.​</li>
<li>Your makefile is called Makefile​ .​ Typing ‘make​ -R -r​’ builds your code without errors and generates an executable file called amongus​ .​ The command-line options -R and -r disable automatic build rules, which will not work on the autograder.</li>
<li>Your Makefile​ specifies that you are compiling with the gcc optimization option -​ O3.​ This is extremely important for getting all of the performance points, as -​ O3 can speed up code by an order of magnitude.</li>
<li>Your test files are named test-n-MODE.txt​ and no other project file names begin with test. Up to 10 test files may be submitted.&nbsp; The “mode” portion of the filename must be MST​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; , ​ OPTTSP​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; or ​ FASTTSP​&nbsp;&nbsp; .​&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The total size of your program and test files does not exceed 2MB.</li>
<li>You don’t have any unnecessary files (including temporary files created by your text editor and compiler, etc) or subdirectories in your submit directory (i.e. the .git folder used by git source code management).</li>
<li>Your code compiles and runs correctly using version 6.2.0 of the g++ compiler. This is available on the CAEN Linux systems (that you can access via login.engin.umich.edu). Even if everything seems to work on another operating system or with different versions of GCC, the course staff will not support anything other than GCC 6.2.0 running on Linux (students using other compilers and OS did observe incompatibilities). To compile with g++ version 6.2.0 on CAEN you <strong>must</strong>​ put the following at the top of your Makefile​ :​</li>
</ul>
&nbsp;

PATH := /usr/um/gcc-6.2.0/bin:$(PATH)

LD_LIBRARY_PATH := /usr/um/gcc-6.2.0/lib64

LD_RUN_PATH := /usr/um/gcc-6.2.0/lib64

&nbsp;

Turn in all of the following files:

<ul>
<li>All your .h and/or .cpp files for the project</li>
<li>Your Makefile​</li>
<li>Your test files</li>
</ul>
&nbsp;

You must prepare a compressed tar archive (.tar.gz file) of all of your files to submit to the autograder. One way to do this is to have all of your files for submission (and nothing else) in one directory. In this directory, run

dos2unix *; tar czvf ./submit.tar.gz *.cpp *.h* Makefile test-*.txt

This will prepare a suitable file in your working directory. If you’re using our Makefile​ ,​ use the command make fullsubmit.​

&nbsp;

Submit your project files directly to either of the two autograders at:

<a href="https://g281-1.eecs.umich.edu/">https://g281-1.eecs.umich.edu/</a> or <a href="https://g281-2.eecs.umich.edu/">https://g281-2.eecs.umich.edu/</a><a href="https://g281-2.eecs.umich.edu/">.</a><u>​</u> <strong>When</strong>​<strong> the autograders are turned on and accepting submissions, there will be an announcement on Piazza.</strong> The autograders are identical and your daily submission limit will be shared (and kept track of) between them. You may submit up to four times per calendar day (more during the Spring). For this purpose, days begin and end at midnight (Ann Arbor local time). <strong>We</strong>​<strong> will count only your best submission for your grade</strong>​. If you would instead like us to use your

LAST submission, see the autograder FAQ page, or <a href="https://docs.google.com/forms/d/e/1FAIpQLSe8BxRNnZKgRI4o-V7eG5F6LY_GhhWjMyJW8yKcP4XKVm2JrQ/viewform?usp=sf_link">use this for</a><u>​ </u><a href="https://docs.google.com/forms/d/e/1FAIpQLSe8BxRNnZKgRI4o-V7eG5F6LY_GhhWjMyJW8yKcP4XKVm2JrQ/viewform?usp=sf_link">m</a>.​

&nbsp;

<strong>Please make sure that you read all messages shown at the top section of your autograder results! These messages often help explain some of the issues you are having (such as losing points for having a bad </strong><strong>Makefile</strong>​<strong> or why you are segfaulting). Also be sure to check if the autograder shows that one of your own test files exposes a bug in your solution (at the bottom). Search the autograder results for the word “Hint” (without quote marks) for potentially useful information.</strong>

&nbsp;

<h1>Grading</h1>
80 points — Your grade will be derived from correctness and performance (runtime). This will be determined by the autograder. On this project we expect a much broader spread of runtimes than on previous projects. As with all projects, the test cases used for the final grading are likely to be different.

&nbsp;

10 points — Your program does not leak memory.&nbsp; Make sure to run your code under valgrind before each submit.&nbsp; This is also a good idea because it will let you know if you have undefined behavior (such as reading an uninitialized variable), which may cause your code to crash on the autograder.

10 points — Student test file coverage (effectiveness at exposing buggy solutions).

&nbsp;

<strong>We also reserve the right to deduct up to 5 points for bad programming style, code that is unnecessarily duplicated, etc.</strong>

&nbsp;

&nbsp;

<h2>Runtime Quality Tradeoffs</h2>
In this project there is no single correct answer (unlike previous projects). Accordingly, the grading of your problem will not be as simple as a ‘diff’, but will instead be a result of evaluating your output. For example, if we gave you a square for Part A, you might choose any 3 of the 4 edges, and print them in any order, meaning there are 24 possible correct output files!

&nbsp;

Particularly for Part B, we expect to see greater variation in student output. Part B asks you to solve a hard problem, and with the given time constraints, we don’t actually expect your output to be optimal for all cases. The quality of your solutions may even vary from case to case. We want you to quickly produce solutions that are close to optimal. This inevitably creates tradeoffs between solution optimality and runtime.

&nbsp;

You may find it useful to implement more than one algorithm or heuristic that you use in Part B, and do some testing plus use the autograder to determine which works the best..

&nbsp;

<strong>Your grade for Part B will be determined based on how close you are to the best solution, computed as a percentage. </strong>

&nbsp;

&nbsp;

<h1>Hints and Advice</h1>
There’s a project tutorial video available: <a href="https://youtu.be/hdTrbU28pnk">https://youtu.be/hdTrbU28pn</a>​ <a href="https://youtu.be/hdTrbU28pnk">k</a>

&nbsp;

It will be difficult to get this project correct without visualizing your MSTs and TSP tours. We​ have provided a visualization tool on the Autograder that you can use; follow this link: https://g281-2.eecs.umich.edu/p4viz/​ .​

&nbsp;

Running your code (on CAEN or locally) using valgrind​ can help you find and remove undefined (buggy) behavior and memory leaks from your code. This can save you from losing points in the final run when you mistakenly believe your code to be correct.

&nbsp;

It is extremely helpful to compile your code with the following gcc options: -​ Wall -Wextra -Wvla -Wconversion -pedantic.​ This way the compiler can warn you about poor style and parts of your code that may result in unintended/undefined behavior.

&nbsp;

Make sure that you are using getopt_long()​ for handling command-line options.​

&nbsp;

<h1>Appendix A</h1>
In order to ensure that your output is within the tolerable margins of error for the autograder to correctly grade your program you <strong>must</strong>​ run the following lines of code before you output anything to cout. We highly recommend that you simply put them at the top of main()​ so that you don’t forget about them.​

&nbsp;

cout &lt;&lt; std::setprecision(2); //Always show 2 decimal places cout &lt;&lt; std::fixed; //Disable scientific notation for large numbers

&nbsp;

You will need to #include​&nbsp;&nbsp;&nbsp;&nbsp; &lt;iomanip&gt; to use this code. ​<strong>If you use a stringstream for output</strong>,​ you should send these lines to your stringstream instead of cout.&nbsp; Don’t use a stringstream for output.

&nbsp;

&nbsp;

<h1>Appendix B</h1>
One possible heuristic (NOT the only one, NOT an easy one) is to construct a starting point for your TSP tour by following MST edges and skipping previously visited vertices. By using this technique correctly, you can find a tour that is guaranteed to be no more than twice the optimal solution’s length (and use this “2x” check for debugging). You can then use this starting point to make adjustments and do better. This is not necessarily the best approach! It is one approach used to illustrate how a heuristic can be used, there are better ones out there.&nbsp; This example method is VERY hard to code.&nbsp; Do some research on other heuristics!

&nbsp;

<h2>“Corner Cutting” algorithm illustrated</h2>
&nbsp;

Suppose locations are distributed in an input map as shown below:

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Below is an MST that would be formed from the above locations.

&nbsp;

&nbsp;

&nbsp;

Below is a path taken by strictly following the edges of the MST.

&nbsp;

&nbsp;

&nbsp;

However, by “cutting corners,” as described in the picture below, an effective TSP solution can be generated. This is possible because once a vertex is visited, it will not be visited again. In the above path that strictly follows the edges of the MST, the middle vertex is visited four times (visited after an outer vertex is visited). If the middle vertex is skipped after the first visit, a TSP tour shown below is achieved.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

The reason we bring up this ‘twice-around-the-tree’ heuristic is to state the theorem that the resulting tours are no worse than 2x the MST cost.

&nbsp;

The following is an explanation/proof sketch as to why the 2x bound is valid:

&nbsp;

If you perform a DFS traversal of a tree and return to the initial node, you have visited every edge exactly twice (“going in” and “returning”), so this gives you exactly double the cost/length of the MST (the fact that the tree is minimal is not important for the logic of the proof – this works for any tree). Since the tree is spanning, you have visited all locations. The only problem with this twice-around-the-tree self-intersecting path is that it’s not a tour. It can be turned into a tour by taking shortcuts (i.e., taking shortcuts is important not only to reduce the length).

&nbsp;

<strong>When considering other heuristics:</strong>

<ol>
<li>The theorem allows you to upper-bound the cost of optimal TSP tours based on MST length.</li>
<li>The theorem has a constructive proof – a heuristic that always produces TSP tours that satisfy this upper</li>
</ol>
3

bound .

&nbsp;

As a consequence, your heuristic should also satisfy the 2x upper bound; if not, you can just implement the twice-around-the-tree heuristic. However, we do not require this because there are much better heuristics – ones that are faster and produce better results.

&nbsp;

<h1>Appendix C</h1>
<strong>&nbsp;</strong>

<h2>Legend for test case names and autograder info</h2>
&nbsp;

Autograder test names are broken down by the mode used with each test:

&nbsp;

<ul>
<li>Name of test file starting with “<strong>A</strong>​ ”: these test files are used with the MST mode.​</li>
<li>Name of test file starting with “<strong>B</strong>​ ”: these test files are used with the FASTTSP mode.​</li>
<li>Name of test file starting with “<strong>C</strong>​ ”: these test files are used with the OPTTSP mode.​</li>
</ul>
&nbsp;

Test files that start with “<strong>C</strong>​ ”​ are much smaller in size than those that start with “<strong>A</strong>​ ”​ and “<strong>B</strong>​ ”.​ The number of rooms for such files is smaller than 40 as compared to tens of thousands of rooms for the others. The reason is that TSP is NP-complete and finding an optimal solution in a reasonable amount of time is only possible for small-sized problems.

&nbsp;

When you start submitting test files to the autograder, it will tell you (in the section called “Scoring student test files”) how many bugs exist, the number needed to start earning points, and the number needed for full points. It will also tell you how many are needed to start earning an extra submit/day!

<sup>3</sup> Such heuristics are also called approximation algorithms.
