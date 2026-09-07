# Question
Given an integer array and a target value, count how many times the target appears in the array using Linear Search.

```cpp
#include<iostream>

int main(){
  int arr[] = {1,2,2,3,4,5,5,6,5,7,2};
  int target = 5;
  int count = 0;
  for(int i=0; i<arr.size(); i++){
    if(arr[i] == target) count++;
  }
  cout << "Target appears total" << cout << "times";
  return 0;
}
```