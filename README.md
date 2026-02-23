# 8-Bit-Arithmetic-Operations-using-8085
## SARAN R
## 212224050042
## Aim:
To perform 8-bit arithmetic operations such as addition, subtraction, multiplication, and division using the 8085 microprocessor.

## Apparatus Required:
•	Laptop with internet connection

## Algorithm:

### For Addition (With Carry Consideration):
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Add the contents of registers A and B.
4.	If carry is generated, store carry in 4301H.
5.	Store the sum in memory location 4300H.
   
### Program:

<img width="1387" height="805" alt="image" src="https://github.com/user-attachments/assets/55780fb0-dedd-4062-b345-1f90c85e9cb9" />

### Output:

<img width="514" height="825" alt="image" src="https://github.com/user-attachments/assets/9b52747c-1642-41a7-ab17-cfaf3598576b" />

<img width="515" height="875" alt="image" src="https://github.com/user-attachments/assets/7419371a-2dfb-4cc9-837d-3764075fadf0" />

### Explanation : 

![WhatsApp Image 2026-02-02 at 11 18 47 AM](https://github.com/user-attachments/assets/9ec7a2cf-226d-4f90-b0bd-b8bfea3929d1)

### For Subtraction (Considering Greater Number):
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Compare A and B.
4.	If A < B, swap the values of A and B to ensure positive result.
5.	Subtract the content of B from A.
6.	Store the result in memory location 4300H.

### Program:

<img width="1335" height="762" alt="image" src="https://github.com/user-attachments/assets/b9262af7-1e89-4126-b771-0d09b19f9c70" />

### Output:

<img width="538" height="757" alt="image" src="https://github.com/user-attachments/assets/14dab02c-ea93-4e3e-853e-8f930073eb16" />

<img width="531" height="745" alt="image" src="https://github.com/user-attachments/assets/9abd6bee-8589-4195-a028-958369215343" />

### Explanation : 

![WhatsApp Image 2026-02-02 at 3 04 01 PM](https://github.com/user-attachments/assets/0dbb9693-38df-490f-892a-703eb1c83257)

### For Multiplication:
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Multiply A and B using repeated addition.
4.	Store the result in memory locations 4300H and 4301H (if required for higher bits).

### Program:

<img width="1560" height="803" alt="image" src="https://github.com/user-attachments/assets/8850d37f-4577-4068-9130-2f865e77b2ed" />

### Output:

<img width="514" height="794" alt="image" src="https://github.com/user-attachments/assets/96594805-a5ca-4e0f-94f5-56d9418a182a" />

<img width="522" height="732" alt="image" src="https://github.com/user-attachments/assets/11932b7d-d862-4096-9b87-c7e0caed5620" />

### Explanation : 

![WhatsApp Image 2026-02-02 at 3 09 16 PM](https://github.com/user-attachments/assets/81f71558-ea5d-4cd2-9b88-a63161889e54)

### For Division:
1.	Load the dividend from memory location 4200H into register A.
2.	Load the divisor from memory location 4201H into register B.
3.	Perform division using repeated subtraction.
4.	Store the quotient in 4300H and remainder in 4301H.

### Program:

<img width="1189" height="826" alt="image" src="https://github.com/user-attachments/assets/bc549150-879d-442c-bc9b-37008584dedb" />

### Output:

<img width="450" height="737" alt="image" src="https://github.com/user-attachments/assets/c0984964-71d4-499c-9a75-5f4b0510f4b6" />

<img width="458" height="744" alt="image" src="https://github.com/user-attachments/assets/1e07f227-2760-4796-98f7-7c424ffb7f71" />

### Explanation : 

<img width="1546" height="1600" alt="image" src="https://github.com/user-attachments/assets/2ecd8e84-f442-4274-b70e-ae33d14c580a" />

## Result:
The 8-bit arithmetic operations using the 8085 microprocessor have been successfully executed and verified using memory access for input and output.

