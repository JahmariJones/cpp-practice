# cpp-practice

C++ exercises on my path to embedded firmware (Arduino → ESP32 → STM32). Most programs are C++ versions of my analog-tools Python scripts.

## Programs
| File | What it does | Concepts |
| --- | --- | --- |
| hello.cpp | First program | compiling with g++ |
| ohms.cpp | Ohm's law calculator | variables, cin/cout, functions |
| divider.cpp | Voltage divider with vout() | functions, if statements |
| series_parallel.cpp | R_eq for any number of resistors | loops, arrays |
| thevenin.cpp | Thevenin equivalent, rejects bad input | references, input checking |
| resistor.cpp | Resistor struct with power-rating check | structs |

## Build and run
g++ (MSYS2 UCRT64), C++20:

```
g++ -Wall -Wextra -std=c++20 ohms.cpp -o ohms
.\ohms
```

## Author
Jahmari Jones, BSEE student, Jacksonville University
