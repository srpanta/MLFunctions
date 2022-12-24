## Fubnctions:
Some important functions that are used in ML and Dl algorithms are plotted here.Inputs are in x-axis and outputs are in y-axis.
### Logistic or sigmoid Function:
$$sigmoid(z)=\frac{1}{1+exp(-z)}$$
In this function inputs $z$ can be values from the interval $-\infty < z < \infty$ while outputs are in the interval $0 &le; y &le; 1$.
### Hyperbolic tangent or tanh Function:
$$y=tanh(z)$$
In this function inputs $z$ can be values from the interval $-\infty < z < \infty$ while outputs are in the interval $-1 &le; y &le; 1$.
### Step Function:
In this function gives constant output as $1$ if inputs are positive and gives $0$ output if inputs are less than or equal to zero.
### Relu Function:
$$ReLu(x)=x,  x &gt; 0$$
    $$.           =0,  x &le; 0$$
In this function gives constant output as $0$ if inputs are less than zero and gives input value  itself as output if inputs are greater than or equal to zero.
### Leaky Relu Function:
$$lReLu(x)=x,  x &gt; 0$$
    $$.           =ax,  x &le; 0$$
where $a$ is a leaky parameter. Generally $a=0.01$ is used.
In this function gives constant output as $0$ if inputs are less than zero and gives input value  itself as output if inputs are greater than or equal to zero.

## Libraries Used:
pyplot library from Matplotlib is used for plotting.
numpy library is used to create an array of input values.
