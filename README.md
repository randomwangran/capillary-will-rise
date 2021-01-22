<img src="images/capillary-will-rise.png" align="right">


# capillary-will-rise

下表面给定速度为零的边界条件。上表面假定接触大气。墙面无滑移。

关键点在

    walls
    {
        type           constantAlphaContactAngle;
        theta0         45;
        limit          gradient;
        value          uniform 0;
    }

假定接触角 45 度。可以观察到计算 0.5 秒后，水和空气界面稍微上升一点距
离。


# What is this?

The equation to the surface can be written:

\(z-\zeta(x, y)=0\)

Tensile force can be written:

\(-\gamma \oint \mathbf{n} \times d \mathbf{x}\)

Somehow the equilibrium becomes to:

\(\rho g H=\Delta p=\frac{2 \gamma \cos \theta}{a}\)

And finally the conclusion

\(H=\frac{2 d^{2} \cos \theta}{a}\)


# Contributing

Yes, please do! See [CONTRIBUTING][] for guidelines.


# License

See [COPYING][]. Copyright (c) 2021 Ran Wang.

[CONTRIBUTING]: ./CONTRIBUTING.md
[COPYING]: ./COPYING
