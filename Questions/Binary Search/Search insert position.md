# Question
Given a sorted array and a target value, find the index where the target should be inserted to maintain the sorted order


```cpp
#include <iostream>
using namespace std;

int main(){
    int arr[] = {1, 3, 4, 5, 6, 8};
    int target = 5;
    int n = sizeof(arr)/sizeof(arr[0]);
    int left=0, right=n-1;
    int index = n;
    while (left<=right){
        int mid = (left+right)/2;
        if(arr[mid]>=target){
            index = mid;
            right = mid-1;
        } 
        else{
            left = mid+1;
        }
    }
    cout << index;
    return 0;
}
```