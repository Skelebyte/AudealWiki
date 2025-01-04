# Namespace
There is a single namespace included in Audeal, the `adl` namespace. It is used to hold all the classes included in Audeal.
## Usage
There are 2 ways to use the `adl` namespace:
```cpp
// Option 1
#include "Audeal.hpp"

int main() {
    adl::Audio myAudio = adl::Audio();
    // ...
}
```
```cpp
// Option 2
#include "Audeal.hpp"

using namespace adl;

int main() {
    Audio myAudio = Audio();
    // ...
}
```
Although both options are usable, option 1 should be prefered so you can tell the difference between what class/function belongs to which library. It will also solve any issues where another library has a class or function with the same name.