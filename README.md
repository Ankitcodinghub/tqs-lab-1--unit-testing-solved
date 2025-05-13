# tqs-lab-1--unit-testing-solved
**TO GET THIS SOLUTION VISIT:** [TQS Lab 1- Unit testing Solved](https://www.ankitcodinghub.com/product/tqs-lab-1-unit-testing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93881&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;TQS Lab 1- Unit testing Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Lab 1

</div>
<div class="column">
Maven configured to run in the command line. Check with: $ mvn –version

Java capable IDE, such as IntelliJ IDEA (version “Ultimate” suggested) or VS Code. Unit testing (with JUnit 5)

</div>
</div>
<div class="layoutArea">
<div class="column">
Learning objectives

<ul>
<li>⎯ &nbsp;Identify relevant unit tests to verify the contract of a module.</li>
<li>⎯ &nbsp;Write and execute unit tests using the JUnit framework.</li>
<li>⎯ &nbsp;Link the unit tests results with further analysis tools (e.g.: code coverage)
Key points
</li>
</ul>
<ul>
<li>● &nbsp;Unit testing is when you (as a programmer) write test code to verify units of (production) code. A unit is a small, coherent subset of a much larger solution. A true “unit” should not depend of the behavior of other (collaborating) modules.</li>
<li>● &nbsp;Unit tests help the developers to (i) understand the module contract (what to construct); (ii) document the intended use of a component; (iii) prevent regression errors; (iv) increase confidence in the code.</li>
<li>● &nbsp;JUnit and TestNG are popular frameworks for unit testing in Java.</li>
</ul>
1.1 Stack contract

In this exercise, you will implement a stack data structure (TqsStack) with appropriate unit tests. Be sure to adopt a write-the-tests-first workflow:

a) Create a new project (maven-based, Java standard application). You may need to update the Java version in the POM.xml:

<pre>         &lt;properties&gt;
             &lt;project.build.sourceEncoding&gt;UTF-8&lt;/project.build.sourceEncoding&gt;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
2 | TQS LABS

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
45426 Teste e Qualidade de Software

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>        &lt;maven.compiler.source&gt;11&lt;/maven.compiler.source&gt;
</pre>
<pre>        &lt;maven.compiler.target&gt;${maven.compiler.source}&lt;/maven.compiler.target&gt;
    &lt;/properties&gt;
</pre>
<ol start="2">
<li>b) &nbsp;Add the required dependencies to run Junit 5 tests1. Here are some sources:
<ul>
<li>– &nbsp;Adapt from the quick start project for Maven2.</li>
<li>– &nbsp;Adapt from this tutorial.</li>
</ul>
</li>
<li>c) &nbsp;Create the required class definition (just the “skeleton”, do not implement the methods body yet; you may need to add dummy return values). The code should compile, but the implementation is yet incomplete.</li>
<li>d) &nbsp;Write the unit tests that will verify the TqsStack contract.

You may use the IDE features to generate the testing class; note that the IDE support will vary. Be

sure to use JUnit 5.x.

Your tests will verify several assertions that should evaluate to true for the test to pass.
</li>
<li>e) &nbsp;Run the tests and prove that TqsStack implementation is not valid yet (the tests should fail for now,
the first step in Red-Green-Refactor).
</li>
<li>f) &nbsp;Correct/add the missing implementation to the TqsStack;</li>
<li>g) &nbsp;Run the unit tests.</li>
<li>h) &nbsp;Iterate from steps d) to f) and confirm that all tests pass.</li>
</ol>
Suggested stack contract:

