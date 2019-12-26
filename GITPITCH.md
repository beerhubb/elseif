## else-if & nested if

---

## Agenda

@ol
* Basic `else-if` statement syntaxs
* Basic `nested if` statement syntaxs
@olend

---

## Basic `else-if` statement syntaxs

```csharp
if (condition) 
{
    
} 
else if(condition2) 
{
    
} 
else 
{
    
}
```

+++

## demo 1

```csharp
var sccore = 81;

if (score > 80) 
{
    Console.writeline("A")
} 
else if (score > 70) 
{
    Console.writeline("B")
}
else 
{
    Console.writeline("F")
}
```

#### result

```csharp
A
```

---

## Basic `nested if` statement syntax 

```csharp
if (condition) 
{
	if (condition) 
	{
		
	} 
	else 
	(

	)
}
```

+++

## demo 1

```csharp
var number = 1;
var numbers = 2;

if (number == 1) 
{

	if (numbers == 2) 
	{
		Console.writeline("Hello World")
	} 
	else 
	{
		Console.writeline("Hello mama");
	}
}
```

#### result

```csharp
Hello World
```
