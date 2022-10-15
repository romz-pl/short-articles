# C++17 global variable with defined lifetime

## See my GitHub repository [global-variable](https://github.com/romz-pl/global-variable)

### The implemation is stored in one file [global.h](https://github.com/romz-pl/global-variable/blob/main/global.h)

Class definition
![Class definition](./fig1.png)

For class of name `Matrix`, the global variable must be used as follows
![Usage for examplary class Marix](./fig2.png)

To function `global::init` the derived class can be passes as well
![The function global::init](./fig3.png)

The global object must be destroyed exactly one time
![The function global::destroy](./fig4.png)

In order to use the object, call function `global::get` defined as follows
![The function global::get](./fig5.png)

The existence of the object can be check by function `global::exists`
![The function global::exists](./fig6.png)


