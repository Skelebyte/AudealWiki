# Getting Started with Audeal
## Download Audeal
To get started, head to the [latest download](https://github.com/Skelebyte/Audeal/releases) of Audeal. The download will contain:

- the Audeal header file (`Audeal.hpp`)
- the miniaudio header file (`miniaudio.h`)


!!! warning
    The miniaudio header is _required_ for Audeal to function, so don't remove it.

## Install
To actually use it, move the contents of the downloaded folder to your project root.

## Using Audeal
To use Audeal, just include it at the top of your file.
```cpp
#include "path/to/Audeal.hpp"

int main() {
    // ...
}
```

## Compiling with Audeal
Because Audeal is just a wrapper, we still have to compile with the flags required for miniaudio.
### Build Requirements for miniaudio
!!! tip inline end
    For more info, head to [Building](https://miniaud.io/docs/manual/index.html#Building) in the miniaudio docs.
| OS      | Flags                       |
|---------|-----------------------------|
| Linux   | `-ldl -lm -lpthread`        |
| Windows | Nothing required            |
| macOS   | `-lm -lpthread`             |



Make sure to include these flags when compiling your project to ensure that miniaudio functions correctly.
