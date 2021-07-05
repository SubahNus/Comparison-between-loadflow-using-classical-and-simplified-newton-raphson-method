# Comparison-between-loadflow-using-classical-and-simplified-newton-raphson-method
In this project, we wanted to implement simplified Newton Raphson for solving load
flow using MATLAB along with the classical one and then compare both models.
In PSAF, we compute the load flow using general Newton Raphson formula. If we
use a lot of bus data and try to simulate it, the software takes some times to give the
output report. On the other hand, if we implement the system using simplified
Newton Raphson, the output report will not take too much time. So, we can also
implement this system at the low configuration PCs easily.
The standard NR power flow method is one of the most powerful algorithms, which
has long history of development, and is widely used to develop commercial powerflow
solution software. Although the standard NR power flow method is very
efficient and commonly used for the power flow calculation to formulate iterative
Jacobian updating matrix equations requires complicated formulae and long
expressions. However, essential difference between NR and SNR (simplified
newton-raphson) is that the proposed algorithm is to find roots of the current
mismatch equations instead of those of the power mismatch equations. This
approach can simplify a very long and complicated mathematical formula to a very
simplistic and short mathematical expression. With this simplification, reduction of
the overall execution time is expected.
