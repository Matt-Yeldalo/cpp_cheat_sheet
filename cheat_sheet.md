# C++ Cheat Sheet - Competitive Programming

## Setup & Run

Basic template, instant stetup macro bound to `"cpp" + tab` in vscode:  

```cpp

    #include <bits/stdc++.h>
    using namespace std;

    int main(int argc, char *argv[]) {

    return 0;
  }
```

1. `g++ (file_name.cpp) -o (chosen_exe_name)`. If no option used, the default exe will be a.exe.

2. `./(chosen_exe_name)`

## Input/Output

### Reading multiple inputs, character by character

```cpp

char ch;
// While there is a character to read
while (cin >> ch){
  cout << ch << endl;
}
```
