# C Data Structures Lab

An educational C project for practicing common data structures: Linked Lists and Stacks.

## Project Structure

- `exercises.c` — Student implementation file (modify this)
- `test.c` — Unit tests (do not modify)
- `arraylist.c` / `arraylist.h` — ArrayList (List TDA) implementation
- `stack.h` — Stack TDA (built on top of List)
- `test.sh` — Build, test, and submission script
- `log` — Auto-generated test run history

## How It Works

- `test.c` includes `exercises.c` and `arraylist.c` directly via `#include`
- Compiled with: `gcc -g test.c -Wall -Werror -o a.out`
- Run `bash test.sh` to compile, test, and optionally push results to GitHub

## Workflow

- **Start application**: Runs `bash test.sh` (console output)
  - Compiles `test.c` (which includes all source files)
  - Runs tests and shows results
  - Prompts to push progress to GitHub remote

## Exercises

1. `crea_lista()` — Create a list with integers 1–10
2. `sumaLista()` — Sum all elements in a list
3. `eliminaElementos()` — Remove all occurrences of a value from a list
4. `copia_pila()` — Copy a stack while preserving order
5. `parentesisBalanceados()` — Check if parentheses in a string are balanced
