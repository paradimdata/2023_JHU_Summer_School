### Welcome to the 2023 PARADIM JHU Summer School on [Data Driven Materials Discovery](https://www.paradim.org/2023_JHU_SS)!

[School Agenda Linked Here](https://www.paradim.org/2023_JHU_SS)

###### This repo provides some of the shared resources for the school including notebooks and links used in lectures or for hands-on experiments/investigations.
---
#### A Crashcourse in Building ML Models with Python and Tensorflow
* https://occamy.chemistry.jhu.edu/SS2023

---
#### Some Tool Info to Prepare:

* https://nanohub.org/tools/compphasestab  (Ale’s example: let’s get a Materials Project API Key and run it)
* Install XtalOpt with GULP:
 * XtalOpt install:  http://xtalopt.github.io/download.html
 * GULP :  https://gulp.curtin.edu.au/download.html (pre-built windows exe available on private course page shared with in person attendees)
 * Start XtalOpt!  (For the Mac you may have to control-click to allow it to open since it is a non-registered developer.)
* SciServer JupyterLab:  
  * Make Compute Container
  * Browse to your temporary storage and git clone https://github.com/paradimdata/2023_JHU_Summer_School
  * Try nanoHUB_remote pymnatgen example
  
---
#### Telegrams and Tools Day-by-Day

##### Day 1
1. ML is both revolutionary and evolutionary.  
Transformative tools/Learn from the data
Makes physic-based modeling more accurate/better predictions
2. ML is more about prediction or speed and less about understanding the physics of a system 
3. Small amount of code + FAIR repository +computational platform = scaling from simple to meaningful
go from pencil-and-paper example to all the structures in a repository
Features/Descriptors are high value.
4. Jupyter notebooks for interactive data exploration/visualization; query and computation from repositories; transparency; ubiquitous in data science and AI/ML
5. Major materials data infrastructure: nanoHUB, Materials Project, AFLOW, OpenKIM, OQMD, NREL MatDB

##### Day 2
1. ML can be “black box”   
When is this a problem? When is it not?  How does one use machine learning?
What does it mean if your black box
2. Tools use data. Databases are changing relatively fast.
3. Distance from Convex Hull is important 
3. ML is often split into three types: Clustering, Classification, Regression. What are some problems 
4. Important Databases are the fuel: Materials Project, OQMD, ICSD… make a list! [Check out someone else's list!](https://github.com/tilde-lab/awesome-materials-informatics)  
 * What do we have?
 * What do we need?  
5. Mithrel makes predictions
6. Extrapolation is a central problem. Can we? 
6. Start poking at community databases! You learn by playing.
7. Precision means right or wrong. 
 * Recall is if you find or don't find something in a class. What percentage of true positives are returned correctly?  That's recall. 
 * What proportion of positive identifications is actually correct? That's precision. 
 * A model with no false negatives is recall = 1.0 
 * A model with no false positives is precision = 1.0

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mtext>Precision</mtext>
  <mo>=</mo>
  <mfrac>
    <mrow>
      <mi>T</mi>
      <mi>P</mi>
    </mrow>
    <mrow>
      <mi>T</mi>
      <mi>P</mi>
      <mo>+</mo>
      <mi>F</mi>
      <mi>P</mi>
    </mrow>
  </mfrac>
</math>


---
<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mtext>Recall</mtext>
  <mo>=</mo>
  <mfrac>
    <mrow>
      <mi>T</mi>
      <mi>P</mi>
    </mrow>
    <mrow>
      <mi>T</mi>
      <mi>P</mi>
      <mo>+</mo>
      <mi>F</mi>
      <mi>N</mi>
    </mrow>
  </mfrac>
</math>

---
##### Day 3

1. Convex Hull shows lowest energy configurations of a system of phases. If you want to make something it needs to be on the hull or not far above it.    
 * How well can we compute the convex hull away from the ground state?
2. Informatics makes the jump from computed properties to searching the property space fast and much easier.
3. How do you featurize (fingerprint) something to meet your question?
4. ML works in multiple places in the materials discovery/design workflow!
 * make functionals for DFT
 * as a fast proxy for DFT 
 * to analyze and make predictions from data (including that computed by DFT)
 * Controlling high-throughput experiments (automation and autonomy)
5. Guides when plugging in ML:
 * Use good physical model when you have it; 
 * keep ML as simple as needed; 
 * use explainable ML when possible. 
6. Simple and explainable is always a goal.