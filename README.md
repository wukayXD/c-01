# c-01
namespace ConsoleApp_2B
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.ResetColor();
            Console.WriteLine("請輸入N值: ");
            int n = Convert.ToInt32(Console.ReadLine());
           for (int i = 1;i<=n;i++)
            {
                for(int j = 1; j <= n; j++)
                {
                    Console.Write($"{i}*{j}={i * j}");
                }
                Console.WriteLine();
            }
            Console.WriteLine(" 任意按鍵離開....");
            Console.ReadKey();
        }
    }
}
