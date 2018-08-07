BMC
===

Notes on Scientific Computing for Biomechanics and Motor Control  
Marcos Duarte  

This repository is a collection of lecture notes and code on scientific computing and data analysis for Biomechanics and Motor Control. The lectures are written using the [Jupyter Notebook](http://jupyter.org/), part of the [Python ecosystem for scientific computing]( http://scipy.org/). You can view these lectures in different ways: simply read on line by clicking on the links below; or download a single notebook or all the stuff or yet fork this entire repository using the GitHub resources and run the notebooks in your computer or in the cloud.  
I hope this material is useful to you and I am open to suggestions or comments.  

Introduction
------------

* [Biomechanics](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/Biomechanics.ipynb)
* [The Biomechanics and Motor Control Laboratory @ UFABC](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/BMClab.ipynb)

Scientific programming
----------------------

* [Python for scientific computing](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/PythonForScientificComputing.ipynb)  
* [Python tutorial](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/PythonTutorial.ipynb)
* [Version control with Git and GitHub](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/VersionControlGitGitHub.ipynb)
* [Code structure for data analysis](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/CodeStructure.ipynb)

Numerical data analysis
-----------------------

* [Scalar and vector](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/ScalarVector.ipynb)
* [Basic trigonometry](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/TrigonometryBasics.ipynb)
* [Matrix](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/Matrix.ipynb)  
* [Descriptive statistics](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/Statistics-Descriptive.ipynb)  
* [Confidence and prediction intervals](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/ConfidencePredictionIntervals.ipynb)
  * [Prediction ellipse and prediction ellipsoid](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/PredictionEllipseEllipsoid.ipynb)
* [Curve fitting](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/CurveFitting.ipynb)
  * [Polynomial fitting](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/PolynomialFitting.ipynb)
* [Propagation of uncertainty](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/Propagation%20of%20uncertainty.ipynb)
* Frequency analysis  
  * [Basic properties of signals](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/SignalBasicProperties.ipynb)
  * [Fourier series](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/FourierSeries.ipynb)
  * [Fourier transform](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/FourierTransform.ipynb)
* [Data filtering in signal processing](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/DataFiltering.ipynb)
  * [Residual analysis for the optimal cutoff frequency](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/ResidualAnalysis.ipynb)  
* [Ordinary Differential Equation](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/OrdinaryDifferentialEquation.ipynb)  
* [Optimization](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/Optimization.ipynb)  
* Change detection  
  * [Detection of peaks](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/DetectPeaks.ipynb)  
  * [Detection of onset](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/DetectOnset.ipynb)  
  * [Detection of changes using the Cumulative Sum (CUSUM)](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/DetectCUSUM.ipynb)
  * [Detection of sequential data](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/detect_seq.ipynb)
* [Time normalization of data](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/TimeNormalization.ipynb)  
* [Ensemble average](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/EnsembleAverage.ipynb)
* [Open files in C3D format](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/OpenC3Dfile.ipynb)

Mechanics
---------

* **Kinematics**
  * [Frame of reference](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/ReferenceFrame.ipynb)
  * [Kinematics of particle](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/KinematicsParticle.ipynb)  
    * [Projectile motion](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/ProjectileMotion.ipynb)  
    * [Spatial and temporal characteristics](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/SpatialTemporalCharacteristcs.ipynb)  
    * [Minimum jerk hypothesis](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/MinimumJerkHypothesis.ipynb)  
  * [Angular kinematics (2D)](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/KinematicsAngular2D.ipynb)  
    * [Kinematic chain](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/KinematicChain.ipynb)  
  * [Rigid-body transformations (2D)](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/Transformation2D.ipynb)  
  * [Rigid-body transformations (3D)](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/Transformation3D.ipynb)
    * [Determining rigid body transformation using the SVD algorithm](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/SVDalgorithm.ipynb)
* **Kinetics**
  * [Fundamental concepts](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/KineticsFundamentalConcepts.ipynb)
  * [Body segment parameters](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/BodySegmentParameters.ipynb)
  * [Free body diagram](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/FreeBodyDiagram.ipynb)
  * [Biomechanical analysis of vertical jumps](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/VerticalJump.ipynb)
  * [Gait analysis (2D)](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/GaitAnalysis2D.ipynb)
  * Force plates
    * [Kistler force plate calculation](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/KistlerForcePlateCalculation.ipynb)
    * [Zebris pressure platform](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/ReadZebrisPressurePlatformASCIIfiles.ipynb)  
  * [Lagrangian Mechanics](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/lagrangian_mechanics.ipynb)  

Modeling and simulation of human movement
-----------------------------------------

* [Muscle modeling](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/MuscleModeling.ipynb)  
* [Muscle simulation](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/MuscleSimulation.ipynb)  
* [Musculoskeletal modeling and simulation](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/MusculoskeletaModelingSimulation.ipynb)
* [Multibody dynamics of simple biomechanical models](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/MultibodyDynamics.ipynb)

Stabilography
-------------

* [The inverted pendulum model of the human standing posture](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/IP_Model.ipynb)
* [Measurements in stabilography](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/Stabilography.ipynb)  
* [Rambling and Trembling decomposition of the COP](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/IEP.ipynb)

Electromyography
---------------

* [Introduction to data analysis in electromyography](http://nbviewer.jupyter.org/github/demotu/BMC/blob/master/notebooks/Electromyography.ipynb)

How to cite this work
---------------------

Here is a suggestion to cite this GitHub repository:

> Duarte, M. (2015) Notes on Scientific Computing for Biomechanics and Motor Control. GitHub repository, https://github.com/demotu/BMC.  

And a possible BibTeX entry:

```tex
@misc{Duarte2015,  
    author = {Duarte, M.},  
    title = {Notes on Scientific Computing for Biomechanics and Motor Control},  
    year = {2015},  
    publisher = {GitHub},  
    journal = {GitHub repository},  
    howpublished = {\url{https://github.com/demotu/BMC}}  
}  
```

License
-------

The non-software content of this project is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/), and the software code is licensed under the [MIT license](https://opensource.org/licenses/mit-license.php).
