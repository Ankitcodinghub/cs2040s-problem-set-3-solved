# cs2040s-problem-set-3-solved
**TO GET THIS SOLUTION VISIT:** [CS2040S Problem Set 3 Solved](https://www.ankitcodinghub.com/product/cs2040s-data-structures-and-algorithms-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109410&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2040S Problem Set 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
We have six impostors on ours hands. Each claims to be Mr. QuickSort, the most popular sorting algorithm around. Only one of these six is telling the truth. Four of the others are just harmless imitators, Mr. BubbleSort, Ms. SelectionSort, Mr. InsertionSort, and Ms. MergeSort. Beware, however, one of the impostors is not a sorting algorithm: Dr. Evil maliciously returns unsorted arrays! And he won’t be easy to catch. He will try to trick you by often returning correctly sorted arrays. Especially on easy instances, he’s not going to slip up.

Your job is to investigate, and identify who is who and what is what. Attached to this problem set, you will find six sorting implementations: (i) SorterA.class, (ii) SorterB.class, (iii)

SorterC.class, (iv) SorterD.class, (v) SorterE.class, and (vi) SorterF.class. These are provided in a single JAR file: Sorters.jar. Each of these class files contains a class that implements the ISort interface which supports the following method:

public void sort(KeyValuePair[] array)

You can find the code for the KeyValuePair class attached as well: it is a simple container that holds two integers: a key and a value. The sort routines will sort the array of objects by key.

You can test these sorting routines in the normal way: create an array, create a sorter object, and sort. See the example file SortTestExample.java.

You can then use the StopWatch to measure how fast each of these sorting routines runs. Each sorting algorithm has some inputs on which it is fast, and some inputs on which it is slow. Some sorting algorithms are stable, and others are not. Using these properties, you can figure out who is who, and identify Dr. Evil.

IntelliJ tips: The first thing you will need to do is to import the class files into your project in

IntelliJ.

• Put the ISort.java file in the src folder.

• Put the Sorters.jar file in the src folder.

• Right click on the .jar file and click “Add as Library.”

Problem 3.a. Write a routine boolean checkSort(ISort sorter, int size) that runs a test on an array of the specified size to determine if the specified sorting algorithm sorts correctly.

Problem 3.b. Write a routine boolean isStable(ISort sorter, int size) that runs a test on an array of the specified size to determine if the specified sorting algorithm is stable.

Problem 3.c. Write whatever additional code you need in order to test the sorters to determine which is which. All evidence you give below you rely on properties of the sorting algorithms, along with data from your tests that supports your claim.

Problem 3.d. What is the true identity of SorterA? Give the evidence that proves your claim.

Problem 3.e. What is the true identity of SorterB? Give the evidence that proves your claim.

Problem 3.f. What is the true identity of SorterC? Give the evidence that proves your claim.

Problem 3.g. What is the true identity of SorterD? Give the evidence that proves your claim.

Problem 3.h. What is the true identity of SorterE? Give the evidence that proves your claim.

Problem 3.i. What is the true identity of SorterF? Give the evidence that proves your claim.
