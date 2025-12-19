#include <stdio.h>

int main() {
    int arr[100] = {10, 20, 30, 40, 50};
    int size = 5;
    int i, temp;

    / traversal /
    for (i = 0; i < size; i++)
        printf("%d ", arr[i]);
    printf("\n");

    / reverse /
    for (i = 0; i < size / 2; i++) {
        temp = arr[i];
        arr[i] = arr[size - 1 - i];
        arr[size - 1 - i] = temp;
    }

    for (i = 0; i < size; i++)
        printf("%d ", arr[i]);
    printf("\n");

    / insertion (index 2, value 25) /
    for (i = size; i > 2; i--)
        arr[i] = arr[i - 1];
    arr[2] = 25;
    size++;

    for (i = 0; i < size; i++)
        printf("%d ", arr[i]);
    printf("\n");

    / deletion (index 3) /
    for (i = 3; i < size - 1; i++)
        arr[i] = arr[i + 1];
    size--;

    for (i = 0; i < size; i++)
        printf("%d ", arr[i]);
    printf("\n");

    return 0;
}
