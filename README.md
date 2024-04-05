# RSA Factoring Challenge

Welcome to the RSA Factoring Challenge repository! This project contains a program designed to factorize natural numbers into products of two smaller numbers.

## Task Description

The task involves breaking down each number provided in a file into its prime factors. The program should run independently without dependencies and adhere to a 5-second time limit for execution.

## Usage

To use the program, follow these steps:

1. Clone the repository to your local machine.
2. Compile the program using your preferred compiler.
3. Execute the program with the following command:
```python
./factors <file>
```
Where `<file>` is a text file containing natural numbers to factor, with one number per line. Each line will contain a valid natural number greater than 1, and the file will end with a new line.

#### Output Format
The program outputs each factorization in the format:
```python
n = p * q
```
Where `n` is the input number, and `p` and `q` are its factors. The factors `p` and `q` do not have to be prime numbers.

#### Example
```python
4=2*2
12=6*2
34=17*2
128=64*2
1024=512*2
4958=2479*2
1718944270642558716715=343788854128511743343*5
9=3*3
99=33*3
999=333*3
9999=3333*3
9797973=3265991*3
49=7*7
239809320265259=15485783*15485773
```
### Repository Structure
- `factors`: The executable program.
- `tests`: Contains test cases for validation.
- `README.md`: Instructions and documentation.