<ul>
<li>⎯ &nbsp;push(x): add an item on the top</li>
<li>⎯ &nbsp;pop: remove the item at the top</li>
<li>⎯ &nbsp;peek: return the item at the top (without removing it)</li>
<li>⎯ &nbsp;size: return the number of items in the stack</li>
<li>⎯ &nbsp;isEmpty: return whether the stack has no items
What to test3:
</li>
</ul>
<ol>
<li>a) &nbsp;A stack is empty on construction.</li>
<li>b) &nbsp;A stack has size 0 on construction.</li>
<li>c) &nbsp;After n pushes to an empty stack, n &gt; 0, the stack is not empty and its size is n</li>
<li>d) &nbsp;If one pushes x then pops, the value popped is x.</li>
<li>e) &nbsp;If one pushes x then peeks, the value returned is x, but the size stays the same</li>
<li>f) &nbsp;If the size is n, then after n pops, the stack is empty and has a size 0</li>
<li>g) &nbsp;Popping from an empty stack does throw a NoSuchElementException [You should test for the Exception occurrence]</li>
<li>h) &nbsp;Peeking into an empty stack does throw a NoSuchElementException</li>
<li>i) &nbsp;For bounded stacks only: pushing onto a full stack does throw an IllegalStateException</li>
</ol>
1 If using IntelliJ: you may skip this step and ask, later, the IDE to fix JUnit imports.

2 Delete the “pom-SNAPSHOT.xml”, if you are cloning the project to use as a quick starter. 3 Adapted from http://cs.lmu.edu/~ray/notes/stacks/

</div>
</div>
<div class="layoutArea">
<div class="column">
TQS LABS | 3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
1.2 EuroMillions

Let us consider the “Euromilhões” use case.

2a/ Pull the “euromillions-play” project and correct the code (or the tests themselves, if needed) to have the existing unit tests passing.

</div>
</div>
<div class="layoutArea">
<div class="column">
For the (failing) test:

testFormat

testConstructorFromBadArr ays

</div>
<div class="column">
You should:

Correct the implementation of Dip#format so the tests pass.

Implement new test logic to confirm that an exception will be raised if the arrays have invalid numbers (wrong count of numbers or stars)

</div>
</div>
<div class="layoutArea">
<div class="column">
Note: you may suspend temporary a test with the @Disabled tag (useful while debugging the tests themselves).

</div>
</div>
<div class="layoutArea">
<div class="column">
2b/ The sample project was prepared for the scenario in which the range for the “stars” was 1..10. However, the rules have changed, and the range is 1..12.

Be sure to include a test to verify the [new] ranges.

2c/ Note that the code provided includes “magic numbers” (2 for the number of stars, 50 for the max range in numbers, [was] 10 for the max range in starts…). Refactor the code to extract constants and eliminate the “magic numbers”.

2d/ The class SetOfNaturals represents a set (no duplicates should be allowed) of integers, in the range [1, +∞]. Some basic operations are available (add element, find the intersection…).

</div>
</div>
<div class="layoutArea">
<div class="column">
4 | TQS LABS

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
45426 Teste e Qualidade de Software

</div>
</div>
<div class="layoutArea">
<div class="column">
What kind of unit test are worth writing for the entity SetOfNaturals? Complete the project, adding the new tests you identified.

2e/ Assess the coverage level in project “Euromillions-play”.

Configure the maven project to run Jacoco analysis.

Run the maven “test” goal and then “jacoco:report” goal. You should get an HTML report under target/jacoco.

$ mvn clean test jacoco:report

Interpret the results accordingly. Which classes/methods offer less coverage? Are all possible decision branches being covered?

Note: IntelliJ has an integrated option to run the tests with the coverage checks (without setting the Jacoco plugin in POM). But if you do it at Maven level, you can use this feature in multiple tools.

Troubleshooting some frequent errors

➔ “Test are run from the IDE but not from command line.”

Be sure to configure the Surefire plug-in in Maven (example).

Explore

● JetBrains Blog on Writing JUnit 5 tests (with vídeo).

● Book: JUnit in Action. Note that you can access it from the OReilly on-line library.

● JUnit 5 cheat sheet.

● Vogel’s tutorial on JUnit. Useful to compare between JUnit 4 and JUnit 5.

</div>
</div>
</div>
