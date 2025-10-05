# Linear Algebra (LA)

This repository contains source code for Linear Algebra assignment solutions written in LaTeX.

## Project Structure

```
la/
├── assignment-1/
│   ├── main.tex           # Main document file
│   ├── q1-p1.tex         # Question 1, part 1
│   ├── q1-p2.tex         # Question 1, part 2
│   ├── q1-p3.tex         # Question 1, part 3
│   ├── q2-p1.tex         # Question 2, part 1
│   ├── q2-p2.tex         # Question 2, part 2
│   ├── q3-p1.tex         # Question 3, part 1
│   ├── q3-p2.tex         # Question 3, part 2
│   ├── q3-p3.tex         # Question 3, part 3
│   ├── q3-p4.tex         # Question 3, part 4
│   ├── q3-p5.tex         # Question 3, part 5
│   ├── q3-p6.tex         # Question 3, part 6
│   ├── q4-p1.tex         # Question 4, part 1
│   ├── q4-p2.tex         # Question 4, part 2
│   ├── q4-p3.tex         # Question 4, part 3
│   └── q4-p4.tex         # Question 4, part 4
└── README.md
```

### Organization

- Each assignment is organized in its own folder (`assignment-1/`, `assignment-2/`, etc.)
- Within each assignment folder:
  - `main.tex` serves as the master document that includes all questions
  - Individual question parts are separated into their own files (`qX-pY.tex`)

## Building LaTeX Files

### Prerequisites

Ensure you have a LaTeX distribution installed:
- **Linux**: Install `texlive-full`
- **macOS**: Install MacTeX
- **Windows**: Install MiKTeX or TeX Live

### Compilation

To build the PDF for any assignment:

1. Navigate to the assignment directory:
   ```bash
   cd assignment-1
   ```

2. Compile the main LaTeX file:
   ```bash
   pdflatex main.tex
   ```

### Output

The compilation will generate:
- `main.pdf` - The final assignment document
- Various auxiliary files (`.aux`, `.log`, etc.) - These can be safely deleted.

