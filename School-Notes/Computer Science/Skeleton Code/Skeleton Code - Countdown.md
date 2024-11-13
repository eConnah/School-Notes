The skeleton code seems to be the game countdown however it suffers from lack of complexity and is unable to do simple mathematics such as multiplying the result of an addition. Everytime you guess a number it disappears from the list, however the list also shuffles along 1 to the left. If the left most side of the list disappears off the screen you die.

<div style="page-break-after: always;"></div>

# Alteration One
Allowing spaces in UserInput.
## Change One
In method PlayGame
```csharp
UserInput = Console.ReadLine();
```
Changed To
```csharp
UserInput = Console.ReadLine().Replace(" ", string.Empty);
```

<div style="page-break-after: always;"></div>

# Alteration Two
Removing duplicate numbers from the available numbers.
## Change One
In method FillNumbers
```csharp
while (NumbersAllowed.Count < 5)
{
	NumbersAllowed.Add(GetNumber(MaxNumber));
}
```
Changed To
```csharp
while (NumbersAllowed.Count < 5)
{
	int tempNumber = GetNumber(MaxNumber);
	if (!NumbersAllowed.Contatins(TempNumber))
	{
		NumberAllowed.Add(TempNumber);
	}
}
```

<div style="page-break-after: always;"></div>

# Alteration Three
Adding the ability to use exponents.
## Change One
In method EvaluateRPN
```csharp
while (!"+-*/".Contains(UserInputInRPN[0]))
```
Changed To
```csharp
while (!"+-*/^".Contains(UserInputInRPN[0]))
```
And Added This
```csharp
case "^":
	Result = Math.Pow(Num1,Num2);
	break;
```
## Change Two
In method CheckIfUserInputValid
```csharp
return Regex.IsMatch(UserInput, @"^([0-9]+[\+\-\*\/])+[0-9]+$");
```
Changed To
```csharp
return Regex.IsMatch(UserInput, @"^([0-9]+[\+\-\*\/\^])+[0-9]+$");
```
## Change Three
In method ConvertToRPN
```csharp
Dictionary<string, int> Precedence = new()
{
	{ "+", 2 }, { "-", 2 }, { "*", 4 }, { "/", 4 }
};
```
Changed To
```csharp
Dictionary<string, int> Precedence = new()
{
	{ "+", 2 }, { "-", 2 }, { "*", 4 }, { "/", 4 }, { "^", 6}
};
```

<div style="page-break-after: always;"></div>

# Alteration Four
Allowing the game to repeat.
## Change One
In method Main
```csharp
// rest of code
```
Changed To
```csharp
do {
	// rest of code
	Console.Write("Would you like to play again (y/n): ");
	playAgain = Console.ReadLine().ToLower() == "y";
} while (playAgain);
```
