```c
void solve(double meal_cost, int tip_percent, int tax_percent) {
  double total;
  double tip,tax;
   
  tip = meal_cost*tip_percent/100;
  tax = meal_cost*tax_percent/100;
  total = meal_cost + tip + tax;
  
  printf("%.0lf",round(total));
}
```
