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

## NAND GATE

A NAND Gate produces the complement of the AND Gate.

### Truth table:

| Input A | Input B | Output (A AND B) |
|:-------:|:-------:|:----------------:|
|    0    |    0    |         1        |
|    0    |    1    |         1        |
|    1    |    0    |         1        |
|    1    |    1    |         0        |

### Circuit Diagram

<img width="692" height="495" alt="Screenshot 2025-08-18 at 5 18 15 PM" src="https://github.com/user-attachments/assets/52fd61e9-03ca-449d-9263-018ee3ca0498" />

Here LED acts as the output!

### Visuals 📸

![nand](https://github.com/user-attachments/assets/f79cf330-7b4e-4b42-a5a2-9a65a321c05f)

LED turns off at [1, 1], and on at rest which is the expected behaviour of an NAND Gate

## NOR GATE

A NOR Gate produces the complement of the OR Gate.

### Truth table:

| Input A | Input B | Output (A AND B) |
|:-------:|:-------:|:----------------:|
|    0    |    0    |         1        |
|    0    |    1    |         0        |
|    1    |    0    |         0        |
|    1    |    1    |         0        |

### Circuit Diagram

<img width="692" height="495" alt="Screenshot 2025-08-18 at 5 53 31 PM" src="https://github.com/user-attachments/assets/5403adb1-a193-413a-9ebf-14330ae10c5f" />

Here LED acts as the output!

### Visuals 📸

![nor](https://github.com/user-attachments/assets/1b0c79e5-c9cd-4eba-9bb9-ad9bb48e449b)

LED turns on at [0, 0], and off at rest which is the expected behaviour of an NOR Gate

## XOR GATE

A XOR Gate produces `1` when inputs are exclusive OR.

### Truth table:

| Input A | Input B | Output (A AND B) |
|:-------:|:-------:|:----------------:|
|    0    |    0    |         0        |
|    0    |    1    |         1        |
|    1    |    0    |         1        |
|    1    |    1    |         0        |

### Circuit Diagram

<img width="692" height="495" alt="Screenshot 2025-08-18 at 5 53 31 PM" src="https://github.com/user-attachments/assets/5403adb1-a193-413a-9ebf-14330ae10c5f" />

Here LED acts as the output!

### Visuals 📸

<img width="976" height="695" alt="Screenshot 2025-08-19 at 8 01 56 PM" src="https://github.com/user-attachments/assets/79e50aac-9673-430a-a82b-930a954a0471" />

LED turns off at [0, 0] and [1, 1], and on at rest which is the expected behaviour of an XOR Gate
