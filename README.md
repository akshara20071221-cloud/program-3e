# program-3e
# 🧪 C Programming Lab
## 📘 Experiment No: 3e
### 🔹
**Date:** 13/3/2026  
**Name:** AKshara.k 
**Register No:** 25003090 

---

## 🎯 AIM
 To write a C program to count the number if odd and even elemets in an array.
---

## 🧠 ALGORITHM
1.Get an array as input from the user.
2.Count the number of odd and even elements by using for loop and if else statements.
3.Print the number of odd and even elements using printf() function.
---

## 💻 PROGRAM

```

#include<stdio.h>
int main()
{
    int num,odd=0,even=0;
    scanf("%d",&num);
    int arr[num];
    for(int i=0;i<num;i++)
    {
        scanf("%d",&arr[i]);
    }
    for(int j=0;j<num;j++)
    {
        if(arr[j]%2==0)
        even++;
        else
        odd++;
        
    }
    printf("Total even elements: %d\n",even);
    printf("Total odd elements: %d",odd); 
}
```

## 🖼️ OUTPUT SCREENSHOT

<img width="828" height="141" alt="image" src="https://github.com/user-attachments/assets/28c632e8-ce3e-4dd1-bcf3-35ac6010a0e9" />


---

## ✅ RESULT
: Thus the C program to count the number of odd and even elements in a given array is executed successfully.
