In this project, I try to solve parametric Laplacian equation problem by using Physics-Informed Neural Networks (PINNs) and Deep Ritz Method (DRM).
There are 3 parametric problems. p-Right Hand Side, p-domain and p-exponent.
For each cases, I compared the result from PINNs, DRM and PINNs-DRM hybrid method.
The hybrid method is my original method from research with my advisor Seungchan Ko.
During our performance evaluation of PINNs and DRM, we observed that the two methods exhibit weaknesses in different aspects.
PINNs have a problem to deal with nonlinear problem, and the performance of DRM varies depending on the governing equation since it uses energy function as a loss term.
Frome this analysis, we thought that these two methods can complement each other.
