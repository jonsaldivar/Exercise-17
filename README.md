# Exercise-17

/*
*Jonathan Saldivar
*ITSE 1336
*Excercise 17
*
*/


import java.util.*;

public class Exercise17{

public static void main(String [] Args){


Scanner Input = new Scanner (System.in);


float fltNumber = 0.0f;
float fltNumber2 = 0.0f;
float fltNumberCounter = 0;
float sum = 0;
float average = fltFirstNumber/sum;
final float size = 17.5f;
float fltinput = 9.5;
Float quit = 0f;
 

  for (int intIndex = 0;
  intIndex < size; intIndex++){
  float[] aryNumbers = {fltNumber,fltNumber2};
  System.out.println("Please enter a number: " + Array.toString(aryNumbers));
  fltNumber = Input.nextFloat();
  fltNumberCounter++;                            

     System.out.println("Please enter the second number: " + Array.toString(aryNumbers));
     fltNumber2 = Input.nextFloat();
     fltNumberCounter++;
     
     sum   = fltNumber + fltNumber2;
     average = sum/fltNumberCounter;
     System.out.println("Average: " + average + Array.toString(aryNumbers));
     if(fltNumber== quit && fltNumber2 == quit){
     System.out.println("\n\n\nGoodbye.");
     break;
     }
     }
     
     }
}
