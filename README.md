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

### Using scanf & printf

```cpp
char ch;
long lo;
int in_;
double dou;
float fl;

int main() {
   
scanf("%d %ld %c %f %lf",&in_,&lo,&ch,&fl,&dou);
printf("%d\n%ld\n%c\n%f\n%lf\n",in_,lo,ch,fl,dou);
    
}

sample input : 3 12345678912345 a 334.23 14049.30493
sample output: 
3
12345678912345
a
334.230
```

## String Methods

### Sub String

```cpp
string s = "12345";

// substr takes start and end index, will produce a string
string drop_last_char = s.substr(0, s.size()-1);

cout << drop_last_char << endl; // "1234"

string section = s.substr(1, 3);

cout << section << endl; // 23
 ```