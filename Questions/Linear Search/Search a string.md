# Question
Given an array of strings and a target string, find whether the target exists using Linear Search.

```cpp
#include<iostream>
#include<string>
using namespace std;

int main(){
  string arr[] = {"hi", "my", "name", "is", "Ashutosh"};
  string target = "name";
  int size = sizeof(arr)/sizeof(arr[0]);
  for(int i=0; i<size; i++){
    if(arr[i] == target){
      cout << "Yes Exists";
      break;
    }
  }
  return 0;
}
```