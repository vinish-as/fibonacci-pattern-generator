# Fibonacci Pattern Generator

An interactive web application that generates and visualizes Fibonacci sequences with multiple pattern representations.

## Features

- **Number Pattern Display** - Shows the complete Fibonacci sequence
- **Triangular Pattern** - Creates a triangle where each row contains Fibonacci numbers
- **Step-by-Step Variable Trace** - Visualizes the algorithm variables (fnm2, fnm1, fn) at each iteration
- **Fibonacci Spiral** - Draws a spiral based on the sequence values
- **Responsive Design** - Works on desktop and mobile devices

## How It Works

The application follows the iterative algorithm A4:
procedure A4
read(n)
if n < 0 then [print (‘error’); stop]
if n = 0 then [print (‘0’); stop]
if n = 1 then [print (‘1’); stop]
fnm2 ← 0; fnm1 ←1
for i ← 2 to n do
fn ← fnm1 + fnm2
fnm2 ← fnm1
fnm1 ← fn
end
print(fn)
end A4


## How to Use

1. Enter a number `n` in the input field
2. Click the **"Generate"** button or press Enter
3. Explore the four visualization panels:
   - Left: Number sequence and triangular pattern
   - Right: Variable trace and Fibonacci spiral

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Font Awesome Icons
- Canvas API for spiral drawing

## Live Demo

[https://your-username.github.io/fibonacci-pattern-generator/](https://your-username.github.io/fibonacci-pattern-generator/)

*(Replace 'your-username' with your actual GitHub username)*

## Screenshots

*(You can add screenshots here later)*

## Author

Your Name

## License

This project is open source and available under the [MIT License](LICENSE).
