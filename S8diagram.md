# S8 (Selector) diagram
```

A = Input 1, type press switch
B = Input 2, type press switch
C = Input 3, type press switch

O1 = Output 1
O2 = Output 2

V++ = DC Voltage
TEMPLATES(IGNORE) START;
↓
                 .
TEMPLATES(IGNORE) END;
S8 (Selector) Diagram:
| - - - - - - - - - |
|    <-  V++  ->    |
|                   |
|                   |
| A       B       C |
|                   |
| ↓       ↓       ↓ |
|                   |
| O1   <------>  O2 |
| - - - - - - - - - |

```

DO NOT USE:
A = Input 1, type press switch
B = Input 2, type press switch
C = Input 3, type press switch

O1 = Output 1
O2 = Output 2

V++ = DC Voltage
↓
- - - - - - - - -
   <-  V++  ->   .
   <-  V++  ->   .
                 .
A.               .

↓

O1


A = Input 1, type press switch
B = Input 2, type press switch
C = Input 3, type press switch

O1 = Output 1
O2 = Output 2

V++ = DC Voltage
↓
                 .
- - - - - - - - -
   <-  V++  ->   
                 
                 
A       B       C      

↓       ↓       ↓

O1   <-    ->  O2
- - - - - - - - -
