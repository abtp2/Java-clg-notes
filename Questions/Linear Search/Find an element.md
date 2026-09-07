# Question
Given an integer array and a target value, find the index of the target using Linear Search. If not found, return -1.


```cpp
#include<iostream>

int main(){
  int arr[] = {1,2,3,4,5,6};
  int target = 4;
  for(int i=0; i<arr.size(); i++){
    if(arr[i] == target){
      cout << i;
      break;
    }
  }
}
```