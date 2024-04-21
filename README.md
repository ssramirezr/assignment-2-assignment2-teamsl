[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ktyD1gKg)
<h1 align="center">
    <tt>> ST0270 Formal Languages and Compilers
Assignment 2 </tt> :chess_pawn:
</h1>

### Names: 
- Lina Sofía Ballesteros Merchán
- Santiago Alvarez Díaz

Development of the proposed activity for the subject of Formal Languages and Compilers taught at EAFIT University by prof Sergio Ramírez. Given a context-free grammar G = (N,Σ,P,S) in Chomsky normal form (CNF) and a string x ∈ Σ∗ , the CKY algorithm decides whether or not x ∈ L(G).

## About
- The program was executed on Windows OS.
- The chosen language was Python.
- A libray called [Tabulate](https://pypi.org/project/tabulate/) was used to visualize the behavior of the CYK algorithm, it is optional to test this feature.
- The code editor used was Visual Studio Code.

## Installing Requirements

Follow these instructions to run the program:

1. Clone the project on your machine or download the ZIP file.

    ```bash
    git clone https://github.com/ssramirezr/assignment-2-assignment2-teamsl.git
    ```
2. Go to the project directory (or wherever you stored it).

    ```bash
    cd assignment2
    ```
  
3. Make sure you have Python. Now you are ready to run the program.
  
    ```bash
    python --version

    ```
4. **(Optional Step)** As mentioned in the About section above, in this work we used a library called Tabulate that allows tables to be printed in a more readable and understandable format. During the execution of this work, this visualization of the table allowed us to check the operation of the CYK algorithm. If you are interested in seeing the behavior of the algorithm through these tables, you can install Tabulate with `pip` and follow the instructions down below. However, it is **not a mandatory requirement** to test the program and is completely optional. 

    ```bash
    pip install tabulate
    ```
After installing Tabulate, uncomment these lines of code and run the program.

 ```bash
    in line 1 from tabulate import tabulate # library to print the table
    in line 23 print(tabulate(table, tablefmt="fancy_grid"))
    in line 51 print(tabulate(table, tablefmt="fancy_grid"))
 ```
An example of the table visualization:

![image](https://github.com/ssramirezr/assignment-2-assignment2-teamsl/assets/140737132/71f2f38b-3ef8-497c-8a7b-3490dafd68c8)

----------------------
## Run the Program

1. Go to the project directory in your code editor or terminal:
   
    ```bash
    
    cd assignment2
    
    ```

3. Run the following in your command prompt:

    ```bash
    
    python flc_assignment2.py
    
    ```
    
4. Enter the number of grammars to process, for example:

    ```bash
       | Enter the number of grammars to process: 1
    ```
    
4. Enter the number of rules and the number of strings, for example:

    ```bash
       | Enter the number of rules and the number of strings: 5 5
    ```
    
4. Enter production rules, for example:

    ```bash
       | Enter production rules: C SB
    ```
    
4. Enter the string to evaluate, for example:

    ```bash
       | Enter the string to evaluate: aab
    ```
    
5. Check results.
     ```bash
   yes
    ```

