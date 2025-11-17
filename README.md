# funworkstuff4

Collection of lab exercises, scripts, and small programs used for coursework.

Summary
- This repository contains a set of numbered lab directories (`lab1`..`lab9`) with exercises, answers, scripts, and small C/Python programs.
- Content appears to be personal lab submissions (answers, source code, build artifacts) for systems and programming tasks.

Quick structure
- `lab1/` — text answers for shell and Emacs exercises (`ans1.txt`, `key1.txt`).
- `lab2/` — utility shell scripts like `buildwords` and `sameln`.
- `lab3/` — Python helper `comm.py` and lab writeups.
- `lab4/` — (short lab exercises)
- `lab5/`..`lab8/` — additional lab directories with assignments and scripts.
- `lab9/` — C programs and makefiles for a random-number lab (`randall`, `randlibsw.c`, `randlibhw.c`, `Makefile`, `lab.txt`, `COPYING`).

Notable files
- `lab2/buildwords` — Bash script that extracts and processes words from HTML input.
- `lab2/sameln` — Bash script that deduplicates files by creating hard links for identical files.
- `lab3/comm.py` — Python implementation of a `comm`-like utility with options to suppress columns and support unsorted input.
- `lab9/` — contains C sources, object files, shared libraries, and a `Makefile` for building `randmain` and `randlib` components.

Usage
- The repository is primarily a collection of examples. To run or inspect scripts, open the relevant `labN` folder and run scripts or compile sources as needed.
- Example: make and run the lab9 `randmain` (if you want to rebuild from sources):

  ```bash
  cd lab9
  make
  ./randmain
  ```

Guidance
- Many compiled artifacts and generated files are present (object files, shared objects, tarballs). If you want a clean, source-only copy, remove the build artifacts (e.g., `*.o`, `*.so`, `randmain`, `dlsubmission.tgz`).
- If you want a more detailed README for a specific lab, tell me which lab(s) and I will expand examples, usage, and how to build/run the contained code.

License / Attribution
- The repo contains a `COPYING` file under `lab9/` — review that file for license information related to the C code in that lab.

Contact
- This README was generated automatically from the repository contents. If anything should be changed, let me know and I will update it.
