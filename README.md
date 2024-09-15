# About me
I'm a mathematics master's student.
Having completed an undergraduate degree in **applied math** with a concentration in data science and machine learning, I enjoy all things math and programming.

# Personal projects

## multi-DimPy ([pip](https://pypi.org/project/multi-dimpy/) and [source](https://github.com/schilln/multi-dimpy/tree/main))

Everyone knows you can't add apples and oranges.<br>
Most people also know you can't add meters and seconds.<br>
But sometimes people do—accidentally, when it's hidden in code or in matrix computations.

Models and algorithms with dimensional inconsistencies might still yield decent results, but they don't make physical sense, and a change of units results in a change to the output, when units shouldn't make a difference.

Software packages for managing dimensions already exist, but they lack the ability to do **dimensioned linear algebra**—they mostly just work with scalar values.
So as a first go and a proof-of-concept, I'm developing a package that wraps NumPy and tracks physical dimensions of $n$-dimensional arrays using theory developed in the book *Multidimensional Analysis* (see citation below).

The project is in its early stages, but so far it's been an invaluable experience both in mathematics and in software development.
See the "develop" branch in the source repository for more recent work.

(Hart, G. W. (1995). Multidimensional Analysis: Algebras and Systems for Science and Engineering. Springer-Verlag.)


## CAD (computer-aided design)
What do you get when you combine **3D modeling** with **math and programming**?
Onshape's *FeatureScript*.<br>
Check out these projects I coded:

- [Icosahedron](https://cad.onshape.com/documents/21fe442c6fdbdcc9cb2b762c/w/619a021ea6ad2afa637303f4/e/aff030f8e2b8273743bfc213) (a 20-sided regular polyhedron with triangle faces)
- [Customizable 3D-printable name plaque](https://cad.onshape.com/documents/08b419c7da1909c559eabade/w/1ad50dfb376ded4ce8ed581e/e/6325e3273e6240fbe1433c1f) (to create your own plaque, create a free account and copy the document, then simply enter your name)
- [Customizable microscope slide drying stand](https://cad.onshape.com/documents/536a36b569d229831fe86d98/w/e6635d88101c4c250cab12e7/e/592906cbd2fa5daeac849e62) (again, use a free account to copy the document and customize)

I also enjoy 3D modeling without any coding.
Check out these other projects I've worked on:

- [3D-printed cello](https://www.thingiverse.com/thing:6687761) (modified from another creator's original design)
- [iPhone case with cello cutout](https://www.thingiverse.com/thing:2626807)

# School projects

## Modeling and altering the Sun's gravity ([paper](papers/2023_A_Space_ODE-ssey.pdf))

We take for granted Newton's laws of motion and his universal law of gravitation.
To help us learn about **ordinary differential equations** (in preparation for studying partial differential equations and optimal control), some fellow students and I wondered, What happens if we *change* the law of gravitation?
This paper is the result!
(Along with some other experiments.)

## Classifying and forecasting sleep states using brain waves ([paper](papers/Do_UMAP_when_you're_tired.pdf))

Sleep researchers have identified various stages of sleep.
When a patient's sleep stages are of interest, researchers typically record the patient's brain waves and annotate them with sleep stages by hand.
To practice our skills with **machine learning methods**, fellow students and I employed various models (including the Kalman filter, reservoir computing, and more) to do the same.

## Optimal freeway on-/off-ramp control ([paper](papers/Poptimal_freeway_corntrol.pdf))

No one enjoys driving in traffic.
While it's a reality of a growing populace, good traffic signaling should be able to help.
As part of our study of optimal control, some classmates and I modeled freeway on- and off-ramps using differential equations and then utilized various **optimal control techniques** to manage traffic flow.
Though certainly a few steps removed from managing any real vehicles, preliminary results suggest our optimal control approach works!
(According to our model, of course.)
Moreover, we learned a lot about optimal control—and developed a greater appreciation for those who *do* strive to combat congestion with traffic controls.

## Why does everyone use the dot product in neural nets? ([paper and code](https://github.com/schilln/word-embeddings))

The vector dot product $\mathbf v_1 \cdot \mathbf v_2$ is used almost everywhere in current neural network research and in production models.
It provides one measure of *similarity* between data points—but it's not the only one.
Cosine similarity (essentially a normalized dot product) and distance under a norm $\lVert \mathbf v_1 - \mathbf v_2 \rVert$ provide similar functionality.
Why is the dot product preferred?

In this paper I investigate the effect on one model's performance of each of these measures of similarity to either **validate** or **challenge** the popular usage of the dot product.

## Analyzing neural net loss surfaces in "dataspace" ([paper and code](https://github.com/schilln/loss-surfaces-in-data))

Traditional deep learning research often examines a model's loss surface in "weightspace"—one measures how the loss changes on a dataset as the parameters, or weights, vary.
Many researchers believe that "flat minimizers" of the loss surface correspond to better generalization, or performance of the model on unseen data.
However, good generalization actually consists of flat minimizers in *dataspace*, not weightspace.
That is, a small variation in data—such as the difference between unseen data and training data—should not lead to a significant decrease in model performance.

To that end, in this project I make a first attempt at answering the question, How do loss surfaces in weightspace compare with those in dataspace?
An answer to this question could **justify** or **refute** the claim that "flat minimizers" in weightspace correspond to good generalization.

## ACME (Applied and Computational Mathematics Emphasis)
This is the full name of my undergraduate major along with its handy acronym.
It's a blend of **math**, **computer science**, and **statistics**, with the goal of understanding, designing, and implementing optimization algorithms and machine learning.

Please message me (e.g. on LinkedIn, linked on my profile) for access to my ACME repository which contains my work on coding labs and will be updated with additional work from time to time.
