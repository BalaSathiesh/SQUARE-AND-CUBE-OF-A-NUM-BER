# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
MOV A,P0 

MOV R0,A 

MOV B,R0 

MUL AB 

MOV P2,A 

END








```

## OUTPUT
<img width="536" height="324" alt="Screenshot 2025-10-27 104530" src="https://github.com/user-attachments/assets/dbb0a874-d3b1-4b5a-bae0-7558bd2272cb" />

![WhatsApp Image 2025-11-02 at 16 52 13_bcfe8db4](https://github.com/user-attachments/assets/2272a251-1f3c-468d-879f-b4d0311ca3d8)


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END








```


## OUTPUT
<img width="439" height="320" alt="Screenshot 2025-11-02 151645" src="https://github.com/user-attachments/assets/04b62ba6-2472-4be9-a62e-20399ab8c62b" />

![WhatsApp Image 2025-11-02 at 16 52 13_d75a246d](https://github.com/user-attachments/assets/60503fc6-f0e5-4bb5-abb3-1c5360d05e63)


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
