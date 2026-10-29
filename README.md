# C++ and DSA Learning Workspace

This folder is set up for C++20 with GCC, VS Code IntelliSense, build tasks, and GDB debugging.

## Run your current file

1. Open this `DSA` folder in VS Code (`File > Open Folder`).
2. Open any `.cpp` file.
3. Click the green **Run C/C++ File** button in the editor title bar, then choose **C++: Run active file** if VS Code asks. It builds and runs the file.
4. Use **Ctrl+F5** to run without the debugger, or **F5** to debug. Set breakpoints by clicking beside a line number.

The build task uses the current `.cpp` file and writes an `.exe` beside it. Build errors appear in the Terminal and Problems panel. `test.cpp` has been preserved.

If the title-bar button still shows the old placeholder, close and reopen the DSA folder or reload VS Code (`Ctrl+Shift+P` → **Developer: Reload Window**). The workspace `.vscode/launch.json` now contains the executable path.

## Learning path

Work through the numbered folders in order. Each `main.cpp` is a compilable starter with a suggested task. Make your own solutions in that folder; add one `main()` per file you compile directly.

1. `01_fundamentals` — input/output, types, conditions, loops, functions
2. `02_strings_arrays` — strings, arrays, vectors, two pointers, prefix sums
3. `03_stl` — vector, pair, map, set, stack, queue, priority queue
4. `04_complexity` — Big O, counting operations, choosing data structures
5. `05_recursion` — base cases, recursion trees, backtracking
6. `06_search_sort` — binary search and sorting
7. `07_linked_lists` — nodes, traversal, insertion, deletion
8. `08_stacks_queues` — monotonic stack, queue, deque
9. `09_trees` — binary trees, BST, traversals, heaps
10. `10_graphs` — adjacency lists, BFS, DFS, shortest paths
11. `11_greedy` — sorting by choices, intervals, proof of a greedy choice
12. `12_dynamic_programming` — states, transitions, memoization, tabulation
13. `13_bit_manipulation` — masks, shifts, XOR, bit tricks

## Suggested routine

For each topic, read the task in its `main.cpp`, implement it, compile/run, then test an ordinary case, an edge case, and a larger case. Keep notes and solved problems in your own files. Use `-Wall -Wextra -Wpedantic` warnings to catch common mistakes.

## Useful shortcuts

- Run/debug: **F5**
- Run without debugger: **Ctrl+F5**
- Build active file: **Ctrl+Shift+B**
- Command Palette: **Ctrl+Shift+P**

C++ standard: **C++20**. This is a single-file workflow; for a project with several `.cpp` files, compile all of them together or add a project-specific build system later.
