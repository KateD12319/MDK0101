# МДК0101
class Worker
{
    public string surname; 
    public int age; 
    public int experience; 
    public void GetInfo()
    {
        Console.WriteLine($"Фамилия: {surname}  Возраст: {age}  Опыт:{ experience}");
    }
}
class Program
{
    static void Main(string[] args)
    {
        Worker tom = new Worker(); 
        tom.surname = "Danilov";
        tom.age = 34;
        tom. experience = 2;
        tom.GetInfo(); 
        Console.ReadKey();
        Name pizza piz = (Name pizza)2;
        Console.WriteLine();
        Name pizza piz1 = (Name pizza)4;
        Console.WriteLine();
        Name pizza piz2 = (Name pizza)1;
        Console.WriteLine();
        Name pizza piz3 = (Name pizza)3;
        Console.WriteLine();
         
        Console.ReadLine();
    }
}

Public class Waiter : Worker
{ 
private static int Age;
    public Waiter (string surname, int age, int experience) : base(surname, age, experience)   
    {
    }
static Waiter ()
   {
      Age = 25;
   }
}
class Pizza
{
    public string name; 
    public int size; 
    public void GetInfo()
    {
        Console.WriteLine($"Название: {name} Размер: {size}");
    }
}
[Flags]
public enum Name pizza
   {
      four cheeses = 1,
      peperomy = 2,
      Hawaiian = 3,
      meat food = 4
   }
