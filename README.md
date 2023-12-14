#include <iostream>
using namespace std;
bool Even(double Number);
int main(){
double Number;
cout<<"Enter the number:";
cin>>Number;
cout<<boolalpha<<Even(Number);
return 0;
}
bool Even(double Number){
if(Number > 0){
return true;
}else{
return false;
}
}
