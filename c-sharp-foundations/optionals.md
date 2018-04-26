
### Nullable Types (optionals)

```csharp
int? i = 10;
double? d1 = 3.14;
bool? flag = null;
char? letter = 'a';
int?[] arr = new int?[10];
```

## Unwrapping a nullable variable

```csharp
int? y = 10;
if (y != null)
{
    System.Console.WriteLine(y.Value);
}
else
{
    System.Console.WriteLine("Undefined");
}
```

```csharp
int? num1 = null;
int num2 = num1 ?? 3;
	
Console.WriteLine(num1); // Prints 3
```

