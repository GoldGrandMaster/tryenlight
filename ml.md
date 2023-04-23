---
layout: page
title: Learn Machine Learning
description: Resources to educate developers on the realms of machine learning.
color: blue
---

<article class="pa1 pa2-ns">
	<h1 class="f4 bold mw6">Table of Contents</h1>
	<ul class="list pl0 ml0 mw6 ba b--light-silver br2">
		<li class="ph3 pv3 bb b--light-silver">
			<a href="#start">Intro to Machine Learning</a>
		</li>
		<li class="ph3 pv3 bb b--light-silver">
			<a href="/neural-network">Build a Neural Network</a>
		</li>
		<li class="ph3 pv3 bb b--light-silver">
			<a href="/stock-market-prediction">Build a Stock Prediction Algorithm</a>
		</li>
		<!-- <li class="ph3 pv3 bb b--light-silver">
			<a href="#">Building a Classification Model</a>
		</li> -->
	</ul>
</article>

<h1 class="f2 bold mw6" id="start">An Introduction to Machine Learning</h1>
<p>Machine Learning itself is an umbrella that covers a vast number of uses and applications, just like Computer Science. It's is a topic that has been gaining a lot of interest for the past decade. The stigma is that it is often associated with page-long computations. Thankfully, that's mostly been eliminated with a bunch of frameworks like <a href="http://scikit-learn.org/stable/">scikit-learn</a>. However, as my friend <a href="https://kabir.ml">Kabir</a>, likes to say:<b> "I think it is just as important to know what exactly goes on under the hood."</b></p>
<p>Defined by Arthur Samuel in 1959, Machine Learning gives "computers the ability to learn without being explicitly programmed." In other words, the computer teaches itself. How?, you may ask. Well, Machine Learning, a subset of AI, uses algorithms and specific models to analyze and train data. This includes the Neural Network, a system that takes several inputs, and produces a single output. Based on the fundamental network of the human brain, the interconnected web of neurons transmitting patterns of electrical signals are what Artifical Neural Networks attempt to mimic. </p>
<div class="pa4">
	<blockquote class="athelas ml0 mt0 pl4 black-90 bl bw2 b--navy">
		<p class="f5 f4-m f3-l lh-copy measure mt0">A computer program is said to learn from experience E with respect to some task T and some performance measure P if its performance on T, as measured by P, improves with experience E.</p><cite class="f6 ttu tracked fs-normal">―Tom Mitchell, Carnegie Mellon University</cite>
	</blockquote>
</div>
<p>In the quote above, Machine Learning is described at the fundamental level. Say you have a task (T) such as predicting stock prices. In this case, experience (E) is your data set, and the performance (P) is your accuracy of which the algorithm learns from.</p>
<p>The thing is, machines aren't human. Sure, a computer can calculate the square root of 603,729, but can it discriminate between a fish and a bird? For these tasks, machine learning is essential.</p>
<p>Neural Networks, at the core, are algorithms that are <i>adaptable</i>, which therefore allow it to <i>learn</i>. Most of the time, this is done by adjusting the <b>weights</b>. If the network produces a desired output, the weights are not adjusted. However, if the network produces an undesired, or "poor" output, the system will adapt and alter the weights in order to imrpove results.</p>
<p>There are three types of learning:</p>
<ol>
	<li><b>Supervised Learning</b>: This type of learning involves training and testing the network with the answers, which the network uses to make adjustments and recognize a pattern.<br></li>
	<li><b>Unsupervised Learning</b>: This type of learning is used when there are no answers available, and the network has to search for a hidden pattern in the data.<br></li>
	<li><b>Reinforcement Learning</b>: This type of learning develops patterns, and then relearns based on the outcomes of the test. In essense, the machine learns from its prior outcomes.</li>
</ol>
<p>The output of a dataset (label) rely on the input (features) and the model that is being used. In fact, the more features you have, the better. This is because you give the model more data to work with, which leads to more accurate labels. Here are some examples of machine learning models: </p>

<ol>
	<li><b>Classification</b>: Is this a cat or a dog?<br></li>
	<li><b>Regression</b>: What will be APPL's stock price tomorrow?<br></li>
	<li><b>Clustering</b>: Is the color of this car red, blue, or green? </li>
</ol>

<p>Now that we've got a brief overview. Let's head over and build some projects!</p>


<a class="f2 fw7 dib no-underline" href="/neural-network">Build a Feedforward Neural Network</a> <br><br>
<a class="f2 fw7 dib no-underline" href="/stock-market-prediction">Build a Stock Prediction Algorithm</a>
