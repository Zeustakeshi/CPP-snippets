# CPP-snippets

-   Code c++ faster with vs code
-   ✨Magic ✨

## Features

|   snippet   | Description              |
| :---------: | :----------------------- |
|    cppt     | Create c++ template      |
| cr-comment  | Create multiline comment |
|    coutn    | Print new line           |
|   powMod    | Binary Exponentiation    |
| check-prime | Check prime number       |

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

#### Print new line :

```
 coutn
```

Code:

```cpp
    cout  << endl;
```

#### Binary Exponentiation

```
 powMod
```

Code:

```cpp
    ll powMod(ll a, ll b, int mod)
    {
        if (b == 0)
        {
            return 1;
        }
        ll x = powMod(a, b / 2, mod) % mod;
        if (b % 2 == 0)
        {
            return ((x % mod) * (x % mod)) % mod;
        }
        else
        {
            return (((x % mod) * (x % mod)) % mod * (a % mod)) % mod;
        }
    }
```
