# Emb_SW_Dev_Cpp
This repository was created do help me during the Udemy course: [Embedded Software Development using C++](https://www.udemy.com/course/embedded-software-development-using-cpp/).

### Section 3

Serial Wire debug can be enable using STMCubeMX.

To use C code inside a C++ program:

```c
extern "C" void SysTick_Handler(void){
	HAL_IncTick();
}
```
### Section 4

Bassically we create the **class** object, within its *public: (.h file)* functions we have the **constructor** to initalize the object. Then we create a **method** to receive datada from Bluetooth module.

On obj.cpp file, we have the source codes for the *class::constructor (same_name::same_name)* and on main we call it and send its parameters.

### Sectino 6

LCD class desing: 

class encapsulation (of HAL, data and functions)

* private: data
* public: methods

print will be a method that can handle datas such as char, array of chars and integer.
