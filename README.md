Download Link: https://assignmentchef.com/product/solved-solvedcis170b-exam
<br>
1. (TCOs 1, 6) Set a variable to a value with the symbol _____, and test equality with _____. (Points : 5)=, ===, ===, ====, =

Question 2.2. (TCOs 1, 6) In the context of object-oriented programming, the Solution Explorer window _____. (Points : 5)exposes the properties of the controlshows the physical components of the programlists the events associated with a controllists the controls on the form

Question 3.3. (TCOs 1, 6) C# comments are represented by which characters? (Points : 4)// and /* */:: and //// and

Question 4.4. (TCOs 2, 3) Your C# program needs to store a single alphanumeric character the user will enter. When your program starts, the default setting for that character should be the letter A. You implement this functionality by writing _____.(Points : 5)char myVar = A;char myVar = ‘A’;char myVar(‘A’);char myVar(A);

Question 5.5. (TCOs 2, 3) What will be the output of this statement?Console.WriteLine(“”to be or not to be””);

(Points : 5)“to be or not to be””to be or not to be” to be or not to be to be or not to be

Question 6.6. (TCOs 2, 3) Before you start writing a program, it’s important to first thoroughly _____. (Points : 5)analyze the problemdesign the solutionspecify the problemAll of the above

Question 7.7. (TCO 4) C# decision structures include _____ and _____. (Points : 5)IF, IF/ELSEIF, FORFOR, FOREACHFOR, WHILE

Question 8.8. (TCO 4) The following C# code _____ compile; however, it contains a _____ error.int x = 15, y = 10;if (x &lt; y);Console.WriteLine(“x is less than y”);

(Points : 5)will, compilerwill, logicalwill not, compilerwill not, logical

Question 9.9. (TCO 5) In this code, the variable _____ is a counter and the variable _____ is an accumulator.double sum = 0, height = 2.0, stop =10, max = 50;int track = 0, num = 0;while (num &lt;= stop){sum = sum + height * num;if (sum &lt;= max)track++;num++;}

(Points : 5)num, tracksum, tracktrack, sumheight, stop

Question 10.10. (TCO 5) What output will this set of statements produce?int a = 10;while (a &lt;= 10){Console.Write(“{0}t”, a);a–;}Console.Write(“{0}t”, a);

(Points : 5)An infinite loopAn exception1010 10 1. (TCOs 7, 8) Because Main() and MyFunction() store counter in _____, the output of this code will be _____.static void Main(){int counter = 8;Console.Write(“{0} “, counter);counter++;MyFunction(ref counter);counter++;Console.Write(“{0} “, counter);Console.Read();}

public static void MyFunction(ref int counter){Console.Write(“{0} “, counter);counter++;}

(Points : 5)different memory locations, 8 9 10the same memory location, 8 9 10different memory locations, 8 9 11the same memory location, 8 9 11

Question 2.2. (TCOs 7, 8) Which is a valid name for a method or function? (Points : 5)mthd11_mthd<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="692410241d010d2958">[email protected]</a>1mthd

Question 3.3. (TCOs 7, 8) Which is a correct heading for a method that returns the difference between two given doubles? (Points : 5)public static void CalcDiff(double price1, double price2);public static double CalcDiff(double price1 , anotherPrice)public static double CalcDiff(double price1 , double price2);public static CalcDiff(double price1, double price2);

Question 4.4. (TCOs 9, 10) A(n) _____ is a notification from the _____ that an action has occurred, such as a mouse click or a key press. (Points : 5)event, GUI applicationconsole application, operating systemGUI application, eventevent, operating system

Question 5.5. (TCOs 9, 10) Which of the following statements will retrieve the selected item of comboBoxEntrees and place it in a myString variable called “myStr”? (Points : 5)myString myStr = comboBoxEntrees.SelectedItem;myString myStr = comboBoxEntrees.Selection();myString myStr = comboBoxEntrees.Text;myString myStr = comboBoxEntrees.getText();

