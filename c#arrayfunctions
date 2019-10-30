using System;
namespace abc
{
    public class arrayfunctions
    {
       
            static void Main(string[] args)
            {
                int[] list = { 34, 72, 13, 44, 25, 30, 10 };
                int[] temp = list;
                int[] list2 = new int[8];
                int a, j,x,z;
                Console.Write("Original Array: ");

                foreach (int i in list)
                {
                    Console.Write(i + " ");
                }
                Console.WriteLine();
            //copying the array
                Array.Copy(list, list2,list.Length);
            Console.Write("Copied" + " Array: ");
            foreach (int i in list2)
            {
                Console.Write(i + " ");
            }
            Console.WriteLine();


            // reverse the array
            Array.Reverse(temp);
                Console.Write("Reversed Array: ");

                foreach (int i in temp)
                {
                    Console.Write(i + " ");
                }
                Console.WriteLine();
            //Index of
            Console.Write("Enter the element you want to know index of: ");
            x = int.Parse(Console.ReadLine());
            z=Array.IndexOf(list, x);
            Console.Write(" index of: "+x+"is"+z);
            Console.WriteLine();
            //sort the array
            Array.Sort(list);
                Console.Write("Sorted Array: ");

                foreach (int i in list)
                {
                    Console.Write(i + " ");
                }
                Console.WriteLine();
            //Binary search
                Console.WriteLine("Binary search :");
            Console.Write("Enter element from first array:");
             a = int.Parse(Console.ReadLine());

             j= Array.BinarySearch(list, a);
               if(j<=0)
            {
                Console.Write("Item not found");
            }
            else
            {
                Console.Write("Item found");
            }
            Console.ReadKey();
            }
        }
    }  


