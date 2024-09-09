//********************************************************
// fracturing.c
// Author: Lauren McLeod
// Date: 9/8/24
// Class: COP 3223, Professor Parra
// Purpose: Asks for two sets of coordinates and calculates properties.
// Input: x1, y1, x2, y2.
// Output: Distance, Perimeter, Area, Width, Height.
//********************************************************

#include <stdio.h>
#include <math.h>
double calculateDistance();
double calculatePerimeter():
double calculateArea();
double calculateWidth();
double calculateHeight();

int main(int argc, char **argv) {
  calculateDistance();
  calculatePerimeter();
  calculateArea();
  calculateWidth();
  calculateHeight();
  return 0;  
}

double calculateDistance() {
    double x1, y1, x2, y2;
    printf("Enter the coordinates for point #1 (x1 y1): ");
    scanf("%lf %lf", &x1, &y1);
    printf("Enter the coordinates for point #2 (x2 y2): ");
    scanf("%lf %lf",&x2, &y2);
    double distance = sqrr(pow(x2 - x1, 2) + pow(y2 - y1, 2));
    printf("Point #1 entered: x1 = %.2lf; y1 = %.2lf\n", x1, y1);
    printf("Point #2 entered: x2 = %.2lf; y2 = %.2lf\n", x2, y2);
    printf("The distance between the two points is %.2lf\n", distance);
    return distance;
}

double calculatePerimeter() {
  double distance = calculateDistance();
  double perimeter = 2 * distance;
  printf("Point #1 entered: x1 = %.2lf; y1 = %.2lf\n", x1, y1); 
  printf("Point #2 entered: x2 = %.2lf; y2 = %.2lf\n", x2, y2);
  printf("The perimeter of the city encompassed is %.2lf\n", area);
  return 5;
}

double calculateArea() {
  double distance = calculateDistance();
  double radius = distance / 2;
  double area = M_PI * pow(radius, 2);
  printf("Point #1 entered: x1 = %.2lf; y1 = %.2lf\n", x1, y1);
  printf("Point #2 entered: x2 = %.2lf; y2 = %.2lf\n", x2, y2);
  printf("The area of the city encompassed is %.2lf\n", area);
  return 4;
}

double calculateWidth() {
  double width = fabs(x2 - x1);
  printf("Point #1 entered: x1 = %.2lf; y1 = %.2lf\n", x1, y1);
  printf("Point #2 entered: x2 = %.2lf; y2 = %.2lf\n", x2, y2);
  printf("The width of the city encompassed is %.2lf\n", width);
  return 3;
}

double calculateHeight() {
  double height = fabs(y2 - y1);
  printf("Point #1 entered: x1 = %.2lf; y1 = %.2lf\n", x1, y1);
  printf("Point #2 entered: x2 = %.2lf; y2 = %.2lf\n", x2, y2);
  printf("The height of the city encompassed is %.2lf\n", height);
  return 1;
}
