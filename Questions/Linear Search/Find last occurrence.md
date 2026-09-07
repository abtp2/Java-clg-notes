# Question
Given an integer array and a target value, find the index of its last occurrence using Linear Search.


```cpp
#include<iostream>
using namespace std;

int main(){
  int arr[] = {1,2,2,3,4,5,2,3,5,4,1,2};
  int target = 2;
  int index = 0;
  int size = sizeof(arr)/sizeof(arr[0]);
  for(int i=0; i<size; i++){
    if(arr[i] == target){
      index = i;
    }
  }
  cout << index;
}
```