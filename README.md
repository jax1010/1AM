# hello-world
first repository;
Compiling the Coding game in my life.

Starting out C++


#include <iostream>
  
  using namespace std;
  
  int main(){
  cout<<"The journey begins";
  return 0;
  }
  
USER INPUT:-
  
  #include <iostream>
  
  using namespace std;
  
  int x;
  
  cout<<"Type a number";
  cin>> x;
  
  cout<<"Your input is: " << x;
  

  STRING:-
  
  #include <string>
  
  string firstname = "jon";
  string lastname = "doe";
  string fullname = firstname + lastname;
  string fullname = firstname + " " + lastname;
  string fullname = firstname.append(lastname);
  cout<< fullname;
  
  
  ELSE IF:-
  
  #include <iostream>
  
  using namespace std;
  
  int time = 20;
  
  if (time<10){
    cout<< "Morning"; }
  elseif (time<20){
    cout<< "Afteroon";}
  else { 
    cout<< "Good night"; }
