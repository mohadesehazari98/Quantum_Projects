# Qiskit
 
![gif](https://www.ibm.com/blogs/research/wp-content/uploads/2018/05/qiskit.gif)

ref ibm.com

Qiskit is an open source software suitable for working with Quantum Computers.

Qiskit is a great tool to start learning Quantum Algorithms and understanding the result of a Classical Computer versus Ideal Quantum Computer or Noisy Quantum Computer.

# Bernstein-Vazirani Algorithm

![image](https://qiskit.org/textbook/ch-algorithms/images/bv1.png)

This algorithm is used to find a number in a black box. Consider black box as a hardware which you can connect input and get the output out of it but you cannot see the inside.

Consider a “n” bit number is stored in that hardware, the goal is to find that number without looking into the hardware.

Classical scheme:
Consider we have a 5-bit number - - - - -. what we can do is to do “AND” operation of the output with 
{10000,01000,00100,00010,00001}. Here after 5 trial, a classical scheme can guess the number correctly.

Quantum scheme:
The difference here is that we can (in one shot) guess the number correctly and we do that by considering all the possibilities of the result. If our inputs were in the state (|0> + |1>) /√2   then the output would be all the possible answers including the correct number. 

in this algorithm one can see the advantages of Quantum Computers over Classical Computers 

this algorithm aims to make a correct guess about an unknown number 

If the number has n bits 

a Classical Computer would need n trials to find the number 

But, Quantum Computers can find the number just in one shot 

# Repeaters 

In the repeater file you can find the implementation of a Quantum repeater using Qiskit tool with noise 

ref : https://arxiv.org/pdf/2009.04584.pdf
