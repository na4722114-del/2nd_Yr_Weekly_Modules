# C Programming — Module 1

Notes and practice programs for **Module 1** of B.Tech CSE (Batch 2025–2029), covering syntax basics, conditionals, loops, switch statements, and pattern printing. Written and tested in VS Code.

## 📌 Topics Covered

- C syntax basics (variables, data types, input/output)
- Conditional statements (`if`, `if-else`, nested `if-else`)
- Loops — `for`, `while`, `do-while`
- `switch` statements
- Pattern programs — square, triangle, pyramid, diamond, and more

## 📂 Folder Structure

Each program lives in its own `.c` file, named by what it does:

```
Module-1/
├── basics/
│   ├── hello_world.c
│   ├── variables_datatypes.c
│   └── input_output.c
├── conditionals/
│   ├── if_else_basic.c
│   ├── nested_if_else.c
│   └── grade_calculator.c
├── loops/
│   ├── for_loop.c
│   ├── while_loop.c
│   └── do_while_loop.c
├── switch/
│   └── switch_case_menu.c
├── patterns/
│   ├── square_pattern.c
│   ├── triangle_pattern.c
│   ├── pyramid_pattern.c
│   └── diamond_pattern.c
└── README.md
```

> Adjust the tree above to match your actual filenames — this is a template based on the topic list.

## ▶️ How to Run

Each file is a standalone C program. Compile and run using GCC:

```bash
gcc filename.c -o output
./output
```

Or use the **Run** button in VS Code with the [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) extension.

## 🖼️ Sample Outputs

Screenshots of VS Code terminal outputs for select programs are included to show expected results. *(Add an `outputs/` or `screenshots/` folder with PNGs, and link them here, e.g. `![Diamond Pattern Output](outputs/diamond_output.png)`.)*

## 🔧 Planned Enhancements

This module is a base for ongoing improvement. Ideas for next passes:

- [ ] Add input validation (handle bad/negative input gracefully)
- [ ] Add comments explaining logic for each pattern program
- [ ] Refactor repeated pattern logic into reusable functions
- [ ] Add a few "challenge" variants (hollow square, inverted pyramid, number patterns, alphabet patterns)
- [ ] Add a Makefile or shell script to compile all programs at once
- [ ] Write a short complexity note (loop count / time complexity) for each pattern

## 🎓 Course Info

- **Course:** B.Tech, Computer Science & Engineering
- **Subject:** C Programming (BCS-201)
- **University:** AKTU (Dr. A.P.J. Abdul Kalam Technical University)
- **Institute:** KCC Institute of Technology and Management, Delhi

## 📜 License

Free to use for learning and reference. If this helped you, a ⭐ on the repo is appreciated!
