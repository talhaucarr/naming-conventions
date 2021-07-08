# Naming Conventions
<ul>
	<li>Pascal Case: Words are written adjacent and the first letters are capitalized.</li>
	<li>Camel Case: Words are written adjacent and the first letters are lowercase.</li>
	<li>Sneake Case: Words are connected by '_'.</li>
</ul>


## C#

| Kind  | Rule |
| ------------- | ------------- |
| Private Field  | _camelCase  |
| Public Field  | PascalCase  |
| Protected Field  | PascalCase  |
| Internal Field  | PascalCase  |
| Property  | PascalCase  |
| Method  | PascalCase  |
| Class  | PascalCase  |
| Interface  | IPascalCase  |
| Local Variable  | camelCase  |
| Parameter  | camelCase  |

[Source](https://www.c-sharpcorner.com/UploadFile/8a67c0/C-Sharp-coding-standards-and-naming-conventions/)

```c#
//for example

public class NamingConventions : INamingConventions//Class, Interface
{   

    	private int _number;//Private
    
    	public int Number //Property, Protected, Public, Internal
	{
		get => _number;
		set => _number = value;
	}

	
    	private int Sum(int number, int number2){//Method, Arguments
		return number + number2;
	}
}
```


## Java

| Kind  | Rule |
| ------------- | ------------- |
| Method  | camelCase  |
| Class  | PascalCase  |
| Interface  | PascalCase  |
| Variable  | camelCase  |
| Package  | camelCase  |
| Constant  | ScreamingSnakeCase  |

[Source](https://www.oracle.com/java/technologies/javase/codeconventions-namingconventions.htmls)

```java
//for example

interface InterfaceMyClass {
    public void Hi();
}

class ForExampleClass{
    
    final ARRAY_SIZE;
    int studentNumber;
    
    public void Hi(){
        System.out.println("Hi");
    }
    
}
```

## C++

| Kind  | Rule |
| ------------- | ------------- |
| Method  | PascalCase  |
| Class  | PascalCase  |
| Variable  | lowerSnakeCase  
| Private Field  | mcamelCase  |
| Public Field  | PascalCase  |
| Static Variables  | Should be prepended with ’s’  |
| Pointer Variables  | Should be prepended with ’p’  |
| Constant  | ScreamingSnakeCase  |
| Arguments  | camelCase  |

[Source](https://users.ece.cmu.edu/~eno/coding/CppCodingStandard.html)

```c++
//for example
const double TWO_PI = 6.28318531; //Global

class CleaningDepartment{ //Class
	public:
	int StartYourEngines( Engine& rSomeEngine, Engine anotherEngine); //Method arguments
		void TestConveyorStart(StatusInfo& rStatus);
		StatusInfo& rGetStatus(); //returns a modifiable object so requires the ’r’ prefix
		int ComputeErrorNumber();
	private:
		static StatusInfo msStatus; //Static
		int mCleanHouse //Private
		int mErrorNumber;
		String *mpName; //Pointer
}

```

## C

| Kind  | Rule |
| ------------- | ------------- |
| Function  | SnakeCase  |
| Variable  | SnakeCase  |
| Pointer Variables  | Should be prepended with ’*’  |
| Global Variables  | Should be prepended with ’g_’  |
| Global Constans  | ScreamingSnakeCase  |
| Define  | ScreamingSnakeCase  |
| Enums  | ScreamingSnakeCase  |
| Arguments  | camelCase  |

[Source](https://users.ece.cmu.edu/~eno/coding/CCodingStandard.html#names)

```c
//for example

#include <stdio.h>
void retry_max(char firstName); //Function, Arguments

#define ARRAY_SIZE  15 //Define

const int A_GLOBAL_CONSTANT= 5; //Global Const
Logger  g_log; //Global Variable

int main(){
	int snake_case = 0; //Variable
	char *name; //Pointer

}

```


## Python
| Kind  | Rule |
| ------------- | ------------- |
| Variable  | lowerSnakeCase  |
| Function  | lowerSnakeCase  |
| Method  | lowerSnakeCase  |
| Class  | PascalCase  |
| Constant  | ScreamingSnakeCase  |
| Module  | lowerSnakeCase  |

[Source](https://realpython.com/python-pep8/)


```python
//python

import my_module

CONST_NAME = "Name" //Const

class ForExample:
	int number_example
	
	def number_sum(number_first):
		return number_first + number_first
		
def add_two_number():
	return 1 + 2

```


