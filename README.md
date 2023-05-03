Download Link: https://assignmentchef.com/product/solved-cs202-assignment-1-implement-sorting-algorithms
<br>
Implement the following sorting algorithms using C++ programming language and sort the input sequence in ascending order.

<ol>

 <li>Insertion Sort</li>

 <li>Selection Sort</li>

 <li>Rank Sort</li>

 <li>Bubble Sort</li>

 <li>Merge Sort</li>

 <li>Quick Sort</li>

 <li>Heap Sort</li>

</ol>

Note:

<ol>

 <li>Program should take n inputs given from the user and display the sorted sequence.</li>

 <li>Each array is implemented using the sequential linear list data structure (hpp).</li>

 <li>Everyone should use the hpp and sorting.hpp classes provided. Do not change the class names. It is expected to strictly use the interfaces provided in the classes to implement the tasks.</li>

</ol>

<h1>3           Problems</h1>

<ol>

 <li>Ross and Rachel are trying to find a new place to live together as a couple. They are in a dilemma. Their friends live in different parts of the city and they want to live close to all of them. All the houses in the city lie on the lattice(integral) points on a horizontal line (x-axis). You are given the x-coordinates of all the houses along that line in an array A of n integers <em>A</em><sub>1</sub><em>,A</em><sub>2</sub><em>,</em>·· <em>,A<sub>n</sub></em>. Your task is to find the sum of all the distinct x that will minimize the total of the distances between their(Ross and Rachel) and each friend’s house. Note that they can also live at their friends’ place if required. Print the answer modulo 10<sup>9 </sup>+7.</li>

 <li>There is a small primary school in town Gachibowli. There studies a girl named Pratibha. She is very talented and hard-working. Whenever she doesn’t find any work she starts getting depressed. Today she has completed all her school homework and now she has nothing to do. To avoid depression she usually takes an array of length n and starts playing with it. She first rolls a dice and according to a number she gets on dice she performs an operation on the array which is usually swapping some elements in the array. If the number on the dice is even she divides it by two and gets the operation number to be performed. If the number on the dice is odd then she divides the number by two and adds one to it to get the operation number to be performed. Apart from this she also has an integer ”head”.</li>

</ol>

Operation 1: She takes the (head+1)th element(say it x) from the array and inserts it between the 1st and (head)th element of the array. She inserts it at ith place such that (i+1)th element is greater than x and (i-1)th element is smaller than x(if there are multiple such places then choose min ”i”). If she doesn’t find both the conditions true at the same time she puts it at a place where at least on of the two conditions holds. After that she increase the head by 1.

Operation 2: She takes the minimum element between (head+1)th and (n)th index of the array and swaps it with (head+1)th element of the array. After that she increase the head by 1.

Operation 3: She iterates from (head+1)th element till end of the array and swaps two elements if a[i]<em>&gt;</em>a[i+1].

She has done some k operations on the array and now it’s time for her to go for her dance class. She wants you to validate if she has done any mistake while doing operations or not. (You should not use any other additional array other than array you are performing operations on.)

<ol start="3">

 <li><em>”Hardest choices require strongest wills (and so does this problem &#x1f642; )”</em>.</li>

</ol>

Thanos is the sole survivor of his planet(Moon of Saturn) Titan who has a different perception of the world. According to him, the resources of universe are limited and the days are not too far when there would only be starving and death when the resources get exhausted. So he is on his own mission to save the universe by killing half population of every species in the universe. On his conquest, he had come across infinity stones and came to know that if he could harness the power of these relics then he could achieve his goal just by a snap of his fingers. So he compelled Eitri of Nidavellir, the weapon forger, to make him a gauntlet so as to harness the power of infinity stones. Now after many hardships, he finally had all infinity stones and then snaps his finger. The gauntlet was designed in a way that doesn’t hinder the natural process of evolution by natural selection(to some extent). So it firstly divides the population into half and then exchanges at most K healthy individuals from one half to the other in order to maximize the difference between the health metrics of both groups and kills the half which is lesser healthy. What is the algorithm that gauntlet applies? Implement it.

Solve it as efficiently as much you can (in terms of time and space complexity).

Input: An array A with values as health metrics of population and integer K.

Output: Two arrays P and Q with Q being the population that has been killed.

<ol start="4">

 <li>In the primary school of Gachibowli, every morning the students assemble in the school playground for prayer. There are ’N’ lines formed at the time of prayer and each line is represented using an uppercase English alphabet. Students enter in the playground in groups of ’M’. Each student has an RollNo assigned by the school. Roll No of students also contains information about the line in which student is going to stand. RollNo’s are assigned in such a way that students of same class stand in same line. Roll No is of the form XZ(ex C123) where X is an uppercase character denoting the line in which student has to stand and Z is a unique integer id assigned to each student. Students have returned after a long vacation. Today, the student are forming lines in a particular fashion. They want to stand behind the first friend they encounter in their line. Two students are friends if they have two common factors other than 1 in their id’s(Ex: if the id’s are 6,12 then they have 2,3 as factors and they are friends. Also 4,8 are friends as they have 2,2 as common factors but 3,6 are not friends). There are total of ’K’ number of student in the school. Now the PTI Chaubey comes in and finds that the students are standing with their friends making noise. So he decided to arrange them into line according to their height.</li>

</ol>

He will swap 2 students in a line at a time and it will cost him on an average of 0.5 sec for each swap. He wants you to help him minimize the time taken to rearrange students in all lines so that the prayer will start as soon as possible. Calculate the minimum time required to rearrange each of the n lines.

Input:

N : No of lines in playground(0<em>&lt;</em>= N <em>&lt;</em>=26)

M : No of students in groups entering into ground.

K : Total number of students in school(It need not be multiple of M. In that case last group entering the ground will have (K mod M) no of students.)

The next k lines will contain two integers each corresponding to student id(integer) and his height(double)

Then there will be ceil(K/N) no of lines telling the students id’s in each group entering the ground.

Output: Output ’N’ numbers showing minimum time required to rearrange each of the n lines(numbers should be in order of line index ’A’ to ’Z’).

(Use Linked List for mimicking each line in ground. Your program should be modular and clean. Try to solve it as efficiently as possible.)