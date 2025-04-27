# cmpsc442-homework-6-solved
**TO GET THIS SOLUTION VISIT:** [CMPSC442 Homework 6 Solved](https://www.ankitcodinghub.com/product/cmpsc-442-homework-6-100-points-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123477&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPSC442 Homework 6  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
TO SUBMIT HOMEWORK

To submit homework for a given homework assignment:

1. You *must* download the homework template file from Canvas, located in Files/Homework Templates and Pdfs, and modify this file to complete your homework. Each template file is a python file that will give you a headstart in creating your homework python script. For a given homework number N, the template file name is homeworkN_cmpsc442.py. The template for homework #6 is homework6_cmpsc442.py. IF YOU DO NOT USE THE CORRECT TEMPLATE FILE, YOUR HOMEWORK CANNOT BE GRADED AND YOU WILL RECEIVE A ZERO. There is also a text file in the Canvas assignment page that you will need, called: brown-corpus.txt

Your homework files for every assignment will have the same name, e.g., rjp49.py. IF YOU DO

NOT RENAME YOUR HOMEWORK FILE CORRECTLY, IT WILL NOT BE GRADED AND

YOU WILL RECEIVE A ZERO. Do not be alarmed if you upload a revision, and it is renamed to include a numeric index, e.g., rjp49-1.py or rjp49-2.py. We can handle this automatic renaming.

Instructions

In this assignment, you will gain experience working with hidden Markov models for part-of-speech tagging.

A skeleton file homework6_cmpsc442.py containing empty definitions for each question has been provided. Since portions of this assignment will be graded automatically, none of the names or function signatures in this file should be modified. However, you are free to introduce additional variables or functions if needed.

You will find that in addition to a problem specification, most programming questions also include a pair of examples from the Python interpreter. These are meant to illustrate typical use cases to clarify the assignment, and are not comprehensive test suites. In addition to performing your own testing, you are strongly encouraged to verify that your code gives the expected output for these examples before submitting.

You are strongly encouraged to follow the Python style guidelines set forth in PEP 8, which was written in part by the creator of Python. However, your code will not be graded for style.

1. Hidden Markov Models [95 points]

In this section, you will develop a hidden Markov model for part-of-speech (POS) tagging, using the Brown corpus as training data. The tag set used in this assignment will be the universal POS tag set, which is composed of the twelve POS tags NOUN (noun), VERB (verb), ADJ (adjective), ADV (adverb), PRON (pronoun), DET (determiner or article), ADP (preposition or postposition), NUM (numeral), CONJ (conjunction), PRT (particle), ‘.’ (punctuation mark), and X (other).

As in previous assignments, your use of external code should be limited to built-in Python modules, which excludes packages such as NumPy and NLTK.

1. [10 points] Write a function load_corpus(path) that loads the corpus at the given path and returns it as a list of POS-tagged sentences. Each line in the file should be treated as a separate sentence, where sentences consist of sequences of whitespace-separated strings of the form “token=POS”. Your function should return a list of lists, with individual entries being 2-tuples of the form (token, POS).

&gt;&gt;&gt; c = load_corpus(“brown_corpus.txt”) &gt;&gt;&gt; c = load_corpus(“brown_corpus.txt”)

&gt;&gt;&gt; c[1402] &gt;&gt;&gt; c[1799]

[(‘It’, ‘PRON’), (‘made’, ‘VERB’), [(‘The’, ‘DET’), (‘prospects’, ‘NOUN’),

(‘him’, ‘PRON’), (‘human’, ‘NOUN’), (‘look’, ‘VERB’), (‘great’, ‘ADJ’),

(‘.’, ‘.’)] (‘.’, ‘.’)]

2. [20 points] In the Tagger class, write an initialization method

__init__(self, sentences) which takes a list of sentences in the form produced by load_corpus(path) as input and initializes the internal variables needed for the POS tagger. In particular, if { t1, t2, . . . , tn } denotes the set of tags and { w1, w2, . . . , wm } denotes the set of tokens found in the input sentences, you should at minimum compute:

The initial tag probabilities π(ti) for 1 ≤ i ≤ n, where π(ti) is the probability that a sentence begins with tag ti.

The transition probabilities a(ti → tj) for 1 ≤ i, j ≤ n, where a(ti → tj) is the probability that tag tj occurs after tag ti.

The emission probabilities b(ti → wj) for 1 ≤ i ≤ n and 1 ≤ j ≤ m, where b(ti → wj) is the probability that token wj is generated given tag ti.

It is imperative that you use Laplace smoothing where appropriate to ensure that your system can handle novel inputs, but the exact manner in which this is done is left up to you as a design decision. Your initialization method should take no more than a few seconds to complete when given the full Brown corpus as input.

3. [25 points] In the Tagger class, write a method most_probable_tags(self, tokens) which returns the list of the most probable tags corresponding to each input token. In particular, the most probable tag for a token wj is defined to be the tag with index i* = argmaxi b(ti → wj).

&gt;&gt;&gt; c = load_corpus(“brown_corpus.txt”) &gt;&gt;&gt; c = load_corpus(“brown_corpus.txt”)

&gt;&gt;&gt; t = Tagger(c) &gt;&gt;&gt; t = Tagger(c)

&gt;&gt;&gt; t.most_probable_tags( &gt;&gt;&gt; t.most_probable_tags(

… [“The”, “man”, “walks”, “.”]) … [“The”, “blue”, “bird”, “sings”])

[‘DET’, ‘NOUN’, ‘VERB’, ‘.’] [‘DET’, ‘ADJ’, ‘NOUN’, ‘VERB’]

Computation will likely proceed in two stages: you will first compute the probability of the most likely tag sequence, and will then reconstruct the sequence which achieves that probability from end to beginning by tracing backpointers.

&gt;&gt;&gt; c = load_corpus(“brown_corpus.txt”) &gt;&gt;&gt; c = load_corpus(“brown_corpus.txt”)

&gt;&gt;&gt; t = Tagger(c) &gt;&gt;&gt; t = Tagger(c)

&gt;&gt;&gt; s = “I am waiting to reply”.split() &gt;&gt;&gt; s = “I saw the play”.split()

&gt;&gt;&gt; t.most_probable_tags(s) &gt;&gt;&gt; t.most_probable_tags(s)

[‘PRON’, ‘VERB’, ‘VERB’, ‘PRT’, ‘NOUN’] [‘PRON’, ‘VERB’, ‘DET’, ‘VERB’]

&gt;&gt;&gt; t.viterbi_tags(s) &gt;&gt;&gt; t.viterbi_tags(s)

[‘PRON’, ‘VERB’, ‘VERB’, ‘PRT’, ‘VERB’] [‘PRON’, ‘VERB’, ‘DET’, ‘NOUN’]

2. Feedback [5 points]

1. [1 point] Approximately how long did you spend on this assignment?

2. [2 points] Which aspects of this assignment did you find most challenging? Were there any significant stumbling blocks?

3. [2 points] Which aspects of this assignment did you like? Is there anything you would have changed?
