16.Fibonacci<br> 
using System;<br>
public class FibonacciExample<br>
{<br>
    public static void Main(string[] args)<br>
    {<br>
        int n1 = 0, n2 = 1, n3, i, number;<br>
        Console.Write("Enter the number of elements: ");<br>
        number = int.Parse(Console.ReadLine());<br>
        Console.Write(n1 + " " + n2 + " "); //printing 0 and 1<br>    
        for (i = 2; i < number; ++i) //loop starts from 2 because 0 and 1 are already printed  <br>  
        {<br>
            n3 = n1 + n2;<br>
            Console.Write(n3 + " ");<br>
            n1 = n2;<br>
            n2 = n3;<br>
        }<br>
    }<br>
}<br>

OUTPUT:<br>
![Screenshot 2022-03-03 102158](https://user-images.githubusercontent.com/98145032/156506486-719a77bd-98a9-4b86-8abd-6b77ae6c1802.png)
