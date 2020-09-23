<div align="center">

## Absolute Beginners lesson 04


</div>

### Description

This code is for examples of variable use and is from a tutorial with some of my own comments added.
 
### More Info
 
Two Text Boxes

One Button

This code works best if used in the

Visual C# 2005 (also Express Edition)

debug. It is for learning about variable types,

assignment, and expressions.

Comment out all blocks except the one you want to see work.

Message boxes

Label Changes

Some parts of the code have errors that show what

happens when not used right.

This code will not run untill some of the comment

marks are removed.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Douglas G\. Allen](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/douglas-g-allen.md)
**Level**          |Beginner
**User Rating**    |4.7 (14 globes from 3 users)
**Compatibility**  |C\#
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__10-33.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/douglas-g-allen-absolute-beginners-lesson-04__10-5218/archive/master.zip)

### API Declarations

The only rights will be in the links provided for additional information.


### Source Code

```
//******************************************************************************
//*   Using variables                                    *
//* From video lesson 4 by Bob Tabor                               *
//* @ http://download.microsoft.com/download/6/2/4/6247616D-A0C7-4552-B622-3F0450DE2462/04CSharp.wmv *
//* Some of my own tests and comments were added.                         *
//* These are mostly examples and each block is commented out like this /*...*/.               *
//* To run them simply uncomment the block desired.                         *
//******************************************************************************************
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Text;
using System.Windows.Forms;
//* Create a form with two text boxes, a label and a button to use this code in .NET 2.0 Framework with Visual C#.
namespace lesson04
{
 public partial class Form1 : Form
 {
  public Form1()
  {
   InitializeComponent();
  }
  private void button1_Click(object sender, EventArgs e)
  {
   /*(remove)
   //Create a string variable.
   string myStringVariable;
   //Assign the string variable a value.
   myStringVariable = "myStringVariable = PI";
   //Display the string.
   MessageBox.Show(myStringVariable);
   (remove)*/
   /*
   //Create another string variable and assign a string.
   string myOtherStringVariable = "PI =";
   //Display the string.
   MessageBox.Show(myOtherStringVariable);
   */
   /*
   //Create an integer variable with a value.
   int myInteger = 3;
   //Display the value as a string by converting it.
   MessageBox.Show(myInteger.ToString());
   */
   /*
   //Create a double variable(integer and decimal) with a value.
   double myDouble = 3.14;
   //Display the value as a string by converting it.
   MessageBox.Show(myDouble.ToString());
   */
   /*
   //Create a string variable using an object value and converting
   //to a string.
   string myMathPI = Math.PI.ToString();
   //Display the object value.
   MessageBox.Show(myMathPI);
   */
   /*
   //Create a Boolean variable and assign it a value.
   bool myBoolean = true;
   //Display the Boolean value as a string.
   MessageBox.Show(myBoolean.ToString());
   */
   /*
   //Create a string variable from another string variable.
   string myConverted = myMathPI;
   //Display the string.
   MessageBox.Show(myConverted);
   */
   /*
   //Create a string variable.
   string hello;
   //Assign it a string.
   hello = "Hello World";
   //Display the string.
   MessageBox.Show(hello);
   */
   /*
   //Display a string literal.
   MessageBox.Show("hello world");
   */
   /*
   //Putting two strings together.
   string firstTextBox = textBox1.Text;
   string secondTextBox = textBox2.Text;
   label1.Text = firstTextBox + " " + secondTextBox;
   */
   /*
   //What happens when using wrong variable types.
   int myVariable = "some string";
   string myvariable = 3;
   */
   /*
   //This works
   int myValue = 3;
   double myOtherValue;
   myOtherValue = myValue;
   */
   /*
   //But will this?
   int myValue;
   double myOtherValue = 3.14;
   myValue = myOtherValue;
   */
   /*
   //Will this work?
   int firstTextBox = 0;
   int secondTextBox = 0;
   int result = 0;
   firstTextBox = textBox1.Text;
   secondTextBox = textBox2.Text;
   result = firstTextBox + secondTextBox;
   label1.Text = result;
   */
   /*
   //Be carefull and enter only integer values or
   //see what happens.
   int firstTextBox = 0;
   int secondTextBox = 0;
   int result = 0;
   firstTextBox = int.Parse(textBox1.Text);
   secondTextBox = int.Parse(textBox2.Text);
   result = firstTextBox + secondTextBox;
   label1.Text = result.ToString();
   */
   /*
   //will this work?
   int x;
   x + 3;
   */
   /*
   //will this work?
   int x;
   x = x + 3;
   */
   //Be sure to check out
   //http://go.microsoft.com/fwlink/?linkid=45191&clcid=409
   //and if you cannot parse xml then go to this link
   //http://msdn.microsoft.com/vstudio/express/visualcsharp/learning/
   //The new Interenet Explorer 7.0 is out of beta and it will parse xml.
   //@ http://windowsupdate.microsoft.com/
  }
 }
}
```

