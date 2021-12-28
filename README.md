using System;
namespace DogLife
{
    class Program
    {
        static void Main(string[] args)
        {
            string dogBreed = Console.ReadLine();
            Console.WriteLine("Entre 'm' or 'f' for gender of dog: ");
           
            char dogGender = Convert.ToChar(Console.ReadLine());

            switch (dogBreed)
            {

               case "Shepherd":
                    if (dogGender == 'm')
                    {
                        Console.WriteLine("{0} dog months", (13 * 12 / 6));
                    }
                    else
                    {
                        Console.WriteLine("{0} dog months", (14 * 12 / 6));
                    }break;
                case "Shih Tzu":
                    if (dogGender == 'm')
                    {
                        Console.WriteLine("{0} dog months", (15 * 12 / 6));
                    }
                    else
                    {
                        Console.WriteLine("{0} dog months", (16 * 12 / 6));
                    }break;
                case "Pitbull":
                    if (dogGender == 'm')
                    {
                        Console.WriteLine("{0} dog months", (14 * 12 / 6));
                    }
                    else
                    {
                        Console.WriteLine("{0} dog months", (15 * 12 / 6));
                    }break;
                case "Poodle":
                    if (dogGender == 'm')
                    {
                        Console.WriteLine("{0} dog months", (16 * 12 / 6));
                    }
                    else
                    {
                        Console.WriteLine("{0} dog months", (17 * 12 / 6));
                    }break;
                case "Samoyed":
                    if (dogGender == 'm')
                    {
                        Console.WriteLine("{0} dog months", (12 * 12 / 6));
                    }
                    else
                    {
                        Console.WriteLine("{0} dog months", (13 * 12 / 6));
                    }break;
                case "Husky":
                    if (dogGender == 'm')
                    {
                        Console.WriteLine("{0} dog months", (11 * 12 / 6));
                    }
                    else
                    {
                        Console.WriteLine("{0} dog months", (12 * 12 / 6));
                    }break;
                default: Console.WriteLine("Invalid dog breed!"); break;
            }
        }
    }
}
