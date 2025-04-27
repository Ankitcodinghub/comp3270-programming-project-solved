# comp3270-programming-project-solved
**TO GET THIS SOLUTION VISIT:** [COMP3270 Programming Project Solved](https://www.ankitcodinghub.com/product/comp3270-programming-project-autocomplete-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121318&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP3270 Programming Project Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1. Pseudocode: Understand the strategy provided for TrieAutoComplete. State the algorithm for the functions precisely using numbered steps that follow the pseudocode conventions that we use. Provide an approximate efficiency analysis by filling the table given below, for your algorithm.

Add

• Pseudocode:

// word is of the string type and weight is a double type

• ADD(word, weight)

1. if weight &lt; 0 then error

2. if word = NIL then error

3. pointer = root of trie

4. index = 1

5. Let W[1…word.length] be a new array of the chars from word

6. while (index &lt;= W.length)

7. key = W[index]

8. if (weight &gt; pointer’s subtreeMaxWeight)

9. //subtreeMaxWeight is an attribute of a node

10. pointer’s subtreeMaxWeight = weight

11. if (pointer.child(key) = NIL)

12. create a new child node for pointer with key value

13. pointer = pointer.child(key)

14. index = index + 1

15. if (index = W.length)

16. set pointer’s word

17. set pointer is a word

18. set pointer’s weight

• Complexity analysis:

Step # Complexity stated as O( )

1 O(1)

2 O(1)

3 O(1)

4 O(1)

5 O(1)

6 O(n)

7 O(n)

8 O(n)

9 Ignore comment

10 O(n)

11 O(n)

12 O(n)

13 O(n)

14 O(n)

15 O(n)

16 O(n)

17 O(n)

18 O(n)

Complexity of the algorithm = O(n)

topMatch

• Pseudocode:

// prefix is a string

• TOPMATCH(prefix)

1. if prefix = NIL then error

2. pointer = root of trie

3. index = 1

4. Let W[1…prefix.length] be a new array of the chars from prefix

5. while (index &lt;= W.length)

6. key = W[index]

7. if (pointer.child(key) NIL)

8. pointer = pointer.child(key)

9. else

10. return “ “

11. index = index + 1

12. create a new max-priority queue PQ for Nodes sorted by subtreeMaxWeight

13. wordFound = false 14. output = “ “

15. while (wordFound)

16. if (pointer is a word)

17. if (pointer’s weight = pointer’s maxSubtreeWeight)

18. wordFound = true

19. ouput = pointer’s word

20. else wordFound = false

21. for all of pointer’s children

22. add them to PQ

23. pointer = PQ.head

24. return output

• Complexity analysis:

Step # Complexity stated as O( )

1 O(1)

2 O(1)

3 O(1)

4 O(1)

5 O(n)

6 O(n)

7 O(n)

8 O(n)

9 O(n)

10 O(n)

11 O(n)

12 O(1)

13 O(1)

14 O(1)

15 O(n)

16 O(n)

17 O(n)

18 O(n)

19 O(n)

20 O(n)

21 O(n2)

22 O(n2)

23 O(n)

24 O(1)

Complexity of the algorithm = O(n2)

topMatches

• Pseudocode:

// prefix is of the string type and k is an integer type

• TOPMATCH(prefix, k)

2. if prefix = NIL then error

3. Let N be a new array list of strings that is empty

4. if k &lt;= 0 then return N

5. pointer = root of trie

6. index = 1

7. Let W[1…prefix.length] be a new array of chars from prefix

8. while (index &lt;= W.length)

9. key = W[index]

10. if (pointer.child(key) NIL)

11. pointer = pointer.child(key)

12. else

13. return N

14. index = index + 1

15. create a new max-priority queue PQ for Nodes sorted by subtreeMaxWeight

16. create a new array list TN of nodes that is empty

17. create a new array list OUT of strings that is empty

18. add pointer to PQ

19. while (PQ.size &gt; 0)

20. if (TN.size = k)

21. sort TN //ascending order

22. firstNode = TN’s first node

23. secondNode = PQ.head

24. if (firstNode’s weight &gt; secondNode)

25. break

26. pointer = PQ.head

27. for all of pointer’s children

28. add child to PQ

29. if (pointer is a word)

30. add pointer to TN

31. sort TN in descending order

32. if (TN.size &gt;= k)

33. for i = 1 to k

34. add TN’s ith node’s word to OUT

35. else

36. for each node in TN

37. add the node’s word to OUT

38. return OUT

• Complexity analysis:

Step # Complexity stated as O(_)

1 O(1)

2 O(1)

3 O(1)

4 O(1)

5 O(1)

6 O(1)

7 O(n)

8 O(n)

9 O(n)

10 O(n)

11 O(n)

12 O(n)

13 O(n)

14 O(1)

15 O(1)

16 O(1)

17 O(1)

18 O(n)

19 O(n)

20 O(n2)

21 O(n)

22 O(n)

23 O(n)

24 O(n)

25 O(n)

26 O(n2)

27 O(n2)

28 O(n)

29 O(n)

30 O(n)

31 O(1)

32 O(n)

33 O(n)

34 O(1)

35 O(n)

36 O(n)

37 O(1)

Complexity of the algorithm = O(n2)

2.Testing: Complete your test cases to test the TrieAutoComplete functions based upon the criteria mentioned below.

Test of correctness:

Assuming the trie already contains the terms {”ape, 6”, ”app, 4”, ”ban, 2”, ”bat, 3”, ”bee, 5”, ”car, 7”, ”cat, 1”}, you would expect results based on the following table:

Query k Result

”” 8 {”car”, ”ape”, ”bee”, ”app”, ”bat”, ”ban”,

”cat”}

”” 1 {”car”}

”” 2 {”car”, ”ape”}

”” 3 {”car”, ”ape”, ”bee”}

”a” 1 {”ape”}

”ap” 1 {”ape”}

”b” 2 {”bee”, ”bat”}

”ba” 2 {”bee”, ”bat”}

”d” 100 {}

3.Analysis: Answer the following questions. Use data wherever possible to justify your answers, and keep explanations brief but accurate:

i. What is the order of growth (big-Oh) of the number of compares (in the worst case) that each of the operations in the Autocompletor data type make?

For the add operation the order of growth is O(n). This is because at most it will have to look at n characters in a word and add them to the trie.

For the topMatches operation the order of growth is O(n2). This is because, for every node looked at in a subtree, each of its children nodes will also have to be looked at. So if you have n nodes to look at with n children each, the cost will be O(n2)

The topMatch operation performs like topMatches with a growth of O(n2). (topMatch and topMatches have very similar algorithms)

ii. How does the runtime of topMatches() vary with k, assuming a fixed prefix and set of terms? Provide answers for

BruteAutocomplete and TrieAutocomplete. Justify your answer, with both data and algorithmic analysis.

Based on the benchmark data in the graph below (Figure 1) TrieAutoComplete performs slower as k increases. However, this is only when the prefix is a real word. When prefix is not a real word the algorithm detects it on the traversal to the prefix node and never enters the part of the program that looks for the k top words. When prefix is a real word it takes longer to find the k top words when k is larger because the algorithm will generally have to run its loop for a longer time. However, compared to Brutes benchmark data, Trie will still perform better with a higher k value.

BruteAutoComplete’s benchmark data (Figure 2) suggests that it is not as affected by k as TrieAutoComplete is. This is because BruteAutoComplete goes through every term it has no matter what the k value is (it’s for each loop does not break until every word is looked at). It’s time cost is also much higher than TrieAutoComplete’s in every case.

iii. How does increasing the size of the source and increasing the size of the prefix argument affect the runtime of topMatch and topMatches? (Tip: Benchmark each implementation using fourletterwords.txt, which has all four-letter combinations from aaaa to zzzz, and fourletterwordshalf.txt, which has all four-letter word combinations from aaaa to mzzz. These datasets provide a

very clean distribution of words and an exact 1-to-2 ratio of words in source files.)

Based on the results from the benchmark analysis, there were not many distinct time differences between fourletterwords.txt and fourletterwordshalf.txt. As far as increasing the prefix, it shouldn’t have too much of an effect on time cost as opposed to the effect the k value would have. This is because the size of the prefix is only important in so far as navigating to the prefix node only requires a growth of O(n) compared to the second part of the algorithm (the part that finds the k words) which has growth of O(n2). Additionally, increasing the input size usually results in much higher time cost. However, based on the benchmark data there was not much of a difference between the results of the two text files.

4. Graphical Analysis: Provide a graphical analysis by comparing the following:

i. The big-Oh for TrieAutoComplete after analyzing the pseudocode and big-Oh for TrieAutoComplete after the implementation.

The big-Oh for the pseudocode and the actual implementation are the same.

ii. Compare the TrieAutoComplete with BruteAutoComplete and BinarySearchAutoComplete.

Words-333333.txt(Figures 3 and 4): For the most part TrieAutoComplete is comparable in time cost to BruteAutoComplete and BinarySearchAutoComplete. There are several instances where it performs faster than either Brute or Binary (e.g. when anotrealword is passed). However, when whitespace is passed as a parameter for topMatches, TrieAutoComplete performs significantly slower than the other two.

Fourletterwords.txt (Firgure 5): Unlike with words-333333, with four letter words TrieAutoComplete performs better than both BruteAutoComplete and BinaryAutoComplete in terms of time cost. BruteAutoComplete performs the worst out of the three, with Binary and Trie being the most comparable to each other.

GRAPHS
