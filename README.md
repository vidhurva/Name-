# Name-
c++ Program that uses null-terminated sequences of characters
   #include <iostream>
   using namespace std;
   
   int main()
   {
           char question[] = "Please enter your first name: ";
           
          // The number of characters in question do need to be defined due to array syntax
          char greeting[] = " Hello, ";
          char greeting2[] = " Your name strikes fear in the hearts of millions. Don't take me seriously.";
          char name[100];  
          
          // Read by user
          cout << question;
          cin  >> name;
          cout << greeting << name << "." << greeting2 << endl;
          // No need to put "[]" syntax, array is declared only once for this program 
          
  return 0;
  }
