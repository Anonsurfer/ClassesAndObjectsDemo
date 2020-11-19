using System;
namespace MethodsAndClasses
{
    class Programmed
    {
        static void Main()
        {
            int x;
            Student_Data student1 = new Student_Data();
            Console.WriteLine("\t\t\t\t\tWelcome to my program ! ");
            Console.WriteLine("1. To Enter The Data Of The Student");
            Console.WriteLine("2. To Information");
            Console.WriteLine("3. To Help ");
            Console.WriteLine("Enter your Choice 1/2/3");
            try
            {
                x = Convert.ToInt32(Console.ReadLine());
                if(x == 1)
                {
                    student1.Enter_Data();
                    student1.Print();
                }
                else if (x == 2)
                {
                    student1.Information();

                }
                else if (x == 3)
                {
                    student1.Help();
                }
                else 
                {
                Console.WriteLine("Sorry, We Didn't get you enter your choice again !");
                Main();
                }
            }
            catch (Exception ex)
            {
                Console.WriteLine("Error !");
                Console.WriteLine(ex);
                Main();
            }
           
        }
    }
    class Student_Data // Class 
    {
        public string name; // Field 
        public string school_name; // Field 
        public int age;  // Field 
        public void Information() // Method inside of a class
        {
            Console.Clear();
            Console.WriteLine("This is a simple information!"); 
        }
        public void Help()
        {
            Console.Clear();
            Console.WriteLine("Welcome to help menu !");
        }
        public void Enter_Data()
        {
           
            Console.WriteLine("\t\t\t\t\tData Entry !");
            Console.WriteLine("Enter the name of student ");
            name = Console.ReadLine();
            Console.WriteLine("Enter the School's Name of: {0}", name);
            school_name = Console.ReadLine();
            Console.WriteLine("Enter the Age of the: {0} ",name);
            try
            {
                age = Convert.ToInt32(Console.ReadLine());
            }
            catch (Exception ex)
            {
                Console.Clear();
                Console.WriteLine(ex);
            }
            
         }
        public void Print()
        {
            Console.Clear();
            Console.WriteLine("Name: {0}", name);
            Console.WriteLine("Age: {0}", age);
            Console.WriteLine("School's Name: {0}", school_name);
        }
    }
}
