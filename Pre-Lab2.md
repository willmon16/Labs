# Lab 2 - Intro to Curve Fitting (Scipy/Numpy) and Plotting (Matplotlib)

##  The Photoelectric Effect, Radioactive Decay, and Projectile Motion
------------------------------------------------------------------------------------------------
## Learning Goals

### Physics/Computing (Curve Fitting) Goals

#### Photoelectric Effect
1.  Describe the experiment performed by Millikan, including the data collected, in your own words.
2.  Describe the model proposed by Einstein, and how it is used to fit Millikan's data.

#### Projectile Motion: Review the basics of 2D projectile motion 

#### Radioactive decay: Review the basics of radioactive decay 

#### Curve-Fitting 
1.  Apply your least squares fit algorithm to appropriate data sets
2.  Evaluate utility of existing software and libraries - (scipy.curvefit)
3.  Apply appropriate fits to Projectile Motion and Radioactive Decay.

### Coding Basics

1.  Apply standard coding concepts (control logic, loops) in order to solve physics problems with a modular design (functions)
2.  Check basic physical principles (energy is conserved, physical bounds are respected)
3.  Catch typical implementation problems / Isolate errors with code testing

### Analyze and present data
1. Generate clear figures from model data
2. Use visualization to analyze results
3. Draw conclusions based on numerical results
4. Use visualization tools to present a compelling case
------------------------------------------------------------------------------------------------

## Pre-Lab Exercises

### Reading Assignment
1.  The lab learning objectives (note the ones related to Millikan)
2.  Read the linked article: [History of the Oil Drop Experiment](https://www.aps.org/publications/apsnews/200608/history.cfm) 
3.  Read Newman Exercise 3.8 - Least-squares fitting and the photoelectric effect 
4.  (Not required:) If you're really interested, you can read Millikan's original 1913 paper.  It is available through its original publisher - [the Physical Review](https://journals.aps.org/pr/abstract/10.1103/PhysRev.2.109) 

### Questions/Exercises
1. Unless you do everything by hand (which is an option), make a Jupyter Notebook - Pre-Lab2.ipynb to start your work below.    

2. Based on the reading, describe the photoelectric effect.  Be sure to address the student learning objectives listed above.

3.  Prove (by hand) Newman's equations for the least squares fit.  You are welcome to write up your proof in Markdown, but that is not necessary.  Here is a useful [link](http://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Typesetting%20Equations.html).

4.  Write out a planned pseudocode to solve Exercise 3.8 (you can mock it up on paper, Markdown, or python with many comments) to do the the exercise.  A few suggestions/additions:

    1.  Make sure to use good programming style as laid out by Newman (section 2.7) - be sure to use a function to do the least squares fit - we will be reusing that function in lab to fit other data.
    2.  Calculate the percent difference between Planck's constant and the accepted value
    3.  In part (c), you can use a different method than Newman's suggestion.  
      * I defined a linspace over the range of $\nu$ values
      * I used numpy arithmetic to calculate a corresponding set of $V$ values
      * I plotted a line from those two arrays.
      
5.  Submitting your work: 
    * Bring your handwritten documents to lab (I'll check them off and give them back to you) 
    * Submit any Markdown/Jupyter Notebook you create in the usual spot - your private repository on Physics-PacU.

For your plots (when you make them in lab): 
*  Be sure to add sensible labels - especially the x and y axes labels.  
*  Including a legend is a nice touch - see [link](https://matplotlib.org/gallery/lines_bars_and_markers/scatter_with_legend.html#sphx-glr-gallery-lines-bars-and-markers-scatter-with-legend-py) or [link](https://matplotlib.org/gallery/text_labels_and_annotations/legend_demo.html#sphx-glr-gallery-text-labels-and-annotations-legend-demo-py) for examples.
------------------------------------------------------------------------------------------------
Note that you will be graded based on the learning objectives, so plan to use your data to tell a scientific story.
