# Emb_SW_Dev_Cpp
This repository was created do help me during the Udemy course: [Embedded Software Development using C++](https://www.udemy.com/course/embedded-software-development-using-cpp/).

### Section 3

To use C code inside a C++ program:

```c
extern "C" void SysTick_Handler(void){
	HAL_IncTick();
}
```
