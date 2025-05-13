# dasc521-homework-8-expectation-maximization-clustering-solved
**TO GET THIS SOLUTION VISIT:** [DASC521 Homework 8-Expectation-Maximization Clustering Solved](https://www.ankitcodinghub.com/product/dasc521-homework-8-expectation-maximization-clustering-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92734&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DASC521 Homework 8-Expectation-Maximization Clustering Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

In this homework, you will implement an expectation-maximization (EM) clustering algorithm in Python. Here are the steps you need to follow:

1. You are given a two-dimensional data set in the file named hw08_data_set.csv, which contains 1000 data points generated randomly from nine bivariate Gaussian densities with the following parameters.

</div>
</div>
<div class="layoutArea">
<div class="column">
𝜇 = #+5.0( , ! +5.0

𝜇” = #−5.0( , +5.0

𝜇# = #−5.0( , −5.0

𝜇$ = #+5.0( , −5.0

𝜇% = #+5.0( , +0.0

𝜇&amp; = #+0.0( , +5.0

𝜇’ = #−5.0( , +0.0

𝜇( = #+0.0( , −5.0

𝜇) = #+0.0( , +0.0

</div>
<div class="column">
Σ !

Σ” Σ# Σ$ Σ% Σ&amp; Σ’ Σ(

Σ)

</div>
<div class="column">
= #+0.8 −0.6 = #+0.8 +0.6 = #+0.8 −0.6 = #+0.8 +0.6 = #+0.2 +0.0 = #+1.2 +0.0 = #+0.2 +0.0 = #+1.2 +0.0 = #+1.6 +0.0

</div>
<div class="column">
−0.6( ,

+0.8 !

</div>
</div>
<div class="layoutArea">
<div class="column">
The given data points are shown in the following figure.

</div>
</div>
<div class="layoutArea">
<div class="column">
+0.6( , +0.8 −0.6( , +0.8 +0.6( , +0.8 +0.0( , +1.2 +0.0( , +0.2 +0.0( , +1.2 +0.0( , +0.2 +0.0( , +1.6

</div>
<div class="column">
𝑁 = 100 𝑁” = 100 𝑁# = 100 𝑁$ = 100 𝑁% = 100 𝑁&amp; = 100 𝑁’ = 100 𝑁( = 100

𝑁) = 200

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2. To initialize your EM algorithm, you should take the centroids given in the file named hw08_initial_centroids.csv as the initial values for the mean vectors. By assigning the data points to the nearest center, estimate the initial covariance matrices and prior probabilities in your EM algorithm. (20 points)

3. After the initialization step, run your EM algorithm for 100 iterations. Report the mean vectors your EM algorithm finds. Your results should be like the following matrix. (50 points)

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>print(means)
</pre>
<pre>[[-4.9508988  -4.98464367]
 [-4.85629614  0.0404331 ]
 [-4.96379877  4.984647  ]
 [ 0.02477868 -5.09014979]
 [-0.09548618 -0.116943  ]
 [-0.03701877  4.91812108]
 [ 5.00933942 -5.02595861]
 [ 4.99839618  0.13777844]
 [ 4.96705774  4.97185503]]
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
4. Draw the clustering result obtained by your EM algorithm by coloring each cluster with a different color. You should also draw the original Gaussian densities you use to generate data points and the Gaussian densities your EM algorithm finds with dashed and solid lines, respectively. Draw these Gaussian densities where their values are equal to 0.05. Your figure should be like the following figure. (30 points)

</div>
</div>
</div>
