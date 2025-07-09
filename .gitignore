#include <stdio.h>
#include <math.h>

int min_steps(int x, int y) {
    int d = y - x;
    if (d == 0) return 0; 

    int n = (int)sqrt(d); 
    if (n * n == d) return 2 * n - 1;
    else if (n * n < d && d <= n * (n + 1)) return 2 * n;
    else return 2 * n + 1;
}

int main() {
    int x, y;
    printf("Введіть x і y: ");
    scanf("%d %d", &x, &y);

    int steps = min_steps(x, y);
    printf("Мінімальна кількість кроків: %d\n", steps);

    return 0;
}
