# BIGlittle
Just for fun
// A simple code to take a user's input and return all capital letters.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace BIGlittle
{
    class Program
    {
        static void Main(string[] args)
        {
            // This line asks the user to input any word.
            Console.WriteLine("Enter any word and press enter.");

            // This line takes the user's input.
            string userInput = Console.ReadLine();

            // This line take the user's input and converts the
            // entire content into uppercase letter(s).
            string toUpper = userInput.ToUpper();

            // This line displays the user's new uppercase version
            // of input in a console.
            Console.WriteLine(toUpper);

            // This line pauses the console and allows the user
            // continue after pressing any key.
            Console.ReadKey();
        }
    }
}
