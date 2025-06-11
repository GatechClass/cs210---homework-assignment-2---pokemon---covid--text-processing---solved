# cs210---homework-assignment-2---pokemon---covid--text-processing---solved
**TO GET THIS SOLUTION VISIT:** [CS210 – Homework Assignment 2 – Pokemon – Covid -Text Processing – Solved](https://mantutor.com/product/cs210-homework-assignment-2-pokemon-covid-text-processing-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;82530&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS210 - Homework Assignment 2  - Pokemon - Covid -Text Processing - Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<h1>Pokemon Box Dataset</h1>
<a href="https://rutgers.instructure.com/courses/133454/files/19785941/download?download_frd=1">Given a CSV data file as represented by the sample file </a><a href="https://rutgers.instructure.com/courses/133454/files/19785941/download?download_frd=1"><strong>pokemonTrain.csv </strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19785941/download?download_frd=1"><strong>&nbsp;</strong></a>

<a href="https://rutgers.instructure.com/courses/133454/files/19785941/download?download_frd=1"><strong>(https://rutgers.instructure.com/courses/133454/files/19785941/download?download_frd=1) </strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19785941/download?download_frd=1">p</a>erform the following operations on it.

<ol>
<li>[7 pts] Find out what percentage of “fire” type pokemons are at or above the “level” 40.</li>
</ol>
Your program should print the value as follows (replace … with value):

The value should be rounded off (not ceiling) using the <strong>round()</strong> function. So, for instance, if the value is 12.3 (less than or equal to 12.5) you would print 12, but if it was 12.615 (more than 12.5), you would print 13.

<strong>Print the value to a file named “pokemon1.txt”</strong>

<ol start="2">
<li>[10 pts] Fill in the missing “type” column values (given by NaN) by mapping them from the corresponding “weakness” values. You will see that usually, a given pokemon weakness has a fixed</li>
</ol>
“type”, but there do exist some exceptions. Hence, fill in the “type” column with the most common



“type” corresponding to the pokemon’s “weakness” value.

For example, most of the pokemons having the weakness “electric” are “water” type pokemons but there are other types too that have “electric” as their weakness (exceptions in that “type”). But since “water” is the most common type for weakness “electric”, it should be filled in.

In case of a tie, use the type that appears first in alphabetical order.

<ol start="3">
<li>[13 pts] Fill in the missing values in the Attack (“atk”), Defense (“def”) and Hit Points (“hp”) columns as follows:
<ol start="40">
<li>Set the pokemon level threshold to 40.</li>
<li>For a Pokemon having level above the threshold (i.e. &gt; 40), fill in the missing value for atk/def/hp with the average values of atk/def/hp of Pokemons with level &gt; 40. So, for instance, you would substitute the missing “atk” value for Magmar (level 44), with the average “atk” value for Pokemons with level &gt; 40. Round the average to one decimal place.</li>
<li>For a Pokemon having level equal to or below the threshold (i.e. &lt;= 40), fill in the missing value for atk/def/hp with the average values of atk/def/hp of Pokemons with level &lt;= 40. Round the average to one decimal place.</li>
</ol>
</li>
</ol>
<strong>After performing #2 and #3, write the modified data to another csv file named “pokemonResult.csv”</strong>

<strong>The following tasks should be performed on the pokemonResult.csv file that resulted above.</strong>

<ol start="4">
<li>[10 pts] Create a dictionary that maps pokemon types to their personalities. This dictionary would map a string to a list of strings. For example:</li>
</ol>
Note: You can create an empty default dictionary of list with defaultdict(list)

Your dictionary should have the keys ordered alphabetically, and also items ordered alphabetically in the values list, as shown in the example.

Print the dictionary in the following format:

<strong>Print the dictionary to a file named “pokemon4.txt”</strong>

<ol start="5">
<li>[5 pts] Find out the average Hit Points (“hp”) for pokemons of stage 3.0.</li>
</ol>
Your program should print the value as follows (replace … with value):



You should round off the value, like in #1 above.

<strong>Print the value to a file named “pokemon5.txt”</strong>

<h1>Problem 2: Covid-19 Dataset (35 points)</h1>
Given a Covid-19 data CSV file with 12 feature columns, perform the tasks given below. Use the sample <a href="https://rutgers.instructure.com/courses/133454/files/19786046/download?download_frd=1">file </a><a href="https://rutgers.instructure.com/courses/133454/files/19786046/download?download_frd=1"><strong>covidTrain.csv</strong></a> <a href="https://rutgers.instructure.com/courses/133454/files/19786046/download?download_frd=1"><strong>&nbsp;</strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786046/download?download_frd=1"><strong>(https://rutgers.instructure.com/courses/133454/files/19786046/download? download_frd=1) </strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786046/download?download_frd=1">&nbsp;to test your code.</a>

<ol>
<li>[5 pts] In the age column, wherever there is a range of values, replace it by the rounded off average value. E.g., for 10-14 substitute 12. (Rounding should be done like in 1.1). You might want to use regular expressions here, but it is not required.</li>
<li>[6 pts] Change the date format for the date columns – date_onset_symptoms, date_admission_hospital and date_confirmation from dd.mm.yyyy to mm.dd.yyyy. Again, you can use regexps here, but it is not required.</li>
<li>[7 pts] Fill in the missing (NaN) “latitude” and “longitude” values by the average of the latitude and longitude values for the province where the case was recorded. Round the average to 2 decimal places.</li>
<li>[7 pts] Fill in the missing “city” values by the most occurring city value in that province. In case of a tie, use the city that appears first in alphabetical order.</li>
<li>[10 pts] Fill in the missing “symptom” values by the single most frequent symptom in the province where the case was recorded. In case of a tie, use the symptom that appears first in alphabetical order.</li>
</ol>
<strong>Note</strong>: While iterating through records, if you come across multiple symptoms for a single record, you need to consider them individually for frequency counts.

<strong>Very Important!</strong>: Some symptoms could be separated by a ‘;’ , i.e., semicolon plus space and some by ‘;’ , i.e., just a semicolon, even within the same record. For example:

<strong>After performing all these tasks, write the whole data back to another CSV file named “covidResult.csv”</strong>



<h1>Problem 3: Text Processing (60 pts)</h1>
For this problem, you are given a set of documents (text files) on which you will perform some preprocessing tasks, and then compute what is called the TF-IDF score for each word. The TF-IDF score for a word is measure of its importance within the entire set of documents: the higher the score, the more important is the word.

The input set of documents must be read from a file named “tfidf_docs.txt”. This file will list all the documents (one per line) you will need to work with. For instance, if you need to work with the set “doc1.txt”, “doc2.txt”, and “doc2.txt”, the input file “tfidf_docs.txt” contents will look like this:

For each document in the input set, clean and preprocess it as follows:

<ol>
<li>[15 pts] Clean.</li>
</ol>
Remove all characters that are not words or whitespaces. Words are sequences of letters (upper and lower case), digits, and underscores.

Remove extra whitespaces between words. e.g., “Hello World! Let’s&nbsp;&nbsp; learn&nbsp;&nbsp;&nbsp; Python!”, so that there is exactly one whitespace between any pair of words.

Remove all website links. A website link is a sequence of non-whitespace characters that starts with either “http://” or “https://”.

Convert all the words to lowercase.

The resulting document should only contain lowercase words separated by a single whitespace.

<ol start="2">
<li>[7 pts] Remove stopwords.</li>
</ol>
From the document that results after #1, remove “stopwords”. These are the non-essential (or

<a href="https://rutgers.instructure.com/courses/133454/files/19787014/download?download_frd=1">“noise”) words listed in the file </a><a href="https://rutgers.instructure.com/courses/133454/files/19787014/download?download_frd=1"><strong>stopwords.txt</strong></a> <a href="https://rutgers.instructure.com/courses/133454/files/19787014/download?download_frd=1"><strong>&nbsp;</strong></a>

<a href="https://rutgers.instructure.com/courses/133454/files/19787014/download?download_frd=1"><strong>(https://rutgers.instructure.com/courses/133454/files/19787014/download?download_frd=1) </strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19787014/download?download_frd=1">&nbsp;</a>

<ol start="3">
<li>[8 pts] Stemming and Lemmatization.</li>
</ol>
This is a process of reducing words to their root forms. For example, look at the following reductions: run, running, runs → run. All three words capture the same idea ‘run’ and hence their suffixes are not as important.

<a href="https://nlp.stanford.edu/IR-book/html/htmledition/stemming-and-lemmatization-1.html">(If you would like to get a better idea, you may want read this </a><a href="https://nlp.stanford.edu/IR-book/html/htmledition/stemming-and-lemmatization-1.html"><strong>article</strong></a>

<a href="https://nlp.stanford.edu/IR-book/html/htmledition/stemming-and-lemmatization-1.html"><strong>(https://nlp.stanford.edu/IR-book/html/htmledition/stemmin</strong></a><a href="https://nlp.stanford.edu/IR-book/html/htmledition/stemming-and-lemmatization-1.html"><strong>g</strong></a><a href="https://nlp.stanford.edu/IR-book/html/htmledition/stemming-and-lemmatization-1.html"><strong>-and-lemmatization-1.html) </strong></a>. This is completely optional, you can do the assignment without reading the article.)

<sup> </sup>Use the following rules to reduce the words to their root form:

<ol>
<li>Words ending with “ing”: “flying” becomes “fly”</li>
<li>Words ending with “ly”: “successfully” becomes “successful”</li>
<li>Words ending with “ment”: “punishment” becomes “punish”</li>
</ol>
These rules are not expected to capture all the edge cases of Stemming in the English language but are intended to give you a general idea of the preprocessing steps in NLP (Natural Language Processing) tasks.

<strong>After performing #1, #2, and #3 for each input document, write the modified data to another text file with the prefix “preproc_”. For instance, if the input document is “doc1.txt”, the output should be “preproc_doc1.txt”.</strong>

<strong>&nbsp;Part 2: Computing TF-IDF Scores (30 pts)</strong>

Once preprocessing is performed on all the documents, you need to compute the

Term Frequency(TF) — Inverse Document Frequency(IDF) score for each word

What is TF-IDF?

<table width="694">
<tbody>
<tr>
<td width="694">In information retrieval, tf–idf or TFIDF, short for term frequency–inverse document frequency, is a numerical statistic that is intended to reflect how important a word is to a document in a collection or corpus.

Resources:

<strong><u>&nbsp;</u></strong><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>TFIDF P</strong></a><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>y</strong></a><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>thon Example</strong></a><strong><u>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </u></strong><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong> (https://towardsdatascience.com/natural-lan</strong></a><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>g</strong></a><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>ua</strong></a><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>g</strong></a><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>e-processin</strong></a><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>g</strong></a><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>feature-en</strong></a><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>g</strong></a><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>ineerin</strong></a><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>g</strong></a><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>-usin</strong></a><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>g</strong></a><a href="https://towardsdatascience.com/natural-language-processing-feature-engineering-using-tf-idf-e8b9d00e7e76"><strong>-tf-idf-e8b9d00e7e76)</strong></a>

<a href="https://en.wikipedia.org/wiki/Tf%E2%80%93idf"><strong>tf-idf Wikipedia Pa</strong></a><a href="https://en.wikipedia.org/wiki/Tf%E2%80%93idf"><strong>g</strong></a><a href="https://en.wikipedia.org/wiki/Tf%E2%80%93idf"><strong>e</strong></a><strong><u>&nbsp;&nbsp; </u></strong><a href="https://en.wikipedia.org/wiki/Tf%E2%80%93idf"><strong> (https://en.wikipedia.or</strong></a><a href="https://en.wikipedia.org/wiki/Tf%E2%80%93idf"><strong>g</strong></a><a href="https://en.wikipedia.org/wiki/Tf%E2%80%93idf"><strong>/wiki/Tf%E2%80%93idf)</strong></a>

<a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>TF-IDF/Term Frequenc</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>y</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong> Technique</strong></a><strong><u>&nbsp;&nbsp; </u></strong><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>&nbsp;(https://medium.com/anal</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>y</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>tics-vidh</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>y</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>a/tf-idf-termfrequenc</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>y</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>-technique-easiest-explanation-for-text-classification-in-nlp-with-code8ca3912e58c3)</strong></a>
</td>
</tr>
</tbody>
</table>
Steps:

<ol>
<li>For each preprocessed document that results from the preprocessing in Part 1, compute frequencies of all the distinct words in that document only. So if you had 3 documemnts in the input set, you will 3 sets of word frequencies, one per document.</li>
<li>Compute the Term Frequency (TF) of each distinct word (also called term) for each of the preprocessed documents:</li>
</ol>
TF(t) = (Number of times term t appears in a document) / (Total number of terms in the document)

<sup> </sup>Note: The denominator, total number of terms, is the sum total of all the words, not just unique instances. Another way to think of this is it is the sum of the number of times each word appears in the document.

<ol>
<li>Compute the Inverse Document Frequency (IDF) of each distinct word for each of the preprocessed documents.</li>
</ol>
IDF is a measure of how common or rare a word is in a document set (a set of preprocessd text files in this case). It is calculated by taking the logarithm of the following term:

To avoid division by zero, set the IDF value as 0 if the ‘Number of documents the word is found in’ is 0.

Also, add 1 to the IDF score so that the TF-IDF score is non-zero. You can read more about IDF here.

<ol>
<li>Calculate TF-IDF score: TF * IDF for each distinct word in each preprocessed document. Use 2 decimal places for the score. Round the average to 2 decimal places.</li>
<li>Print the top 5 most important words in each preprocessed document according to their TF-IDF scores. The higher the TF-IDF score, the more important the word. In case of ties in a document, pick words in alphabetical order. You should print the result as a list of (word,TF-IDF score) tuples sorted in descending TF-IDF scores.</li>
</ol>
<strong>Print to a file prefixed with “tfidf_”. So if the initial input document was “doc1.txt”, you should print the TF-IDF results to “tfidf_doc1.txt”</strong>.

<strong>Testing:</strong>

<ol>
<li>You can begin with the following three sentences as separate documents against which to test your code:</li>
</ol>
#d1 = “It is going to rain today.”

#d2 = “Today I am not going outside.”

#d3 = “I am going to watch the season premiere.”

<a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3">You can match values computed by your code with this same example in the </a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>TF-IDF/Term</strong></a>

<a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>Frequenc</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>y</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong> Technique</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>&nbsp;(https://medium.com/anal</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>y</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>tics-vidh</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>y</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>a/tf-idf-term-frequenc</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>y</strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3"><strong>-techniqueeasiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3) </strong></a><a href="https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3">page referenced abov</a>e.

Look for it under “Let’s cover an example of 3 documents” on this page.

<ol start="2">
<li><a href="https://rutgers.instructure.com/courses/133454/files/19786243/download?download_frd=1">Next, you can test your code against </a><a href="https://rutgers.instructure.com/courses/133454/files/19786243/download?download_frd=1"><strong>txt</strong></a></li>
</ol>
<a href="https://rutgers.instructure.com/courses/133454/files/19786243/download?download_frd=1"><strong>(https://rutgers.instructure.com/courses/133454/files/19786243/download?download_frd=1) </strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786243/download?download_frd=1">a</a>nd <a href="https://rutgers.instructure.com/courses/133454/files/19786254?wrap=1"><strong>test2.txt</strong></a> <a href="https://rutgers.instructure.com/courses/133454/files/19786254/download?download_frd=1"><strong>&nbsp;</strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786254/download?download_frd=1"><strong>(https://rutgers.instructure.com/courses/133454/files/19786254/download?download_frd=1)</strong></a>

<a href="https://rutgers.instructure.com/courses/133454/files/19786290/download?download_frd=1">. Compare your resulting preprocessed documents with our results in </a><a href="https://rutgers.instructure.com/courses/133454/files/19786290/download?download_frd=1"><strong>preproc_test1.txt</strong></a> <a href="https://rutgers.instructure.com/courses/133454/files/19786290/download?download_frd=1"><strong>&nbsp;</strong></a>

<sup></sup><a href="https://rutgers.instructure.com/courses/133454/files/19786290/download?download_frd=1"><strong>(https://rutgers.instructure.com/courses/133454/files/19786290/download?download_frd=1) </strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786290/download?download_frd=1">and </a><a href="https://rutgers.instructure.com/courses/133454/files/19786297/download?download_frd=1"><strong>preproc_test2.txt </strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786297/download?download_frd=1"><strong>&nbsp;</strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786297/download?download_frd=1"><strong>(https://rutgers.instructure.com/courses/133454/files/19786297/download? </strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786304/download?download_frd=1"><strong>download_frd=1) </strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786304/download?download_frd=1">, and your TF-IDF results with our results in&nbsp; </a><a href="https://rutgers.instructure.com/courses/133454/files/19786304/download?download_frd=1"><strong>tfidf_test1.txt</strong></a> <a href="https://rutgers.instructure.com/courses/133454/files/19786304/download?download_frd=1"><strong>&nbsp;</strong></a>

<a href="https://rutgers.instructure.com/courses/133454/files/19786304/download?download_frd=1"><strong>(https://rutgers.instructure.com/courses/133454/files/19786304/download?download_frd=1) </strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786304/download?download_frd=1">&nbsp;</a>and <a href="https://rutgers.instructure.com/courses/133454/files/19786328/download?download_frd=1"><strong>tfidf_test2.txt</strong></a> <a href="https://rutgers.instructure.com/courses/133454/files/19786328/download?download_frd=1"><strong>&nbsp;</strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786328/download?download_frd=1"><strong>(https://rutgers.instructure.com/courses/133454/files/19786328/download? download_frd=1) </strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786328/download?download_frd=1">&nbsp;&nbsp;</a>

<ol start="3">
<li><a href="https://rutgers.instructure.com/courses/133454/files/19786393/download?download_frd=1">Finally, you can try your code on these files: </a><a href="https://rutgers.instructure.com/courses/133454/files/19786393/download?download_frd=1"><strong>txt</strong></a></li>
</ol>
<a href="https://rutgers.instructure.com/courses/133454/files/19786393/download?download_frd=1"><strong>(https://rutgers.instructure.com/courses/133454/files/19786393/download?download_frd=1) </strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786393/download?download_frd=1">, </a><a href="https://rutgers.instructure.com/courses/133454/files/19786400/download?download_frd=1"><strong>covid_doc2.txt</strong></a> <a href="https://rutgers.instructure.com/courses/133454/files/19786400/download?download_frd=1"><strong>&nbsp;</strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786400/download?download_frd=1"><strong>(https://rutgers.instructure.com/courses/133454/files/19786400/download?</strong></a>

<a href="https://rutgers.instructure.com/courses/133454/files/19786405/download?download_frd=1"><strong>download_frd=1) </strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786405/download?download_frd=1">and </a><a href="https://rutgers.instructure.com/courses/133454/files/19786405/download?download_frd=1"><strong>covid_doc3.txt</strong></a> <a href="https://rutgers.instructure.com/courses/133454/files/19786405/download?download_frd=1"><strong>&nbsp;</strong></a>

<a href="https://rutgers.instructure.com/courses/133454/files/19786405/download?download_frd=1"><strong>(https://rutgers.instructure.com/courses/133454/files/19786405/download?download_frd=1) </strong></a><a href="https://rutgers.instructure.com/courses/133454/files/19786405/download?download_frd=1">.</a> Results for these are not provided, however the files are small enough that you can identify the words that make the cut and manually compute TF-IDF.
