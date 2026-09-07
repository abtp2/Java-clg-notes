# Question
Given an integer array and a target value, find the index of its last occurrence using Linear Search.


```cpp
#include<iostream>

int main(){
  int arr[] = {1,2,2,3,4,5,2,3,5,4,1,2};
  int target = 2;
  int index = 0;
  for(int i=0; i<arr.size(); i++){
    if(arr[i] == target){
      index = i;
    }
  }
  cout << index;
}
```