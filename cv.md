# Arina Zhukova

> Whoever does not take risks runs the greatest risk of being left with nothing.

![Моё фото](photo.jpg)

---

### Navigation
- [Contact information](#contact-information)
- [About Me](#about-me)
- [Skills](#skills)
- [Code example](#code-example)
- [Experience](#experience)
- [English language](#english-language)

---

### Contact information 
**Telephone:** +375(29) 736-93-71  
**Email:** zhuchkovvaa@mail.ru  
**Instagram:** [@zhuchkovva](https://www.instagram.com/zhuchkovva)

---

## About Me
I am a second-year student at **Belarusian-Russian University**, studying **Software Engineering** at the Faculty of Electrical Engineering.
I am a cheerful, outgoing, and goal-oriented person.
My main goal is to become a skilled software engineer. I also really want to work in a large office with a big and friendly team.

---

## Skills
- **Programming Languages**: C#
- **Databases**: Microsoft Access
- **Tools**: Visual Studio

---

## Code Example
```csharp
using System;

class Program

    static void Main(string[] args)
    {
        int rows = 0, cols = 0;
        int[,] myArray = null;

        try
        {
            Console.Write("Enter number of matrix rows: ");
            rows = int.Parse(Console.ReadLine());
            Console.Write("Enter number of matrix columns: ");
            cols = int.Parse(Console.ReadLine());

            if (rows < = 0 || cols < = 0)
            {
                throw new ArgumentException("Matrix dimensions must be positive numbers.");
            }

            myArray = new int[rows, cols];
            InputArray(myArray);
            Output(myArray);
            FindMaxElement(myArray);
        }
        catch (FormatException ex)
        {
            Console.WriteLine($"Input error: invalid number format. {ex.Message}");
        }
        catch (ArgumentException ex)
        {
            Console.WriteLine($"Validation error: {ex.Message}");
        }
    }
```
---

## Experience
-Electronic Catalog "Cables, Adapters and Splitters" in C# WinForms
-"Walking route"
-Development of an Information System "Educational Process Management'"

---

## English language 
My English level is **A2**.
