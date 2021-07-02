# Naming Conventions
<ul>
	<li>Camel Case: Words are written adjacent and the first letters are capitalized. It may be that the first letter of the first word is written in lowercase.</li>
	<li>Sneake Case: Words are connected by '_'.</li>
</ul>


## C#

| Kind  | Rule |
| ------------- | ------------- |
| Private Field  | _lowerCamelCase  |
| Public Field  | UpperCamelCase  |
| Protected Field  | UpperCamelCase  |
| Internal Field  | UpperCamelCase  |
| Property  | UpperCamelCase  |
| Method  | UpperCamelCase  |
| Class  | UpperCamelCase  |
| Interface  | IUpperCamelCase  |
| Local Variable  | lowerCamelCase  |
| Parameter  | lowerCamelCase  |

```c#
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
| Method  | lowerCamelCase  |
| Class  | UpperCamelCase  |
| Interface  | UpperCamelCase  |
| Variable  | lowerCamelCase  |
| Package  | lowerCamelCase  |
| Constant  | ScreamingSnakeCase  |

## C++

| Kind  | Rule |
| ------------- | ------------- |
| Method  | UpperCamelCase  |
| Class  | UpperCamelCase  |
| Variable  | lowerSnakeCase  
| Private Field  | mlowerCamelCase  |
| Public Field  | UpperCamelCase  |
| Static Variables  | Should be prepended with ’s’  |
| Pointer Variables  | Should be prepended with ’p’  |
| Constant  | ScreamingSnakeCase  |
| Arguments  | lowerCamelCase  |

## Python
| Kind  | Rule |
| ------------- | ------------- |
| Variable  | lowerSnakeCase  |
| Function  | lowerSnakeCase  |
| Method  | lowerSnakeCase  |
| Class  | UpperCamelCase  |
| Constant  | ScreamingSnakeCase  |
| Module  | lowerSnakeCase  |


