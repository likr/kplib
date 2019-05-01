# kplib

Test instances for 0-1 knapsack problems

The instances were generated according to the following book chapter. 

> Kellerer, H., Pferschy, U., & Pisinger, D. (2004). Exact solution of the knapsack problem. In Knapsack Problems (pp. 117-160). Springer, Berlin, Heidelberg.

The generation code is available here.

* https://bitbucket.org/likr/mnkproblems/
* https://bitbucket.org/likr/mnkptools/

(However, updating this code has stopped...)

## Data format

The following equation is a formulation of 0-1 knapsack problems.

<img src="https://latex.codecogs.com/gif.latex?%5Cbegin%7Baligned%7D%20%5Cmax%20%26%20%5Csum_%7Bi%3D1%7D%5En%20p_i%20x_i%20%5C%5C%20%5Ctext%7Bs.t.%7D%20%26%20%5Csum_%7Bi%3D1%7D%5En%20w_i%20x_i%20%5Cleq%20c%2C%20%5C%5C%20%26%20x_i%20%5Cin%20%5C%7B0%2C%201%5C%7D.%20%5Cend%7Baligned%7D" />

A problem instance are described in the following data format in `.kp` file.

```
n
c

p_1 w_1
p_2 w_2
…
p_n w_n
```


## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
