# Tailwind CSS Gradient Issue

This repository demonstrates a bug where Tailwind CSS gradients aren't rendering correctly.  The expected output is a smooth color transition, but the actual output is a solid color.

## Bug Description

A simple gradient applied to a div element using Tailwind CSS does not render the expected gradient.  Instead of a smooth transition between the specified colors, a solid color is displayed.

## Solution

The issue was resolved by ensuring the correct order of classes and updating the Tailwind CSS configuration to include the necessary color palettes.

## How to Reproduce

1. Clone this repository.
2. Install Tailwind CSS (if not already installed).
3. Run a development server (e.g., using Vite or Webpack). 
4. Observe the rendered gradient in the browser.  It should be solid, not a gradient.
5. Check the bugSolution file to see how the gradient has been corrected. 
