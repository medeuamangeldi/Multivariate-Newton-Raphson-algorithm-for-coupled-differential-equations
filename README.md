# Multivariate-Newton-Raphson-algorithm-for-coupled-differential-equations

File "multivariate_newton_raphson_test_code_for_coupled_ode.py" is just a test code to solve some simple system of ordinary differential equations shown below.

dy_1/dt = -0.04*y_1 + 10^4*y_2*y_3
dy_2/dt = 0.04*y_1 - 10^4*y_2*y_3 - 3*10^7*(y_2)^2
dy_3/dt = 3*10^7*(y_2)^2

with initial condition y_1(0), y_2(0), y_3(0) = 1, 0, 0
