Download Link : https://programming.engineering/product/the-bias-variance-tradeoff-svms-and-kernel-methods/

# The-Bias-variance-Tradeoff-SVMs-and-Kernel-Methods
The Bias-variance Tradeoff, SVMs and Kernel Methods
Questions

Please finish the programming part first.

1. RBF Kernel (2 points) As discussed in class, the RBF kernel is defined as

                            K(x, x′) = e−γ∥x−x′ ∥22
                            	

                            (1)

Hopefully, from the programming part, you have already gotten a sense about how the hyper-parameter γ impact the model performance. Based on your observation and Equation 1, please give an intuitive explanation about how γ could impact model complexity. Your answer should cover

        Whether higher or lower values leads to more flexible models, and

        Why?

    Polynomial Kernels (3 points) In our lecture on kernel methods, we show that a special case of the polynomial kernels

                            K(x, x′) = ( x, x′ + c)d
                            	

                            (2)

with d = 2 and x, x′ ∈ R2. On our lecture slides, we show how this special case can be decomposed as a dot product with a nonlinear mapping Φ(·)

                        K(x, x′) = Φ(x), Φ(x′) .
                        	

                        (3)

In this problem, consider d = 3 with x, x′ ∈ R2 and show how the Φ(x) is defined in this case. Note that, before splitting the kernel function to be a dot product of two high-dimensional vectors, make sure merge the same items as much as you can, as we demonstrated in class.

1
