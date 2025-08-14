# LOGIC GATES

Logic gates are fundamental building blocks of digital circuits, performing logical operations on binary inputs (0s and 1s) to produce a single binary output. They are essential components in electronic devices like computers and smartphones.

Building logic gates from scratch provides a foundational understanding of how all modern digital electronics work, from a simple calculator to a complex computer. It bridges the gap between the abstract idea of a "gate" and the physical reality of how electricity is controlled to perform computations.

### From Magic to Physics
At a high level, we're told computers use 1s and 0s. By building a gate, you see what a 1 and a 0 physically are: a high voltage (+5V) and a low voltage (0V or Ground). You learn that "logic" is just the clever arrangement of electronic switches (transistors) that manipulate these voltages. It turns the "magic" of computing into understandable physics.

Understanding the low-level struggle makes you appreciate the layers of abstraction that allow programmers to work with high-level languages without ever thinking about individual electrons, voltages, or "sneak paths." It’s like learning how an engine works makes you a more knowledgeable driver.

## AND GATE 

A AND Gate produces a high output (1) only when all of its inputs are high (1); otherwise, the output is low (0).

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

## OR GATE

An OR Gate produces a high output (1) if at least one of its inputs is high (1). The output is only low (0) when all inputs are low (0).

### Truth table:

| Input A | Input B | Output (A AND B) |
|:-------:|:-------:|:----------------:|
|    0    |    0    |         0        |
|    0    |    1    |         1        |
|    1    |    0    |         1        |
|    1    |    1    |         1        |

### Circuit Diagram

<img width="400" height="240" alt="or-gate" src="https://github.com/user-attachments/assets/a08403ae-3e0d-4d44-a907-2146f2f57ce0" />

Here LED acts as the output!

### Visuals 📸

![orgate](https://github.com/user-attachments/assets/1f046d33-f641-48ee-8887-559650f443ce)

LED turns off at [0 | 0], and on at the rest which is the expected behaviour of an OR Gate

## NOT GATE

A NOT Gate produces the complement of the input.

### Truth table:

| Input | Output |
|:-----:|:------:|
|  0    |    1   |
|  1    |    0   |

### Circuit Diagram

<img width="220" height="200" alt="not-gate" src="https://github.com/user-attachments/assets/e4476731-a5b6-4284-9446-b833b9ed158d" />

Here LED acts as the output!

### Visuals 📸

![notgate](https://github.com/user-attachments/assets/a6a3c373-5ce5-4315-859f-2c33dbfd9480)

LED turns off at [1], and on at [0] which is the expected behaviour of an NOT Gate
