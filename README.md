# csci4390-6390-homework-1-covariance-and-eigenvectors-solved
**TO GET THIS SOLUTION VISIT:** [CSCI4390-6390 Homework 1-Covariance and Eigenvectors Solved](https://www.ankitcodinghub.com/product/csci4390-6390-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92555&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI4390-6390 Homework 1-Covariance and Eigenvectors Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Part I (both CSCI-4390 and CSCI-6390):

a. Mean vector and total variance

Compute the mean vector μ for the data matrix, and then compute the total variance var(D); see Eq. (1.8) for the latter. b. Covariance matrix (inner and outer product form)

Compute the sample covariance matrix Σ as inner products between the attributes of the centered data matrix (see Eq. (2.38) in chapter compute the sample covariance matrix as sum of the outer products between the centered points (see Eq. (2.39)).

c. Correlation matrix as pair-wise cosines

Compute the correlation matrix for this dataset using the formula for the cosine between centered attribute vectors (see Eq. (2.30)). Output which attribute pairs are i) the most correlated, ii) the most anti-correlated, and iii) the least correlated?

Create the scatter plots for the threee interesting pairs using matplotlib and visually confirm the trends, i.e., describe how each of the three results in a particular type of plot.

Part II: Eigenvectors (50 Points) CSCI-4390 Only: Dominant Eigenvector

Compute the dominant eigenvalue and eigenvector of the covariance matrix Σ via the power-iteration method. One can compute the dom vector/-value of the covariance matrix iteratively as follows.

</div>
</div>
<div class="layoutArea">
<div class="column">
Let

</div>
</div>
<div class="layoutArea">
<div class="column">
⎛⎜1⎞⎟ x 0 = ⎜ ⎜⎝ 1 ⋮ ⎟ ⎟⎠

xi = Σ xi−1

We then find the element of xi that has the maximum absolute value, say at index m. For the next round, to avoid numerical issues with la

we re-scale xi by dividing all elements by xim, so that the largest value is always 1 before we begin the next iteration.

To test convergence, you may compute the norm of the difference between the scaled vectors from the current iteration and the previous o

can stop if this norm falls below some threshold. That is, stop if

∥xi − xi−1∥2 &lt; ε For the final eigen-vector, make sure to normalize it, so that it has unit length.

</div>
</div>
<div class="layoutArea">
<div class="column">
be the starting vector in Rd, where d is the number of dimensions. In each iteration i, we compute the new vector:

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
x

</div>
</div>
<div class="layoutArea">
<div class="column">
p

p

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
<div class="layoutArea">
<div class="column">
i

</div>
</div>
<div class="layoutArea">
<div class="column">
r

n

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Also, the ratio xim gives you the largest eigenvalue. If you did the scaling as described above, then the denominator will be 1, but the n xi−1,m

will be the updated value of that element before scaling.

Once you have obtained the dominant eigenvector, u1, project each of the original data points xi onto this vector, and print the coordinat new points along this “direction”.

CSCI-6390 Only: First Two Eigenvectors and Eigenvalues

Compute the first two eigenvectors of the covariance matrix Σ using a generalization of the above iterative method.

Let X0 be a d × 2 (random) matrix with two non-zero d-dimensional column vectors with unit length. We will iteratively multiply X0 the left.

The first column will not be modified, but the second column will be orthogonalized with respect to the first one by subtracting its projecti the first column (see section 1.3.3 in chapter 1). That is, let a and b denote the first and second column of X1, where

</div>
</div>
<div class="layoutArea">
<div class="column">
X1 = Σ X0

b = b − ( bT a ) a

Before the next iteration, normalize each column to be unit length, and repeat the whole process. That is, from X1 obtain X2 and so on, convergence.

To test for convergence, you can look at the distance between Xi and Xi−1. If the difference is less than some threshold ε then we stop. Once you have obtained the two eigenvectors: u1 and u2, project each of the original data points xi onto those two vectors, to obtain the

projected points in 2D. Plot these projected points in the two new dimensions. Submission

Submit your code via submitty. Name your python script: assign1.py.

Your script will be run as follows:

assign1.py FILENAME EPS

Here FILENAME is the name of the input CSV file, EPS the convergence threshold ε for the eigen-vector/-value computation.

You may assume that the input CSV data file energydata_complete.csv resides in the local directory where the script will be called from. epsilon as 0.001 or 0.0001. You may find the pandas read_csv function useful to read the CSV file.

Save all your output to a pdf file named assign1.pdf. The output should comprise the mean vector, total variance, covariance matrix via in outer product formulas, correlation matrix, the observations, the dominant eigen-vectors and eigenvalues. The scatter plots should also be output file as well, with any required comments. You will lose points if you do not include the output PDF file.

Note that since there are &gt;19k points, you should not print out the full eigenvectors. Just print out the first 10 and last ten values per eigen

Your script must use Python version 3. Please note that you can use built-in NumPy/Python functions for reading and parsing the text inpu should NOT use any of the built-in functions like cov or eigen for this assignment. You may however verify your answers by comparing t from the built-in methods.

Tutorial on Python and NumPy

For those not that familiar with pythoni or NumPy, you may search online for tutorials, e.g. https://docs.python.org/3/tutorial/ or https://numpy.org/doc/stable/

</div>
</div>
</div>
</div>
