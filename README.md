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

### Example CSV

TYPE,SIDE,QUANTITY,PRICE
LIMIT,BUY,5,4.00
LIMIT,SELL,4,5.00
MARKET,SELL,3,
LIMIT,BUY,2,5.20
MARKET,BUY,3,
