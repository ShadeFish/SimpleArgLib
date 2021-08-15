# SimpleArgLib
Simple Class to parse input arguments

```c#
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


