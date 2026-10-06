# Lab_06

# Number Theory: Addition
In this lab you've learned the basics of number theory as it relates to addition.
## Rubric
| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary
- In this lab we learned how logic gates can be used to perform binary addition. We created a basic XOR implementation acting as a stair light, an adder and full adder in Verilog, then connected two full adders together to create a two bit adder and tested our designs on the Basys 3 board.

## Lab Questions
### 1 - How might you add more than two bits together?
- We could add more bits by connecting additional full adders together. The carry out from each full adder would connect to the carry in of the next full adder.
## 
### 2 - What is the importance of the XOR gate in an adder?
- The XOR gate determines the sum bit in binary addition. It outputs 1 when the input bits are different and 0 when they are the same.
##
### 3 - What is the largest number a two bit adder can handle? What happens when you go over?
- Each two-bit input can represent up to 3 (11), so the largest sum is 6 (110). The extra bit is represented by the carry out from the most significant full adder.
##
