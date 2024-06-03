# ODE Tasks
ODE concentrates a set of good development practices. Our role centers between the Business layer and the View layer.
Abstracting, simplifying and standardizing works when invoking, saving and dispatching UseCase<P, R> to the view layer.

## Features
- **Guard of UseCase**: Safely blocks the execution of a UseCase<P, R> and prevents cyclomatic complexity in the presenter.
- **Dispatch UseCase**: Dispatch a UseCase<P, R>.
- **Dispatch Chain UseCase**: Dispatch a UseCase<P, R> that depends on other use cases.
- **Dispatch Sequence UseCase**: Dispatch a list of UseCase<P, R> that are independent of each other.

### Guard of UseCase
`````{tab} Python
  ```python
  print("Hello World!")
  ```
  ````

  ````{tab} C++
  ```c++
  #include <iostream>

  int main() {
    std::cout << "Hello World!" << std::endl;
  }
  ```
  ````
`````

### Dispatch UseCase
`````{tab} Python
  ```python
  print("Hello World!")
  ```
  ````

  ````{tab} C++
  ```c++
  #include <iostream>

  int main() {
    std::cout << "Hello World!" << std::endl;
  }
  ```
  ````
`````

### Dispatch Chain UseCase
`````{tab} Python
  ```python
  print("Hello World!")
  ```
  ````

  ````{tab} C++
  ```c++
  #include <iostream>

  int main() {
    std::cout << "Hello World!" << std::endl;
  }
  ```
`````

### Dispatch Sequence UseCase
`````{tab} Python
  ```python
  print("Hello World!")
  ```
  ````

  ````{tab} C++
  ```c++
  #include <iostream>

  int main() {
    std::cout << "Hello World!" << std::endl;
  }
  ```
  ````
`````