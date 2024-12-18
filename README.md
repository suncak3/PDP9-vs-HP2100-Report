# PDP-9 vs HP2100 Architecture Comparison

This repository contains a comparative analysis of the **PDP-9** and **HP2100** architectures, as well as an implementation of a **binary search algorithm** for the HP2100 assembler.

## Directory Structure

- `doc/`
  - `PDP9_vs_HP2100_Report.pdf` - The final comparative report.
- `code/`
  - `binarysearch.pal` - HP2100 assembler implementation of binary search.

## Binary Search Program

### Description:
The `binarysearch.pal` file implements a **binary search algorithm** for the HP2100 architecture. It searches for a specified key value within an array of integers stored in memory.

### Inputs:
- Array of integers stored in memory.
- A search key value.

### Outputs:
- Index of the found value.
- `-1` if the value is not found.

## How to Run the Program

### Prerequisites:
- **SIMH Emulator** with HP2100 support: [SIMH GitHub Repository](https://github.com/simh/simh).

### Steps to Run:
1. Copy the `binarysearch.pal` file into your HP2100 emulator directory.
2. Open a terminal and navigate to the emulator directory.
3. Start the HP2100 emulator:
4. Load the program:
5. Run the program:

## References

- [SIMH GitHub Repository](https://github.com/simh/simh)
- [HP2100 Manual](https://archive.computerhistory.org/resources/text/HP/HP.2100.1972.102646165.pdf)
- [PDP-9 User Manual](https://bitsavers.org/pdf/dec/pdp9/PDP-9_UsersManual.pdf)

---

Author: Mustafinov Talgat
