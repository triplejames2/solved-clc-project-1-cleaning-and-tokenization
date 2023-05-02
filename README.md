Download Link: https://assignmentchef.com/product/solved-clc-project-1-cleaning-and-tokenization
<br>
<h1></h1>

Write a program that can clean a file and count the words in it.  It should run using the following command in the terminal:

./clean_and_count_tokens.py &lt;input_file&gt; &lt;output_file&gt;

The input file to clean is in xml, which contain tags encased in &lt;&gt;.  These tags should <u>not</u> be counted.  All other words are counted.

A word may only contain the following:

<ul>

 <li>Capital letters</li>

 <li>Lowercase letters</li>

 <li>the straight apostrophe ‘</li>

 <li>internal periods (with alphabetic characters on either side)</li>

</ul>

Words should count towards the tally regardless of capitalization.  Ex: ‘Is’ and ‘is’ should both count as instances of ‘is’

Write the results to a file, one word per line with the count IN ORDER from most common to least common.  Ties should be in alphabetical order.  There should be a single tab between the word and the count.

A sample input/output is included in the folder.  Please take a look!

Please run your code on the included Wikipedia-LexicalAnalysis.xml, and call the output file lexical_analysis_out.txt

You may only import: sys, re (or regex)

Your submission should include the following 2 files:

<ol>

 <li>py</li>

 <li>txt</li>

</ol>

Depending on how you organize your code, you may have more files than this.

Due Monday, March 11, 2019

<h2>Level 2</h2>

In addition to the above file, write a program that uses nltk’s word_tokenizer and porter stemmer after cleaning out the tags, but before counting the tokens.  This program should run using the following command in the terminal:

./nltk_clean_and_count_stems.py &lt;input_file&gt; &lt;output_file&gt;

For more information about NLTK’s tokenizing/stemming, check out Chapter 3 of the NLTK book: <u><a href="http://www.nltk.org/book/ch03.html">http://www.nltk.org/book/ch03.html</a></u>

Check out sample_stemmed_out.txt for an example output.

You may import: sys, re (or regex), nltk (for this file only)

Your submission should include:

<ol>

 <li>py</li>

 <li>py</li>

 <li>txt</li>

 <li>txt</li>

</ol>

Depending on how you organize your code, you may have more files than this.

<h2>Level 3</h2>

In addition to both of the above files, write your own Porter Stemmer.  See <u><a href="https://tartarus.org/martin/PorterStemmer/def.txt">https:// </a><a href="https://tartarus.org/martin/PorterStemmer/def.txt">tartarus.org/martin/PorterStemmer/def.txt</a></u> for the original paper that describes the algorithm in detail.  Your program should remove the tags, tokenize the text, and run it through your porter stemmer before counting the tokens.  It should run using the following command in the terminal:

./my_clean_and_count_stems.py &lt;input_file&gt; &lt;output_file&gt; You may import: sys, re (or regex). You may not use NLTK for any of these steps.

<table width="0">

 <tbody>

  <tr>

   <td width="340">Your full submission should include:</td>

   <td width="283"> </td>

  </tr>

  <tr>

   <td width="340">1.     clean_and_count_tokens.py2.     nltk_clean_and_count_stems.py3.     my_clean_and_count_stems.py4.     lexical_analysis_out.txt</td>

   <td width="283">5.     lexical_analysis_nltk_stemmed_out.txt6.     lexical_analysis_stemmed_out.txt</td>

  </tr>

 </tbody>

</table>

Depending on how you organize your code, you may have more files than this.