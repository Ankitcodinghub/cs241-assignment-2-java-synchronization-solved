# cs241-assignment-2-java-synchronization-solved
**TO GET THIS SOLUTION VISIT:** [CS241 Assignment 2-Java Synchronization Solved](https://www.ankitcodinghub.com/product/cs241-assignment-2-java-synchronization-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91973&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS241 Assignment 2-Java Synchronization Solved&nbsp;&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Problem Definition

</div>
</div>
<div class="layoutArea">
<div class="column">
It is required to simulate a limited number of devices connected to a router’s Wi-Fi using Java threading and semaphore. Routers can be designed to limit the number of open connections. For example, a Router may wish to have only N connections at any point in time. As soon as N connections are made, the Router will not accept other incoming connections until an existing connection is released. Explain how semaphores can be used by a Router to limit the number of concurrent connections

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
The following rules should be applied:

➔ The Wi-Fi number of connected devices is initially empty.

➔ If a client is logged in (print a message that a client has logged in) and if it can be served ➔ (means that it can reach the internet), then the client should perform the following

activities:

◆ Connect

◆ Performonlineactivity

◆ Logout

➔ Note: these actions will be represented by printed messages, such that there is a

random

➔ waiting time between the printed messages when a client connects, do some online

➔ activities and logged out.

➔ If a client arrives and all connections are occupied, it must wait until one of the currently ➔ available clients finish his service and leave.

➔ After a client finishes his service, he leave and one of the waiting clients (if exist) will

➔ connect to the internet.

Solution Design

You program must contain the following classes:

1. Router Class: that contains a list of connections and methods to occupy a connection and release a connection.

2. Semaphore Class: as given the synchronization lab.

3. Device Class: represent different devices (threads) that can be connected to the router;

each device has its own name (i.e. C1) and type (i.e. mobile, pc, tablet…) and it may perform three activities: connect, perform online activity and disconnect/logout.

4. Network Class: this class contains the main method in which the user is asked for two

inputs:

<ul>
<li>● &nbsp;N: max number of connections a router can accept</li>
<li>● &nbsp;TC: total number of devices that wish to connect).</li>
<li>● &nbsp;TC lines that contain: name of each device, and its type</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Program Output

You will print the output logs in a file, which simulates the execution order of the devices threads and the printed messages of each device

NOTE THAT: This is just an example not the only scenario that can be applied.

Sample Input

What is the number of WI-FI Connections?

2

What is the number of devices Clients want to connect? 4

C1 mobile

C2 tablet

C3 pc

C4 pc

Sample Output

<pre>- (C1)(mobile)arrived
- (C2)(tablet)arrived
- Connection 1: C1 Occupied
- Connection 2: C2 Occupied
- C4(pc) arrived and waiting
- C3(pc)arrived and waiting
- Connection 1: C1 login
- Connection 1: C1 performs online activity
- Connection 2: C2 login
- Connection 2: C2 performs online activity
- Connection 1: C1 Logged out
- Connection 1 : C4 Occupied
- Connection 1 : C4 log in
- Connection 1 : C4 performs online activity
- Connection 2: C2 Logged out
- Connection 2: C3 Occupied
</pre>
</div>
</div>
</div>
<div class="page" title="Page 4"></div>