Question 6.6. (TCOs 9, 10) Because a _____ inherits members from the _____ class, it has the methods Show() and Hide(). (Points : 5)Button, ControlForm, ControlRadioButton, ComboBoxTextBox, Form

Question 7.7. (TCOs 11, 12) Given the following declaration, what is/are the value(s) of inches[1,1]?double[,] inches = { {2.25, 3.25, 4.5, 7.25},{3.75, 4.75, 3.5, 3.75} };

(Points : 5)2.252.25 3.753.25 4.754.75

Question 8.8. (TCOs 11, 12) An array is a list of data items that _____. (Points : 5)are all integersare not indexedhave different namesshare the same data type

Question 9.9. (TCOs 11, 12) To delete a specified number of characters from a String, use its _____ method. (Points : 5)Delete();Concat();Insert();Remove();

Question 10.10. (TCO 13) To print out the time a file called “timeSheet.txt” was created, write _____. (Points : 5)Console.WriteLine(File.GetCreationTime(“timeSheet.txt”));Console.WriteLine(GetFileInfo(“timeSheet.txt”);Console.WriteLine(GetCreationTime(“timeSheet.txt”);Console.WriteLine(File.FileInfo(“timeSheet.txt”);

Question 11.11. (TCO 13) A _____ represents a chunk of data and enables the programmer to work with a sequence of bytes. (Points : 5)DirectoryFileStreamTextFile

Question 12.12. (TCO 13) In the following code, the statement “StudentData.Close()” _____.try{StreamWriter StudentData = new StreamWriter(“Dossier.txt”,true);for (int i = 0; i &lt; 10; i++)StudentData.WriteLine(“Student[{0}]: “, i);StudentData.Close();}

(Points : 5)writes 10 lines to “Dossier.txt”keeps the StreamWriter object “StudentData” openwrites a final new line to “Dossier.txt”releases any resources associated with “Dossier.txt”1. (TCO 3) Show the source code for a C# console application called “Downpayment” to display the 20% down payment one would make on a $250,000 house. (Note that the down payment would be .20 times the value of the house.)Declare and initialize appropriate variables for down payment and house value.Include at least three descriptive comments.State what your program displays when it runs.State how you would use the debugger to check the values of your variables as your program runs.(Points : 20)

Question 2. 2. (TCO 5) Describe two types of loops that can be used to print every third integer from 0 to 300 (i.e., 0, 3, 6, 9, etc.), each on its own line. Which would be a better choice and why? Write the code using that type of loop. (Points : 20)Spellcheckerstatement 1 to call method A below. Write statement 2 to call method B. Which method uses pass by-value? Which method uses pass by-reference?static void Main(){int balance = 15000;//statement 1//statement 2

}

//method Apublic static void addBonus(ref int balance){balance = balance + 1000;}

//method Bpublic static int addBonus(int balance){return (balance + 1000);}

(Points : 20)SpellcheckerQuestion 4. 4. (TCO 9) Identify an example of one of each of the following GUI design errors in Figure 2:inconsistencymisalignmentclutter

How could each of the three errors be corrected to improve the user experience?

Image Description(Points : 20)Spellchecker

Question 5. 5. (TCO 12) Although the following code compiles and runs, the programmer made some major readability errors. Describe at least three changes that would make it easier for other programmers to read and understand the code.

class Program{static void Main() //main{int a;int Float = 10; // intsfor(int i = 0;i &lt; Float;i++) /* loop */{a=method(i);Console.WriteLine(a);}Console.Read(); //read}public static int method(int a) /*method*/ {return (int)(Math.Pow((double)a,2.0));}}

(Points : 20)SpellcheckerQuestion 6. 6. (TCO 11) Write a C# program to store an array of integers 10 through 19. Use an appropriate loop to multiply all of the values in the list. Print out the result. (Points : 20)Spellchecker