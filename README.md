# NAND2TETRIS

კონსპექტი კურსისთვის - [Coursera](https://www.coursera.org/learn/build-a-computer)


[პირველი დავალება](https://github.com/peferron/nand2tetris/tree/master/01)
## კვირა 1 - Elementary Logic Gates
[Image Source](https://theorycircuit.com/basic-logic-gates-truth-table/)
### Nand (primitive)

AND + NOT
![nand primitive](https://theorycircuit.com/wp-content/uploads/2017/05/nand-gate-truth-table.png)

### Not

[YouTube](https://youtu.be/gI-qXk7XojA?t=170)
![Not gate](https://theorycircuit.com/wp-content/uploads/2017/05/not-gate-truth-table.png)
### And

[YouTube](https://youtu.be/gI-qXk7XojA?t=283)
![And gate](https://theorycircuit.com/wp-content/uploads/2017/05/and-gate-truth-table.png)
### Or

[YouTube](https://youtu.be/gI-qXk7XojA?t=347)
![Or gate](https://theorycircuit.com/wp-content/uploads/2017/05/or-gate-truth-table.png)
### Xor

[YouTube](https://youtu.be/gI-qXk7XojA?t=437)
![xor gate](https://theorycircuit.com/wp-content/uploads/2017/05/xor-gate-truth-table.png)
### Mux
### Dmux
### Not16
### And16
### Mux16
### Or8Way
### Mux4Way16
### Mux8Way16
### DMux4Way
### DMux8Way

---

HDL - Hardware Discribe Language
- [VHDL](https://en.wikipedia.org/wiki/VHDL)
- [Verilog](https://www.tutorialspoint.com/vlsi_design/vlsi_design_verilog_introduction.htm)
- ...
---

## კვირა 2 - Arithmetic-Logic Unit
დადებითი - ![Formula](https://render.githubusercontent.com/render/math?math=0%20...%202%5E%7Bn-1%7D-1&mode=inline) 

უარყოფითი - ![Formula](https://render.githubusercontent.com/render/math?math=0%20...%20-2%5E%7Bn-1%7D&mode=inline)

y-x = y + (-x) \
გამოკლების მთავარი იდეა: \
![](https://render.githubusercontent.com/render/math?math=2%5En%20-%20x%20%3D%201%20%2B%20%282%5En%20-%201%29%20-%20x)

იმისთვის რომ 4 გადავაქციოთ უარყოფითად, \
`1111` \
`-` \
`0100` \
`=` \
`1011` \
`+` \
`0001` \
`=` \
`1100 = 12 = -4`


---

## Binary Table
| Binary | Decimal | 
|:---:|:---:|
`0000` | `0` 
`0001` | `1` 
`0010` | `2` 
`0011` | `3` 
`0100` | `4` 
`0101` | `5` 
`0110` | `6` 
`0111` | `7` 
`1000` | `-8` (8)
`1001` | `-7` (9)
`1010` | `-6` (10)
`1011` | `-5` (11)
`1100` | `-4` (12)
`1101` | `-3` (13)
`1110` | `-2` (14)
`1111` | `-1` (15)

---
### Halfadder
![](images/half-adder.png)

### FullAdder (Regular adder)
![](images/full-adder.png)

### Add16
### Inc16
### ALU - Arthmetic Logic Unit
![](images/alu.png)
![](images/alu-chip.png)
---
## კვირა 3 - Registers And Memory
### Bit
### Register
### RAM8
### RAM64
### RAM512
### RAM4K
### RAM16K
### PC
---
## კვირა 4 - Computer Architecture
### Memory
### CPU
### Computer
---
## კვირა 5 - Writing Low-Level Programs
---
## კვირა 6 - Developing An Assembler
