# big-data-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [Big Data Homework 1 Solved](https://www.ankitcodinghub.com/product/big-data-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101424&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Big Data Homework 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Problem 1&nbsp; Data: /home/public/google

Description: The data for this problem comes from Google’s project for counting word frequencies in its entire Google Books collection. You are given two files: one file reports 1 grams (single words) and another file reports 2 grams (pairs of words; one following each other in text). The data represents the number of occurrences of a particular word (or pairs of words) in a given year across all books available by Google Books. The number of volumes/books containing a word (or pairs of words) is also reported.

Write a MapReduce program that reports the average number of volumes per year for words containing the following three substrings: ‘nu,’ ‘chi,’ ‘haw’.

Example:

The 1-gram file format –the regex “\\s+” will match any kind of whitespace (space, tab etc):

word \\s+ year \\s+ number of occurrences \\s+ number of volumes \\s+ … The 2-gram (bigram) file format:

word \\s+ word \\s+ year \\s+ number of occurrences \\s+ number of volumes \\s+…

The final output should show the year, substring, and average number of volumes across both bigram

and unigram formats where the substring appears in that year. For example: 2000,nu,345

2010,nu,200

1998,chi,31

The ‘year’ column may include erroneous values which can be a string. If the year field is a string, the record should be discarded.

If each word in the bigram includes the string, it should be counted twice in the average.

For example, for the bigram “nugi hinunu” with volume count of 10, when calculating the average, its contribution to the numerator should be 2 times 10 and in the denominator, it should be 2. A unigram counts only once regardless of the number of occurrences of “nu” in the word.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Do this in the most efficient way with a single MapReduce job. Beyond the file formats described above, you are not allowed to make any structural assumptions on the data; e.g., that the 2 gram file contains more fields compared to the 1 gram file.

Problem 2 (40 points) Data: /home/public/google

Description: The data set is the same as in the previous exercise. You need to compute the standard deviation of all volume values (across all records and both files) in MapReduce. The output should be a single value. You must not use more than 2 MapReduce jobs.

Problem 3 Data: /home/public/music

Description: The data for this problem is a subset of the million-song database (https://www.kaggle.com/c/msdchallenge#description), and its size is 42GB. The file is in csv format. Your task is to extract the song title (column 1), artist’s name (column 2) and duration (column 3) for all songs published between the years 2000 and 2010. The year is in column 166 – note that some year entries can be erroneous and should be discarded. Additionally, you can assume that all songs are unique, so there is no need to remove any duplicates. You should do this as efficiently as possible in MapReduce.

Problem 4 Data: /home/public/music

Description: The data set is the same as in the previous exercise. For each artist in the data set, compute the maximum duration across all of their songs. The output should be: artist, max duration.

In addition, the management of your firm wants the artists’ names to be sorted across all files based on the first character. This means that each output file of your MapReduce job must be sorted by the first character of an artist’s name. You cannot take the output files and then sort them in a spreadsheet software. You are only allowed to concatenate the output files in the end.

In order to save computing resources for your firm, you have to use 5 reducers.

</div>
</div>
</div>
