# CPP-snippets

![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)

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

### Create c++ template.

```json
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

### Create multiline comment:

```json
 cr-comment
```

Code:

```cpp
    /* your comment here */
```

### Create array:

```json
 cr-arr
```

Code:

```cpp
    data_type arr[length];
```

### Create vector :

```json
 cr-vec
```

Code:

```cpp
    vector <data_type> vector_name;
```

### Create function :

```json
 cr-func
```

Code:

```cpp
return_type function_name ( parameter list ) {

}
```

### Create nested for loops :

```json
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

### Create random id (uuid) :

```json
 cr-id
```

Code:

```cpp
    4c79f6ae-c418-4772-b8e6-0a24702551fb
```

### Print to screen and new line :

```json
 cout
```

Code:

```cpp
    cout  << value << endl;
```

### Print to screen and space :

```json
 couts
```

Code:

```cpp
    cout  << value << " ";
```

### Print new line :

```json
 coutn
```

Code:

```cpp
    cout  << endl;
```

### Print array item to screen

```json
cout-arr
```

Code:

```cpp
    for (size_t i = 0; i < length; ++i)
    {
        cout << arr[i] << endl;
    }
```

### Get input from user

```json
    cin
```

Code:

```cpp
    cin >> variable_name;
```

### Get value for array from user input

```json
    cin-arr
```

Code:

```cpp
    for (int i = 0; i < length; ++i)
    {
        cin >> arr[i];
    }
```

