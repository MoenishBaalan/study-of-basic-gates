# STUDY OF BASIC GATES
## AIM:

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

## Equipments Required:

Software – Quartus prime 

## Theory

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

## AND gate

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

## OR gate

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

## NOT gate

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

## NAND gate

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

## NOR gate

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

## Ex-OR gate

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

## Ex-NOR gate

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

## Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## PROGRAM

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by:Gokul R
 
 RegisterNumber: 212222230039
 
## Logic symbol & Truthtable
### AND GATE
![320280673-cb7bb724-8b45-40af-8405-9c563ccfbb45](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/912fc3c1-1a21-4632-8d57-c578617fbe78)


### LOGIC SYMBOL AND TRUTH TABLE
![320280721-dd2dcf2d-b50a-4d9a-bcff-4559c857f185](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/62711ce7-d447-4406-aff8-30cee5c613fd)

![320281002-0b7606a2-7958-46c4-8dce-5e33d3a67f13](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/cde77e28-b860-46d8-ac06-124a5b019b15)



## RTL realization Output:
![320280924-646e1b73-e358-414d-bd3d-af683b4fccc5](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/5ff94b12-8095-449c-b71d-410b82453ac2)


### OR GATE
![320281107-04af8cbf-f7c1-47cb-91f4-7b22bb69d306](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/072dee71-6416-467e-b1b8-2733035dc4f8)

### LOGIC SYMBOL AND TRUTH TABLE
![320281127-b91cf740-feeb-4fad-a526-fdcf0790e01f](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/7d3d5e28-b258-42a0-99e8-0657a84bc11c)

![320281152-6a13234f-72c9-412f-8fe4-dec27258d9a8](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/10c9a062-b39a-40d3-9b12-fee826ca070e)

## RTL realization Output:
![320281275-f356d5ca-08f3-4a20-beb2-700636a675f3](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/f5eb4f5e-2ce0-4a7a-8ecc-2b315d7ef678)

### NAND GATE
![320281328-e0e774a6-675a-4ae5-8c88-4dd038d2d2d9](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/7e927122-df9f-4390-90c1-0ab11f96d9fe)

### LOGIC SYMBOL AND TRUTH TABLE
![320281357-96009bf3-ca80-4f9e-a78c-fdd8a24cfc1f](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/7ae25f72-30f2-40a8-b5bf-1d7481a99e02)

![320281379-cf17b691-fdc6-4c12-8e54-8f86144595a9](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/204767d1-a0f3-4d71-9801-1058bc166aa2)

## RTL realization Output:
![320281410-17c61d09-8683-4412-a849-4a42ea63ac13](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/6dd10184-bd2a-4dbe-afb5-b194717387cf)

### NOT GATE
![320281454-79d2b7e8-2589-4ebd-a565-7e8ab093bd8a](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/4cb86acc-6d42-4ef3-8802-929889285e76)

### LOGIC SYMBOL AND TRUTH TABLE
![320281483-117a8e9d-8560-45b5-8dfc-a60ab13e5c91](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/bd124244-be3e-4f43-ac75-596bdb7d69d4)
![320281495-85372843-11e7-4c72-9c72-f7d717880eb3](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/c7fb5e94-f8ad-4fb6-ae6e-ef93ac71117c)

## RTL realization Output:
![320281510-e38ab851-d647-41b7-b7de-2997e27fcd35](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/dc93f349-6d25-49f9-a1a3-a8706c27f7e9)


### NOR GATE
![320281537-4715b206-b384-4531-98db-0d9d21c0a1e0](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/6b909647-3fd4-4422-a4cf-bda742d45f58)


### LOGIC SYMBOL AND TRUTH TABLE

![320281561-c2a6b7a1-77f5-4cdd-a1ae-ad71c2fd0805](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/2b0b4b1d-8927-42bb-8885-e789d6371f70)

![320281584-8f6f5031-5c48-47ba-8441-553f40c1fab0](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/b67386f0-b95e-44b1-8d1e-63c955287d12)

## RTL realization Output:
![320281613-4d5c8295-caad-4a6f-ba36-591cc57c33e4](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/23195a5d-b247-4f92-a450-20c4dab5d176)

### EX-OR GATE
![320281864-62794195-059b-4a3b-9770-016116dc8dcd](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/f342375a-5081-40a0-a8ba-6bd6f22581e0)

### LOGIC SYMBOL AND TRUTH TABLE
![320281898-6fb964da-a49c-4c58-b44d-53ec5fffe766](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/0d2967bf-42c7-480e-b263-f7c8892ce04f)
![320281910-880d416c-56e1-49c5-be41-b97c5a0c7bfa](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/b1b1f9b6-5fbb-4748-9926-4cfa97a5c5ac)

## RTL realization Output:
![320281990-2dece152-fdd1-4827-8e8f-ba05a7f87a11](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/bce92763-ce26-4960-b320-f34398b8e722)


### EX-NOR GATE
![320282203-0f097a73-285a-4477-aca5-79ad9462a4ce](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/2010ffa6-a6c1-46ae-9dd7-afda97a10dab)

### LOGIC SYMBOL AND TRUTH TABLE
![320282637-7351e5b4-6475-402a-b7f0-ba8077ff6151](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/521e0c04-80fd-429e-a9ec-6918fbbc3d13)
![320282706-87155193-516b-49b8-a202-167578e943e8](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/71fdee92-af97-4bf9-a062-173724b1d6cb)

## RTL realization Output:
![320282768-1e994fb0-6b75-4bdb-8636-2d7edc098582](https://github.com/MoenishBaalan/study-of-basic-gates/assets/147473396/a3e68ac4-8f49-47f7-835e-d84c312527d0)

## Result:
Thus, the study of basic gates was executed successfullly.

