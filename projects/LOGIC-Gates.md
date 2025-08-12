# LOGIC GATES

Logic gates are fundamental building blocks of digital circuits, performing logical operations on binary inputs (0s and 1s) to produce a single binary output. They are essential components in electronic devices like computers and smartphones.

Building logic gates from scratch provides a foundational understanding of how all modern digital electronics work, from a simple calculator to a complex computer. It bridges the gap between the abstract idea of a "gate" and the physical reality of how electricity is controlled to perform computations.

### From Magic to Physics
At a high level, we're told computers use 1s and 0s. By building a gate, you see what a 1 and a 0 physically are: a high voltage (+5V) and a low voltage (0V or Ground). You learn that "logic" is just the clever arrangement of electronic switches (transistors) that manipulate these voltages. It turns the "magic" of computing into understandable physics.

Understanding the low-level struggle makes you appreciate the layers of abstraction that allow programmers to work with high-level languages without ever thinking about individual electrons, voltages, or "sneak paths." It’s like learning how an engine works makes you a more knowledgeable driver.

## AND GATE 

An AND Gate produces a high output (1) only when all of its inputs are high (1); otherwise, the output is low (0).

### Truth table:

| Input A | Input B | Output (A AND B) |
|:-------:|:-------:|:----------------:|
|    0    |    0    |         0        |
|    0    |    1    |         0        |
|    1    |    0    |         0        |
|    1    |    1    |         1        |

### Circuit Diagram

<img width="400" height="300" alt="AND Gate" src="https://github.com/user-attachments/assets/fb3f66f1-d0c4-4879-ad15-ba16650df8c0" />


Here LED acts as the output!

### Visuals 📸

![andgates](https://github.com/user-attachments/assets/0e71f72c-f139-49f3-9cc6-9c96b40bb0f6)

LED turns on at [1 | 1], and off at the rest which is the expected behaviour of an AND Gate
