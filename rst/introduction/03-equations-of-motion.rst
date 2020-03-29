Equations of Motion
###################

Let's start off by considering a simple ball launched at some angle $\alpha$ relative to the horizon with an initial velocity of $v_0$. Based on what you know from playing with such an object. The ball will travel up for some distance, then fall to the Earth. We can define the velocity of the ball t any moment in terms of two parts. One part describes the motion parallel to the horizon, and the other part defines the motion vertically. At any moment in time, the ctual velocity of the ball is a vector with a $v_x$ and a $v_y$ component. The vector equation for this velocity looks like this:

..  math::

    \overrightarrow{v} = v_x \hat{i} + v_y \hat{j}

Here is SymPy_ at work

.. mathcode::

    import sympy
    a, b = sympy.symbols('a, b')
    a * 10 + 2 * b
