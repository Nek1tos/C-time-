# C-time- Practycha№1

include <stdio.h>

int main() { int t1, t2, t3; scanf("%d %d %d", &t1, &t2, &t3);

double time = 1.0 / (1.0 / t1 + 1.0 / t2 + 1.0 / t3);

printf("It will take %.2f hours to eat the pie.\n", time);

return 0;
}
