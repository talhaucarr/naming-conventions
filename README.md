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

## C

| Kind  | Rule |
| ------------- | ------------- |
| Function  | SnakeCase  |
| Variable  | SnakeCase  |
| Pointer Variables  | Should be prepended with ’p’  |
| Global Variables  | Should be prepended with ’g_’  |
| Global Constans  | ScreamingSnakeCase  |
| Define  | ScreamingSnakeCase  |
| Enums  | ScreamingSnakeCase  |
| Arguments  | camelCase  |

![References](https://users.ece.cmu.edu/~eno/coding/CCodingStandard.html#names)&nbsp;




## Python
| Kind  | Rule |
| ------------- | ------------- |
| Variable  | lowerSnakeCase  |
| Function  | lowerSnakeCase  |
| Method  | lowerSnakeCase  |
| Class  | PascalCase  |
| Constant  | ScreamingSnakeCase  |
| Module  | lowerSnakeCase  |


