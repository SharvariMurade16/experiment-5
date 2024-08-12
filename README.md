# Experiment-5
## Aim-
To study and implement C++ decision making statements
## Theory-
Decision-making statements control the flow of a program based on conditions. Key types include:

1. If-Else Statement:
Executes one block if the condition is true, another if false.

2.Nested if-else statements:
these are used when you need to check multiple conditions in a hierarchical manner. An if or else block can contain another if-else statement inside it. This is useful for more complex decision-making processes.

3. calculator statement:
it is used for doing mathematical calculations among some given values.

4. Switch Case Statement:
Used in some languages to handle multiple conditions, mimicked in Python using dictionaries.

## Code-
```
//sharvari murade
//23070123088
//entc-b1

#include <iostream>
using namespace std;
int main(){
    int num;
    cout<<"Enter a number: ";
    cin>>num;
    if(num==0){
        cout<<"Entered number is 0";
    } else if(num%2==0){
        cout<<"Entered number is Even";
    } else {
        cout<<"Entered number is Odd";
    }

    return 0;
}
```
## Output-
![83519510-21B1-4EC3-8C5A-EF9F4A3443DA_4_5005_c](https://github.com/user-attachments/assets/4a31b481-da28-48fe-bbd3-ef32d6682f8a)

```

//sharvari murade
//23070123088
//entc-b1

#include <iostream>
using namespace std;
int main(){
    int n1, n2;
    cout<<"Enter first number: ";
    cin>>n1;
    cout<<"Enter second number: ";
    cin>>n2;
    if(n1>n2) {
        cout<<n1<<" is greater than "<<n2;
    } else {
        cout<<n2<<" is greater than "<<n1;
    }

    return 0;
}
```
## Output-

![A16781A6-53C4-4261-B722-540F405EFF18](https://github.com/user-attachments/assets/80ecde03-5ea9-4c48-b7cf-9ed74d59e08e)

```
//sharvari murade
//23070123088
//entc-b1


#include <iostream>
using namespace std;

int main() {
  int y;
  cout << "Enter a year: ";
  cin >> y;
  if((y%4==0 && y%100!=0)||(y%400==0)){
    cout<<y<<" is a leap year";
  } else{
    cout<<y<<" is not a leap year";
  }
  return 0;
}
```
### Output-

![5DAB093D-4A47-41F1-A759-955B78C6CE4C](https://github.com/user-attachments/assets/ddb0961d-1e7b-4949-91b7-f28d2d3e11c6)

```
//sharvari murade
//23070123088
//entc-b1

#include <iostream>
using namespace std;

int main() {
  int a,b,c;
  cout << "Enter first number: ";
  cin >> a;
  cout << "Enter second number: ";
  cin >> b;
  cout<<"Welcome to calculator"<<endl;
  cout<<"Operations: Addition(1), Subtraction(2), Multiplication(3), Division(4)"<<endl;
  cout<<"Enter your operation number: "<<endl;
  cin>>c;
  
  switch(c){
      case 1:
      cout<<"The sum of your digits is = "<<(a+b);
      break;
      case 2:
      cout<<"The difference of your digits is = "<<(a-b);
      break;
      case 3:
      cout<<"The product of your digits is = "<<(a*b);
      break;
      case 4:
      if(b!=0){
          cout<<"The division of your digits is = "<<(a/b);
      } else { 
          cout<<"divide by 0 error";
      break; }
  }
  return 0;
 }
```
### Output-
![8DF4CFA1-4F37-435F-88B9-438084548B50](https://github.com/user-attachments/assets/99612d4d-f1f5-48f4-a7e6-232fb48cc17c)

```
//sharvari murade
//23070123088
//entc-b1

#include <iostream>
using namespace std;
int main(){
    string password;
    cout<<"Enter password: ";
    cin>> password;
    if(password=="Password"){
        cout<<"Access Granted";
    } else {
        cout<<"Access Denied";
    }
    return 0;
}
```
### Output-
![7FA7ADB8-2A7C-419C-AABF-2EDDD8ECE361](https://github.com/user-attachments/assets/c1afcd64-cb30-495f-9df4-a33e029ec2e7)

```
//sharvari murade
//23070123088
//entc-b1

#include <iostream>
using namespace std;

int main() {
  int a,b,c;
  cout << "Enter a number: ";
  cin >> a;
  if(a>7){
      cout<<"Enter valid number";
  } else { 
      switch(a){
          case 1:
          cout<<"Monday";
          break;
          case 2:
          cout<<"Tuesday";
          break;
          case 3:
          cout<<"Wednesday";
          break;
          case 4:
          cout<<"Thursday";
          break;
          case 5:
          cout<<"Friday";
          break;
          case 6:
          cout<<"Saturday";
          break;
          case 7:
          cout<<"Sunday";
          break;
        }
  }
  return 0;
 }
```
### Output-
![5D894274-44BA-4BE6-AA00-992140B98DC9](https://github.com/user-attachments/assets/554a5329-3ea6-43e4-8ce8-e893b432079b)

## Conclusion-


Decision-making statements in programming, such as if-else, nested if-else, and switch, are essential for controlling the flow of execution. They allow programs to perform different actions based on conditions, enabling complex decision-making and tailored responses to varying inputs.
