# com1001-lab-5-solved
**TO GET THIS SOLUTION VISIT:** [COM1001 Lab 5 Solved](https://www.ankitcodinghub.com/product/com1001-lab-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99843&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COM1001 Lab 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Write a Python program which takes a sequence of inputs that contain some English-Turkish word pairs and some query items. Input data will contain a number of word pairs, i.e. M_WORDS, at the beginning and then followed by word pairs in the order of English:Turkish. After that, a query string, which contains language option to translate to, i.e. TR or EN, and a set of words will be provided.

Write a program that searches given words from the given dictionary and translates the words in the query items and prints them in alphabetical order. It is expected that your program will be able to translate both from Turkish to English and from English to Turkish. Program details and the output format is specified below. Please also look at the sample I/O files.

Specification details:

<ul>
<li>– &nbsp;You can assume that there will be at least one word pair in the dictionary and one word in the query string.</li>
<li>– &nbsp;Each word pairs will be provided in different lines.</li>
<li>– &nbsp;If the query string starts with “EN”, then your program is expected to translate the given words
into English, if starting with “TR”, then it is expected to translate them into Turkish.
</li>
<li>– &nbsp;Sometimes the same word can be searched more than once in the query. In this case, do not
print and count duplicate words.
</li>
<li>– &nbsp;When printing the words which has meaning in the dictionary, you must first print the
searched language, then the translated language. You should print these pairs in alphabetical

order according to the searched language.
</li>
<li>– &nbsp;If the query contains words that do not have meaning in the dictionary, print the total number
of not found words and the list of these words in alphabetical order.

I/O format:

input:

&lt;M_WORDS&gt;

&lt;WORD_1_EN&gt;[:]&lt;WORD_1_TR&gt;

…

&lt;WORD_M_EN&gt;[:]&lt;WORD_M_TR&gt;

&lt;TR || EN&gt;[Space] &lt;QUERY_1&gt;[Space]…. &lt;QUERY_N&gt;

output:

&lt;FOUND_QUERY_1&gt;[=]&lt;TRANSLATED_QUERY_1&gt;[Newline]

…

&lt; FOUND_QUERY_K&gt;[=]&lt;TRANSLATED_QUERY_K&gt;[Newline]

&lt;NOT_FOUND_COUNT&gt;[ word not found: ]&lt;NOT_FOUND_QUERY_1&gt;[Space]…&lt;NOT_FOUND_QUERY_L&gt;
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Please note that 0 &lt;= K &lt;= N, 0 &lt;= L &lt;= N. If K is zero, you will not print anyhing for found word pairs. If L is zero, then you will not print anything for not found words. Since the query can also contain duplicate words and these words will only be printed once, K + L &lt;= N.

Testing: You are provided with some sample I/O files. Assume that input.txt stands for a sample input and output.txt stands for the corresponding output file and your source code is named as Lab5.py; you can test your program from the command line using the following commands. (&gt;: stands for command prompt) &gt; python Lab5.py &lt; input.txt &gt; my_output.txt This command redirects the inputs in the input.txt file as if they are provided from the command line to your python code. The outputs, which you generate using the print() func1on in your source codes, are redirected to my_output.txt file. You can then check if my_output.txt file is exactly the same with the provided output.txt file, using diff command from the command prompt: &gt; diff output.txt my_output.txt

Submission:

<ol>
<li>1- &nbsp;Name your Python source file as &lt;student_id&gt;.py; replace &lt;student_id&gt; using your student id number.</li>
<li>2- &nbsp;Upload your python file using the interface provided in e-kampüs course page.</li>
</ol>
</div>
</div>
</div>
