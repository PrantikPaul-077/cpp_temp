### C++ Input Methods Cheat Sheet

A quick reference for all commonly used C++ input methods with descriptions and examples.



| Input Method    | Description                                      | Example                                |
| --------------- | ------------------------------------------------ | -------------------------------------- |
| `cin`           | Reads formatted input separated by whitespace.   | `cin >> x;`                            |
| `getline()`     | Reads an entire line including spaces.           | `getline(cin, s);`                     |
| `cin.get()`     | Reads a single character (including whitespace). | `char ch; cin.get(ch);`                |
| `cin.getline()` | Reads a C-style character array until newline.   | `char str[100]; cin.getline(str,100);` |
| `scanf()`       | C-style formatted input (works in C++).          | `scanf("%d",&x);`                      |
| `fgets()`       | Reads an entire line into a character array.     | `fgets(str,100,stdin);`                |
| `stringstream`  | Reads values from a string as if it were input.  | `stringstream ss(s); ss >> x;`         |
| `ifstream`      | Reads input from a file.                         | `ifstream fin("input.txt"); fin >> x;` |
