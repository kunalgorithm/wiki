# Kinematics

Kinematics is the description of motion. We describe the motion of a point particle using three terms - position, velocity and acceleration.

**Displacement**

$$
\begin{align*}
\Delta \vec{x}\equiv\vec x_f- \vec x_i\
\end{align*}
$$

Displacement answers the question "Has the object moved?"

The $\equiv$ symbol is significant in that is indicates that not only does $\vec{x\_f} - \vec{x\_i}$ equal the displacement $\Delta{\vec{x}}$ but more importantly displacement is **operationally defined** by $\vec{x\_f} - \vec{x\_i}$.

**Velocity**

> Is the object moving now, and if so, how quickly?

$$
\vec{v}_{av}\equiv
\frac{\vec{x_f}-\vec{x_i}}{\vec{t_f}-\vec{t_i}}
\equiv
\frac{\Delta\vec{x}}{\Delta\vec{t}}
$$

Note that this is average velocity. If we want instantaneous velocity, we use displacement steps that are small enough

$$
\vec{v}_{inst}
\equiv
\frac{\vec{\delta{x}}}{\delta{t}}
$$

or if we use limits from calculus, we get

$$
\vec{v_{inst}}
\equiv
\frac{\vec{d{x}}}{d{t}}
$$

where d is assumed to be small enough so that the difference between stepping and smooth-changing in the quantities of distance and time are negligible.

**Acceleration**

> Is the object's velocity changing, and if so, how quickly?

$$
\vec{a}_{av}\equiv
\frac{\vec{v_f}-\vec{v_i}}{\vec{t_f}-\vec{t_i}}
\equiv
\frac{\Delta\vec{v}}{\Delta\vec{t}}
$$

Once again we have the definition for **average acceleration**, whereas instantaneous acceleration can be defined as

$$
\vec{a}_{inst}
\equiv
\frac{\vec{\delta{v}}}{\delta{t}}
$$

and with the help of some calculus

$$
\vec{a_{inst}}
\equiv
\frac{d{\vec{v}}}{d{t}}
=
\frac{d^2{\vec{v}}}{d{t^2}}
$$

**Vectors**

The arrows in the definitions for **displacement, velocity**, and **acceleration** above include an arrow above some of the terms, which indicates that direction is an import part of their definitions. These quantities are **vectors**.

The directions of the vectors acting upon an object can differ.

1. If the direction of velocity and acceleration are the same, the object is speeding up.
2. if they are opposite, the object is slowing down.
3. if they are perpendicular, the object's initial speed remains contanst while the speed in the direction of the acceleration increases. For example, a bullet fired in a horizontal direction will be acted upon by gravity and will therefore accelerate downwards towards the earth. 

General motion is a combination of 1 & 3 or 2 & 3.

**Equations of motion**

A particle with constant acceleration has no changes in velocity.

$$
\frac{d{\vec{v}}}{d{t}}
=
0 \frac{m}{s^2}
$$

Since acceleration is a vector, this means no changes in direction or magnitude, allowing us to derive an equation for velocity as a function of time by integrating the constant acceleration

$$
v(t)= v(0)+\int\limits_{0}^{t}{\bold{a}\ dt}
$$

which gives us the following equation for velocity as a function of time

$$
v(t)=v_0+\bold{a}t
$$

To derive the equation for position we integrate the equation for velocity

$$
\boldsymbol{x}(t)=\boldsymbol{x}(0)+\int\limits_{0}^{t}\boldsymbol{v}(t)\ dt
$$

Integrating again gives the equation for position

$$
\boldsymbol{x}(t)=\boldsymbol{x}_0+\boldsymbol{v}_0t+\frac{1}{2}\boldsymbol{a}t^2
$$

The following are the '''equations of motion''':

| Equation | Description |
| :--- | :--- |
| $\vec{x}=\vec{x}\_0 + \vec{v}\_0 t+\frac{\vec{a}t^2}{2} $ | Position as a function of time |
| $\vec v = \vec v\_0 + \vec a t  $ | Velocity as a function of time |

These equations can be minipulated to either eliminate time or eliminate acceleration.

**What about speed?**

To calculate the average speed, distance travelled, or time taken, we need following formula:

$$
speed=\frac{distance}{time\ taken}
$$

If you have 2 of the 3 values, you can solve for the third.

**Speed vs Velocity**

Keep in mind that velocity is a **vector** quantity that refers to the rate at which an object changes position, whereas speed is a **scalar** quantity, which cannot be negative.

Speed is measured in the same physical measurement as velocity, but does not contain an element of direction. Speed is thus the magnitude component of velocity. Velocity contains both the magnitude and direction components.

## Enter Isaac

Isaac Newton was an English physicist, mathematician \(or "natural philosopher" as it was described during his time\), astronomer, and alchemist. He is most widely known for the development of **classing mechanics** and **calculus**.

### Newton's laws of motion

Newton dictated three laws of motion, which describe the relationship between a body, the forces acting upon it, and its motion in response to said forces.

1. **First Law** \(also referred to as the _law of inertia_\) states that a body in motion will stay in motion. 
2. **Second Law** The vector sum of the external fores F on an object is equal to the mass m of that object multiplied by the acceleration vector a of the object, or $F=ma$.
3. **Third Law** states that one body exerts a force on a second body, the second body simultaneously exerts a force equal in magnitude and opposity in direction on the first body. 

