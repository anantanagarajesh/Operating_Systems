#include <stdio.h>

void transpose(int p[3][3], int t[3][3]);

int main() {
  int i, j, row, col;
  int p[3][3], t[3][3];

  for (i = 0; i < 3; i++) {
    for (j = 0; j < 3; j++) {
      printf("Enter the elements of matrix P [%d,%d]: ", i, j);
      scanf("%d", & p[i][j]);
    }
  }
  
 for (row = 0; row < 3; row++) {
    for (col = 0; col < 3; col++) {
      t[row][col] = p[col][row];
    }
  }
 
  printf("Transpose of matrix P is:\n\n");

  for (i = 0; i < 3; i++) {
    for (j = 0; j < 3; j++) {
      printf("%d ", t[i][j]);
    }
    printf("\n");
  }
}
