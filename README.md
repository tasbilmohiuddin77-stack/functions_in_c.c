# functions_in_c.c
#include &lt;stdio.h>  int max_of_four(int a, int b, int c, int d) {     int max = a;      if (b > max)         max = b;     if (c > max)         max = c;     if (d > max)         max = d;      return max; }  int main() {     int a, b, c, d;      scanf("%d", &amp;a);     scanf("%d", &amp;b);     scanf("%d", &amp;c);     scanf("%d", &amp;d);      
