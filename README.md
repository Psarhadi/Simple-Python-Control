<h1 align="center">Simple Python and MATLAB for Control Systems Simulation and Data Visualisation: A Side-by-Side Tutorial</h1>


<p align="center">
  <img src="Front_page.png" alt="Figure 1" width="40%">
</p>
This repository provides a simplified approach to learning Python for control system simulation and data visualisation for engineers and researchers coming from a MATLAB background. It uses a novel **side-by-side approach** to achieve a similar level of proficiency in both programming languages for basic tasks. Two main guides are provided:

**A – Installation Guide**  
First, a short note on installing Python and VS Code for development. Any similar IDE, such as Google Colab, can be used instead.

[Download the Installation Guide here](Python_Visual_Studio_Code_Control_Installation_V1.pdf)
* If you already have a Python interpreter installed, you can proceed to the next step. 

**B – Side-by-Side Technical Note**  
The main PDF file includes the side-by-side tutorial with detailed explanations.  

[Download the Python MATLAB Tutorial here](Python%20MATLAB%20Tuturial.pdf)



The PDF includes examples in the following chapters:

1. **Introduction**  
2. **Basic vector and matrix manipulations**  
3. **Basic plotting functions and visualisation**  
4. **Classic linear control system analysis (transfer function)**  
5. **State-space control system design and analysis**  
6. **Control flow statements (loops and conditional statements)**  
7. **Defining functions**  
8. **Differential equation (nonlinear system) simulation**  
9. **Discrete-time control system analysis**  
10. **Data analysis and visualisation**

Together, these Chapters provide the essential knowledge to carry out basic tasks with equivalent proficiency in both programming languages. It assumes that the reader is already familiar with the underlying theory and MATLAB simulations for each topic.


Results for depth tracking over Monte Carlo runs:


Final values for depth and yaw tracking:
<p align="center">
  <img src="images/MCS_CEP.png" alt="Figure 2" width="30%">
</p>

> Feel free to use and amend the code with citation.

> Code by: [Pouria Sarhadi](https://go.herts.ac.uk/pouria-sarhadi).

Further references:

[1]  J. Enayati, P. Sarhadi, et. al., "Monte Carlo Simulation Method for Behavior Analysis of an Autonomous Underwater Vehicle", Proceedings of the IMechE, Part M: Journal of Engineering for the Maritime Environment, Aug. 2016, Vol: 230, No:3, pp: 481-490. 

[2] P. Sarhadi, A. Ranjbar Noei, A. Khosravi, "Adaptive integral feedback controller for pitch and yaw channels of an AUV with actuator saturations", ISA Transactions, November 2016, Vol: 65, pp: 284–295.  

The AUV model/parameters are adapted from:

T. Prestero, "Verification of a six degree of freedom simulation model for the REMUS autonomous under water vehicle", MIT, 2001.

which belongs to the REMUS AUV.
