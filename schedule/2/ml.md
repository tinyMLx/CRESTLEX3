# How Machine Learning Works
{:.no_toc}

* TOC
{:toc}

## Introduction to Machine Learning (and Review of AI)
Welcome back!  Yesterday, we experimented with artificial intelligence (AI), which was a set of techniques our computers use to act on their own, making decisions much like us humans would.  We saw examples of **classification** and **prediction** which all went a step further into AI and used **machine learning**.

**Machine learning** is a way in which computers learn 👨🏾‍🏫 rules on their own using historical **data** to train, practice, and then make predictions.  Today, we'll explore further just how computers *learn*.  We'll relate the process to human anatomy, our brain 🧠 and **neurons**, and we'll talk about how we can help computers practice and learn by providing strong 💪 and diverse 🌎 datasets!

<a class="d-block mb-1 small text-end text-muted" href="{{'/schedule/2/ml/intro.pdf' | relative_url }}" target="_blank">
    Open
    <i class="fas fa-external-link-alt ms-1"></i>
</a>
<div class="border border-1 border-dark ratio ratio-85x110 mt-1">
    <iframe id="pdf-js-viewer" src="{{ site.baseurl }}/web/viewer.html?file={{'/schedule/2/ml/intro.pdf' | relative_url }}" title="webviewer" frameborder="0" width="500" height="600"></iframe>
</div>

<br><br>

## Machine Learning is Different
Unlike traditional programming where we provide *all* of the **explicit** rules to the computer, machine learning is rooted in the idea that computers can learn the rules for themselves (with a few hints from us, of course).  This way, we don't have to think up every different possible input.  Our trained **model** can make best guesses on its own, using rules it created!

<a class="d-block mb-1 small text-end text-muted" href="{{'/schedule/2/ml/paradigm.pdf' | relative_url }}" target="_blank">
    Open
    <i class="fas fa-external-link-alt ms-1"></i>
</a>
<div class="border border-1 border-dark ratio ratio-85x110 mt-1">
    <iframe id="pdf-js-viewer" src="{{ site.baseurl }}/web/viewer.html?file={{'/schedule/2/ml/paradigm.pdf' | relative_url }}" title="webviewer" frameborder="0" width="500" height="600"></iframe>
</div>

<br><br>


## Models and Training
A **model** is at the heart of any machine learning application.  It's the framework the system use for making *inferences* (or predictions).  Because our machine learning model is used for artificial intelligence (used to mimic a human), it's structure is a lot like our human anatomy.  In fact, like our brain 🧠, we use **neurons** and **neural networks** in our machine learning models.

To make machine learning work, our models need to be **trained**.  We give them "practice problems" and then let the models guess and check, learning and improving along the way (very similar to the process you might use to study for a test)!

<a class="d-block mb-1 small text-end text-muted" href="{{'/schedule/2/ml/training.pdf' | relative_url }}" target="_blank">
    Open
    <i class="fas fa-external-link-alt ms-1"></i>
</a>
<div class="border border-1 border-dark ratio ratio-85x110 mt-1">
    <iframe id="pdf-js-viewer" src="{{ site.baseurl }}/web/viewer.html?file={{'/schedule/2/ml/training.pdf' | relative_url }}" title="webviewer" frameborder="0" width="500" height="600"></iframe>
</div>

<br><br>


## Transforming our Inputs
There are only certain ways our model can accept inputs!  It's on us to make sure the data inputs are structured in a friendly format for our model.  We **flatten** and apply **filters** to our inputs to help pick out the important **features** that our model might want to see 👀 when making a prediction. 

<a class="d-block mb-1 small text-end text-muted" href="{{'/schedule/2/ml/filter.pdf' | relative_url }}" target="_blank">
    Open
    <i class="fas fa-external-link-alt ms-1"></i>
</a>
<div class="border border-1 border-dark ratio ratio-85x110 mt-1">
    <iframe id="pdf-js-viewer" src="{{ site.baseurl }}/web/viewer.html?file={{'/schedule/2/ml/filter.pdf' | relative_url }}" title="webviewer" frameborder="0" width="500" height="600"></iframe>
</div>

<br><br>


## Data, Data, Data!
Our machine learning application and the model at the heart of our system is only as good as its training **data**, similar to the way you can speak one language, but probably can't understand too many others!  Luckily, we can get data from lots of **sensors** in the world!  As more and more of our devices become *smart* and connected, there's more data to collect!  But we have to make sure that the data is **clean**, well-managed, labeled **correctly**, and from a **diverse** background (that means lots of different inputs from lots of different people).  Otherwise, our systems could have **bias**, which isn't fair to some people :(

We also have to watch out for **overtraining** where our model only becomes good at identifying the inputs it's already seen and nothing else!  

<div class="message">
This is <b>a lot</b> to think about, and it's one of the biggests challenges in ML today!
</div>

<a class="d-block mb-1 small text-end text-muted" href="{{'/schedule/2/ml/data.pdf' | relative_url }}" target="_blank">
    Open
    <i class="fas fa-external-link-alt ms-1"></i>
</a>
<div class="border border-1 border-dark ratio ratio-85x110 mt-1">
    <iframe id="pdf-js-viewer" src="{{ site.baseurl }}/web/viewer.html?file={{'/schedule/2/ml/data.pdf' | relative_url }}" title="webviewer" frameborder="0" width="500" height="600"></iframe>
</div>

<br><br>

## The Machine Learning Workflow
Let's review everything we need to know for building a machine learning application, from start to finish!

<a class="d-block mb-1 small text-end text-muted" href="{{'/schedule/2/ml/workflow.pdf' | relative_url }}" target="_blank">
    Open
    <i class="fas fa-external-link-alt ms-1"></i>
</a>
<div class="border border-1 border-dark ratio ratio-85x110 mt-1">
    <iframe id="pdf-js-viewer" src="{{ site.baseurl }}/web/viewer.html?file={{'/schedule/2/ml/workflow.pdf' | relative_url }}" title="webviewer" frameborder="0" width="500" height="600"></iframe>
</div>

<br><br>


## Agenda for the Afternoon

<a class="d-block mb-1 small text-end text-muted" href="{{'/schedule/2/ml/agenda.pdf' | relative_url }}" target="_blank">
    Open
    <i class="fas fa-external-link-alt ms-1"></i>
</a>
<div class="border border-1 border-dark ratio ratio-85x110 mt-1">
    <iframe id="pdf-js-viewer" src="{{ site.baseurl }}/web/viewer.html?file={{'/schedule/2/ml/agenda.pdf' | relative_url }}" title="webviewer" frameborder="0" width="500" height="600"></iframe>
</div>