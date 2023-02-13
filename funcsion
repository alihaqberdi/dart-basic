#A simple function that returns the square of a number:
int square(int num) {
  return num * num;
}


#A function that calculates the factorial of a number:
int factorial(int num) {
  int result = 1;
  for (int i = 1; i <= num; i++) {
    result *= i;
  }
  return result;
}



#A function that concatenates two strings:
String concatenate(String str1, String str2) {
  return str1 + str2;
}



#A function that returns the larger of two numbers:
int max(int num1, int num2) {
  if (num1 > num2) {
    return num1;
  } else {
    return num2;
  }
}


#A function that returns the smaller of two numbers:
int min(int num1, int num2) {
  if (num1 < num2) {
    return num1;
  } else {
    return num2;
  }
}


#A function that calculates the hypotenuse of a right triangle:
double hypotenuse(double a, double b) {
  return sqrt(a * a + b * b);
}


#A function that checks if a number is even:
bool isEven(int num) {
  return num % 2 == 0;
}


#A function that checks if a number is odd:
bool isOdd(int num) {
  return num % 2 != 0;
}


#A function that checks if a number is prime:
bool isPrime(int num) {
  if (num <= 1) {
    return false;
  }
  for (int i = 2; i <= sqrt(num); i++) {
    if (num % i == 0) {
      return false;
    }
  }
  return true;
}


#A function that calculates the power of a number:
double power(double base, int exponent) {
  double result = 1;
  for (int i = 0; i < exponent; i++) {
    result *= base;
  }
  return result;
}


#A function that calculates the Fibonacci number at a given index:
int fibonacci(int index) {
  if (index == 0 || index == 1) {
    return index;
  }
  return fibonacci(index - 1) + fibonacci(index - 2);
}


#A function that calculates the GCD of two numbers:
int gcd(int num1, int num2) {
  int remainder;
  while (num2 != 0) {
    remainder = num1 % num2;
    num1 = num2;
    num2 = remainder;
  }
  return num1;
}
