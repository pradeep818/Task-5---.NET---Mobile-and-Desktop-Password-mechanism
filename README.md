namespace pradeep;
class System
{
    public static void Main(string[] args)
    {
        Console.WriteLine("          *****Welcome to Ausis Store*****:");
        Console.Write("Choose your Device (1.Mobile 2.Desktop) : ");
        int y = Convert.ToInt32(Console.ReadLine());
        if (y == 1)
        {
            Console.ForegroundColor = ConsoleColor.Gray;
            Console.WriteLine("Enter the Password to set(num) : ");
            int s = Convert.ToInt32(Console.ReadLine());
            Console.Clear();
            Console.ForegroundColor = ConsoleColor.Blue;
            Console.WriteLine("Enter the Password to login");
            int r = Convert.ToInt32(Console.ReadLine());
            if (r != s)
            {
                for (int i = 1; i <= 3; i++)
                {
                    Console.ForegroundColor = ConsoleColor.Magenta;
                    Console.WriteLine("Wrong Password");
                    Console.WriteLine("Enter the Password to login");
                    int o = Convert.ToInt32(Console.ReadLine());
                    






                }
                for (int l = 30; l >= 1; l--)
                {
                    Console.Clear();
                    Console.WriteLine("Countdown" + l + "seconds");
                    
                    Console.Write("Enter password to login");
                    


                }
            }
            if (r == s)
            {
                Console.ForegroundColor = ConsoleColor.Red;

                Console.WriteLine("    *****Welcome BRO******");

            }

            


        }
        if (y == 2)
        {
            Console.ForegroundColor = ConsoleColor.Gray;
            Console.WriteLine("Enter the Password to set(num) : ");
            String s = Console.ReadLine();
            Console.Clear();
            Console.ForegroundColor = ConsoleColor.Blue;
            Console.WriteLine("Enter the Password to login");
            String r = Console.ReadLine();
            if (r != s)
            {
                for (int i = 1; i <= 3; i++)
                {
                    Console.ForegroundColor = ConsoleColor.Magenta;
                    Console.WriteLine("Wrong Password");
                    Console.WriteLine("Enter the Password to login");
                    String o = Console.ReadLine();







                }
                for (int l = 30; l >= 1; l--)
                {
                    Console.Clear();
                    Console.WriteLine("Countdown" + l + "seconds");

                    Console.Write("Enter password to login");



                }
            }
            if (r == s)
            {
                Console.ForegroundColor = ConsoleColor.Red;

                Console.WriteLine("    *****Welcome BRO******");

            }




        }






    }
}
