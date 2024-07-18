# Rosenbrock Function Optimization

This project demonstrates the optimization of the Rosenbrock function using the `scipy.optimize.minimize` function from the SciPy library and visualizes the results using `matplotlib`.

## Rosenbrock Function

The Rosenbrock function is defined as:

\[ f(x, y) = (a - x)^2 + b(y - x^2)^2 \]

where \( a \) and \( b \) are constants. The function has a global minimum at \( (a, a^2) \).

### Facts about the Rosenbrock Function

- **Commonly used for testing optimization algorithms:** The Rosenbrock function is a classic test problem for optimization algorithms due to its non-convex nature and the narrow, curved valley containing the minimum, which makes it challenging for many optimization techniques.
  
- **Known as the "Rosenbrock's valley" or "Rosenbrock's banana function":** The function is often referred to as the banana function because of the banana-shaped contours in the function's plot.
  
- **Global minimum:** The global minimum of the Rosenbrock function is at \( (a, a^2) \), typically (1, 1) for the default values of \( a \) and \( b \). At this point, the function value is zero.
  
- **Used in machine learning and artificial intelligence:** The function is used to evaluate the performance of optimization algorithms in machine learning, particularly for those involved in training machine learning models.


## Getting Started

### Prerequisites

To run the code, you'll need to have Python and the following libraries installed:

- numpy
- scipy
- matplotlib

### Installing

You can install the required libraries using the `requirements.txt` file:

```bash
pip install -r requirements.txt
