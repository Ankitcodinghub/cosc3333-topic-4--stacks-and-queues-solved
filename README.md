# cosc3333-topic-4--stacks-and-queues-solved
**TO GET THIS SOLUTION VISIT:** [COSC3333 Topic 4- Stacks and Queues Solved](https://www.ankitcodinghub.com/product/cosc3333-cosc3331-data-structures-algorithms-ii-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113668&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COSC3333 Topic 4- Stacks and Queues Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Target Topic: Stacks and Queues

Important Note:

Throughout this document, you will find questions that appear in bold italics. You must address these questions in a separate file that will be the report you must submit along with the working set of programs required for this assignment.

These reports will be an important portion of the grade for these assignments as they show your understanding of the programs you submit and the underlying rationale for the strategy you have adopted to solve these programming problems.

Devise your answers carefully and in an organized manner.

The working programs without justifying report to prove your understanding of your solution will not be granted a passing grade.

Here is the description of the assignment:

You are asked to use TWO STACKS and ONE QUEUE to implement an experimental

As for data we are using objects of type Item defined as follows: class Item

Attributes: int key; //randomly generated in the range 1-10 inclusive int timeStamp; //The number representing the object’s order of generation //The first object instantiated will have 1 for this attribute, //The second will have 2, etc.

Methods:

The constructor that receives a randomly generated number and a time stamp starting with 1 to the total number of items to be created.

The toString method to display the attributes of this object in the following format: For an Item with 5 for the key and the time stamp of 1, this method will generate the following String:

5:1

Note that these objects will be sorted based on their key attributes.

Important note: We ALLOW DUPLICATE values for keys in this assignment. This means that you MUST take this possibility into consideration and incorporate that in your algorithm.

As you notice the timeStamp is our guide to keep track of the duplicate values from their position in the original sequence to where they will end up in the sorted sequence.

Important Notes:

• Do not attempt to sort these objects based on their time stamp. Every sort algorithm must stick with a criteria and for us that is the key attribute.

• You are devising a new sorting algorithm, do not call pre-defined sorting algorithms provided by the textbook or worst from other sources to sort this data. You MUST come up with a strategy to use these data structures to sort data.

This is how you get started on this assignment:

Prompt the user for the size of data, not exceeding 20.

At the beginning, you process each object one at a time, deciding where they need to go, your choices are two stacks and a queue or a variable that holds the object with the maximum or minimum key, based on your strategy.

The point is that you do not store all these Item objects in an input array and THEN get to sorting them. You get the objects one at a time and decide where they go based on their keys and your strategy.

After you are done with instantiating all your objects, you should have identified the object with the maximum or minimum key of all, that item (or items in case we have duplicate of max/min key) will be placed in the proper spot/spots in your output array, hence sorting the list one item at a time.

An additional note: Notice that if you go by finding the maximum key, your output array will be populated from the end, and if you go for the minimum, it will be populated from the beginning: Your Choice. I go with the maximum for these instructions.

After you found the object with maximum key of all, you have the rest of data to process and find the next max item/items. The rest of data is stored in one of your data structures. You continue the process of sorting the rest of the data set based on their keys. You notice the size of data now is short of one or possibly more, if we had a duplicate situation, compared to the previous step.

As stated above, this sorting algorithm will build the sorted sequence one item at a time. So you need to constantly move your data among the stacks and the queue to find the next item/s to be placed in the proper position/s. When done, the two stacks and the queue will be empty and your output array will be populated by the sorted data set.

These are what you need to output for this assignment:

ONLY FOR THE PURPOSE OF THIS ASSIGNMENT, YOU SHOULD ADD THE FOLLOWING TWO METHODS IN THE STACKX AND QUEUE CLASSES GIVEN IN THE BOOK:

displayStack() displayQueue()

These display methods must call the toString methods of Item objects to display their attributes of keys and time stamps.

This is to monitor the contents of the stacks and the queues throughout implementation of your algorithm.

A sample label of the output at every step of your algorithm would be:

Stack1(bottom -&gt; top):

Stack2(bottom -&gt; top):

Queue(front -&gt; rear):

OutputArray:

++++++++++++++++++++++++++++++++++++++++

where the contents of each data structure will follow on each line, at every iteration of your process. For the output array, you can display zeros for the yet-to-be populated spots. Note that you must check for null spots in this output array to avoid nullPointerException. Note that the +++ line helps the readability of the output of your program by separating the steps.

The following are the points you must address in your report: i. Explain your algorithm in a step-by-step format.

ii. What role did the queue play in your algorithm? Could you have fulfilled all the requirements of this assignment with three stacks? Explain your answer. iii. Is this experimental sorting algorithm stable? Explain your answer. iv. Does this experimental sorting algorithm sort in place? Explain your answer. v. What is the running time of this algorithm in big O notation?

vi. Share your thoughts on the challenge of making this algorithm a stable algorithm

• Programs that do not compile will be considered void.
