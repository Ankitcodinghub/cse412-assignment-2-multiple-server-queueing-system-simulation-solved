# cse412-assignment-2-multiple-server-queueing-system-simulation-solved
**TO GET THIS SOLUTION VISIT:** [CSE412 Assignment 2-Multiple-server queueing system simulation Solved](https://www.ankitcodinghub.com/product/cse-412-simulation-and-modeling-lab-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112788&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE412 Assignment 2-Multiple-server queueing system simulation Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Assignment-2 (Multiple-server queueing system simulation)

• Consider an office building with 12 floors (numbered 1–12). There are four elevators (servers) which service the building. Each elevator has a maximum capacity of 12 passengers.

• People (customers) enter the lobby of the building at floor 1 and take an elevator to their destination floor (floor 2 to floor 12). Each customer selects the first available elevator (numbered 1–4). When a person enters an elevator and selects the floor of destination, the elevator waits 15 sec (door holding time) before closing its doors. If another person arrives within the 15-sec interval, the waiting cycle is repeated. If no person arrives within the 15-sec interval, the elevator departs to deliver all of its passengers. It is assumed that, even if fully loaded with 12 passengers, the elevator waits 15 sec before departing. We assume no other passengers are picked up along the way. After delivering its last passenger, the elevator returns to the main floor, picking up no passengers on the way down. When a person arrives in the lobby and no elevator is available (because all four elevators are transporting their load of passengers), a queue begins to form in the lobby.

• We assume that it takes 5 sec for an elevator to travel between floors, 3 sec to open and 3 sec close its doors, and 3 sec for each passenger to disembark. We also assume that it takes 3 sec for each passenger in a queue to enter the next available elevator.

• A customer chooses a floor with equal likelihood [uniform probability distribution U (2, 12)].

• The simulation terminates when the simulation clock value exceeds 10000 sec.

• For performance measure, we consider the following quantities:

1) Total number of customers serviced during the entire simulation

2) queue length means the number of customers in queue

3) (delay time)i means the time customer i waits in a queue before stepping into an elevator

4) (elevator time)i means the time customer i spends in an elevator

5) (delivery time)i means the time required to deliver customer i to destination floor from time of arrival, including any waiting time.

6) (load size)j means number of occupants of elevator j when it departs from floor 1

7) (operation time)j means the total time elevator j operates (running between floors) during the entire simulation

8) (available time)j means the total time elevator j spends in floor 1 being available for loading

9) (number of max loads)j means the total number of times elevator j departs from floor 1 with full load of 12 customers during the entire simulation

10) (number of stops)j means the total number of stops made by elevator j during the entire simulation

Format of the Input:

10000 // simulation termination

12 4 12 6 // number of floors, elevators, capacity, batch size

15 5 3 3 //door holding time, inter-floor traveling time, opening time, closing time

3 3 // passenger embarking and disembarking time

1.5 // mean interarrival time

Format of the Output: The output can be presented in a tabular format like the following table:

All times are measured in seconds and rounded to the nearest second.
