In this project, I try to solve parametric Laplacian equation problem by using Physics-Informed Neural Networks (PINNs) and Deep Ritz Method (DRM).
There are 3 parametric problems. p-Right Hand Side, p-domain and p-exponent.
For each cases, I compared the result from PINNs, DRM and PINNs-DRM hybrid method.
The hybrid method is my original method from research with my advisor Seungchan Ko.

The reason why we dealed with parametric problem is a weakness of traditional numerical methods, which is they have to train model every time to make result for different parameters, since they are mesh-based methods.

During our performance evaluation of PINNs and DRM, we observed that the two methods exhibit features in different aspects.
PINNs have a problem to deal with nonlinear problems, but have a high accuracy at the collocation points.
On the other hand, performance of DRM varies depending on the governing equation since DRM uses loss function be consist of energy function which includes weak formulation of governing equation. This implies that DRM has a priority to deal with high-dimensional problems and to catch the global position of solution.
Frome this analysis, we found a clue that these two methods can complement each other. So we experimented this idea, and made the hybrid method.

In this codes, we found a optimal architecture for each neural network by repeating experiments couple of times.
