# Command line application template for C

Implement CLI application by editing [main.c](src/main.c).  
You may add new files to keep your code clean, if it is allowed in your challenge.

## How to get input parameters
You can get arguments with ordinary C way, using `int argc` and `char * argv[]`.

```c
int main(int argc, char * argv[])
{
  // code to run
  return 0;
}
```

## How to output result
You can use `printf`.

``` c
  printf ("argv[%i]: %s\n", i, argv[i]);
```

## How to compile
To compile, we are using [clang](http://clang.llvm.org/) gcc command.

If you want to change compile option or etc, please edit [makefile](makefile).  
