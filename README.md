# SimpleArgLib
Simple Class to parse input arguments

```c#
 /* INPUT SYNTAX EXAMPLE:
            myApp.exe -argumentName(value) -argumentName

            OUTPUT:
            1. argumentName:value
            2. -arguementName:""
  */

class Program
{
  static void Main(string[] args)
  {
   foreach (Argument arg in SimpleArg.Parse(args))
   {
    Console.WriteLine(arg.ToString());
   }
   
   Console.Read();
  }
}
```


