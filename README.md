# cs342-assignment-1--bank-algorithms-solved
**TO GET THIS SOLUTION VISIT:** [CS342 Assignment 1 -Bank Algorithms Solved](https://www.ankitcodinghub.com/product/cs342-assignment-1-bank-algorithms-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91958&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS342 Assignment 1 -Bank Algorithms Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
It is needed to be familiar with the Deadlock problem and how to solve it. Therefore, it is required to apply the deadlock avoidance algorithms by applying the Banker’s algorithm. You will write a Java code that implements the banker’s algorithm: processes request and release resources and the banker will grant a request only if it leaves the system in a safe state. A request is denied if it leaves the system in an unsafe state.

The bank will employ the strategy outlined in the textbook &amp; lectures whereby it will consider requests from n processes for m resources. The bank will keep track of the resources using the following data structures:

</div>
</div>
<div class="layoutArea">
<div class="column">
int [] available;

int [][] maximum;

int [][] allocation; int [][] need;

</div>
<div class="column">
//the available amount of each resource //the maximum demand of each process

//the amount currently allocated to each process //the remaining needs of each process

</div>
</div>
<div class="layoutArea">
<div class="column">
You should build a test program to test your code. The test program should take the initial number of the available resources at the bank, the maximum need, and the actually allocated resources for each process. Your program should calculate the need matrix as well as the new available vector.

Output:

The output screen must appear every action happened as well as the current state for the bank by showing the values for your data structures as well as the process requests and releasing for the resources. The bank decisions to either deny or approve the requests must be shown through the output screen.

After the testing the user can type:

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ul>
<li>– &nbsp;RQ &lt;process#&gt; &lt;r1&gt; &lt;r2&gt; &lt;r3&gt;: It means that process request resources. So add this request to the needed resources for the given process and check again if the system is in a safe state.</li>
<li>– &nbsp;RL &lt;process#&gt; &lt;r1&gt; &lt;r2&gt; &lt;r3&gt;: It means that process release resources. So check if release resources are less than or equal to allocated resources and if so, then subtract this release resources from allocated resources for a given process.</li>
<li>– &nbsp;Recover: if a request let to a Deadlock, apply recovery algorithm (choose a victim , force it to release resources and check again if the system is in a safe state, if still in an unsafe state then will choose a victim again force it to release and check again and keep repeating until it reaches a safe state).
Mention based on what did you choose your victim (i.e. priority, how much longer to complete, resources used, resources needed …etc.).
</li>
<li>– &nbsp;Quit: it closes the application</li>
</ul>
</div>
</div>
</div>
