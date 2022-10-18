# CPP-snippets

-   Code c++ faster with vs code
-   ✨Magic ✨

## Features

|  snippet   | Description                         |
| :--------: | :---------------------------------- |
|    cppt    | Create c++ template                 |
| cr-comment | Create multiline comment            |
|   cr-arr   | Create array                        |
|   cr-vec   | Create vector                       |
|  cr-func   | Create function                     |
|  cr-dbfor  | Create nested for loops             |
|   cr-id    | Create random id (uuid)             |
|    cout    | Print to screen and new line        |
|   couts    | Print to screen and space           |
|   coutn    | Print new line                      |
|  cout-arr  | Print array item to screen          |
|  cin-arr   | Get value for array from user input |

## Usage

#### Setup

-   Local: create folder `.vscode` in your project and then add file `cpp.code-snippets`
-   Global:
    -   Select User Snippets under `File` > `Preferences` (`Code` > `Preferences` on macOS)
    -   Select the `c++` language for which the snippets should appear, or the New Global Snippets file option if they should appear for all languages. VS Code manages the creation and refreshing of the underlying snippets file(s) for you.

#### Create c++ template.

```
 cppt
```

Code:

```cpp
#include<bits/stdc++.h>
using namespace std;
int main ()
{

    return 0;
}
```

#### Create multiline comment:

```
 cr-comment
```

Code:

```cpp
    /* your comment here */
```

#### Create array:

```
 cr-arr
```

Code:

```cpp
    data_type arr[length];
```

#### Create vector :

```
 cr-vec
```

Code:

```cpp
    vector <data_type> vector_name;
```

#### Create function :

```
 cr-func
```

Code:

```cpp
return_type function_name ( parameter list ) {

}
```

#### Create nested for loops :

```
 cr-dbfor
```

Code:

```cpp
 for (size_t i = 0; condition; ++i)
    {
        for (size_t j = 0; condition; ++j)
        {
            /* code */
        }
    }
```

#### Create random id (uuid) :

```
 cr-id
```

Code:

```cpp
    4c79f6ae-c418-4772-b8e6-0a24702551fb
```

#### Print to screen and new line :

```
 cout
```

Code:

```cpp
    cout  << value << endl;
```

#### Print to screen and space :

```
 couts
```

Code:

```cpp
    cout  << value << " ";
```

#### Print new line :

```
 coutn
```

Code:

```cpp
    cout  << endl;
```

#### Print array item to screen

```
cout-arr
```

Code:

```cpp
    for (size_t i = 0; i < length; ++i)
    {
        cout << arr[i] << endl;
    }
```

#### Get input from user

```
    cin
```

Code:

```cpp
    cin >> variable_name;
```

#### Get value for array from user input

```
    cin-arr
```

Code:

```cpp
    for (int i = 0; i < length; ++i)
    {
        cin >> arr[i];
    }
```
