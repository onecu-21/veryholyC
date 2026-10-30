# VeryholyC

> Simple. It uses LLVM, ISO, GNU, etc.

> However It is not allowed to use MSVC.

> Only code you can run at windows is this:

``` C
#include<stdlib.h>

int main(void){
#ifdef _WIN32
    exit(1);
#endif

return 0;
}
```