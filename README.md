# 25331a05d8-pointer
#include <stdio.h>

int main() {
    int arr[5] = {10, 20, 30, 40, 50};
    int *ptr;

    ptr = arr; 
    printf("_25331a05d8_\n");

    printf("Pointer Arithmetic:\n");

    for(int i = 0; i < 5; i++) {
        printf("Value = %d, Address = %p\n", *ptr, ptr);
        ptr++;
    }

    return 0;
}
