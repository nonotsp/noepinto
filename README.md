# Hello, I'm Noé 👋

Second-year engineering student at [Télécom SudParis](https://www.telecom-sudparis.eu/en/), passionate about finance, data, and algorithms.  
Currently building a strong background in statistics, optimization, and software engineering through personal and academic projects.

<!-- Optional: Add a link to your CV -->
<!-- [My CV](https://example.com/cv.pdf) -->

---

>  **How to reach me**: [noe.pinto@telecom-sudparis.eu](mailto:noe.pinto@telecom-sudparis.eu)  
>  or via [LinkedIn](https://www.linkedin.com/in/noé-pinto-a6b952301/)

---

In addition to coursework, I’ve been actively exploring quantitative finance, algorithmic trading, and responsible computing through hands-on projects.

Feel free to check out some of my work below 👇

---

###  [Mini-Facebook](https://github.com/nonotsp/mini-facebook)

A minimalist social network implemented in Bash.  
Users can create accounts, add friends, post messages, and view their wall.  
Designed to explore process synchronization and interprocess communication with named pipes.

> `Bash • IPC • Process Synchronization • Systems Programming`


---

### [Order Book Simulator](https://github.com/nonotsp/order-book-simulator)

**Order Book Simulator** is a Java-based simulation of a financial order book, supporting both market and limit orders.  
This project was built as part of my academic and personal work during my second year at Télécom SudParis.

## About the Project

This simulator models a central limit order book, matching buy and sell orders using price and FIFO priority.  
It supports:

-  Limit orders (BUY / SELL)
-  Market orders (BUY / SELL)
-  FIFO matching (First-In-First-Out)
-  Order book visualization (terminal view) *(new)*
-  CSV-based execution (stream of orders) *(new)*
-  Multi-order processing via algorithmic runner *(new)*


### 1. Clone the repo

```bash
git clone https://github.com/nonotsp/order-book-simulator.git
cd order-book-simulator
```
### 2. Compile the project

```bash
javac src/*.java
```


### 3. Run the simulation

```bash
java src.Main
```
It will read and execute orders from the orders.csv file.

---

### [Kalman Filtering – Target Tracking](https://github.com/nonotsp/kalman-tracking-project)

Kalman Filtering applied to the estimation of object trajectories from noisy sensor data.  
Developed during the *Statistical Filtering* course at Télécom SudParis, this project includes both synthetic simulations and real-world applications (e.g., aircraft tracking).

## About the Project

The goal is to estimate the position and velocity of a moving target using probabilistic state-space models.  
The project is divided into three main parts:

- **Synthetic Scenario** – Simulation of a mobile object and reconstruction via standard Kalman Filter  
- **Aircraft Tracking** – Application to real 2D trajectory data with missing observations  
- **Extended Kalman Filter (EKF)** – Adaptation to nonlinear polar observations (angle and distance)

Includes a full implementation from scratch, error analysis, and performance visualization.

> `Python • State-Space Models • Kalman Filter • EKF • Signal Processing

---

### [Particle Filtering – Object Tracking](https://github.com/nonotsp/particle-filtering-project)

Implementation of a particle filter to estimate hidden states in non-linear and/or non-Gaussian models.  
Developed during the *Statistical Filtering* course at Télécom SudParis, this project includes:
- a benchmark model from econometrics (Kitagawa),
- and a face tracking system based on color histograms from a video sequence.

## About the Project

The goal is to estimate the hidden state \( X_n \) from sequential noisy observations \( Y_n \), using a particle approximation of the posterior distribution.

The project is divided into two main parts:

- **Kitagawa Model (Econometrics)**  
  A nonlinear state-space model used to test filtering performance.  
  Includes particle filtering with resampling and analysis of estimation error under varying parameters.

- **Face Tracking (Computer Vision)**  
  Applies particle filtering to image sequences using a histogram-based observation model.  
  Each particle defines a candidate position for the tracked object, and its weight is based on color similarity.

Features include:
- Adaptive tracking with resampling
- Estimation of position in image frames
- Real-time trajectory visualization

> `Python • Particle Filter • Sequential Monte Carlo • Image Processing • Computer Vision`
