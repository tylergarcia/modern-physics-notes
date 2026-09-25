# Exam 1 Review

### Visual Aids
[[adding-speeds.html]] Visual Aid – Relativistic Velocity Addition
[[doppler-effect.html]] Visual Aid - Doppler Effect
[[light-clock.html]] Visual Aid - Moving Clocks Run Slower
[[twin-paradox.html]] Visual Aid - Twin Paradox
[[what-each-transformation-keeps.html]] Visual Aid - What Does Each Transformation Keep?

## Galilean Transformation
$$
\begin{aligned}x'&=x-vt \newline
y' &= y \\ z' &= z  \\ t' &= t
\end{aligned}
$$
When considering motion in one direction $x$, the new $x'$ coordinate is just $x$ with the new distance $vt$ added/subtracted. Crucially, time is invariant. 

### Problem 1b: Show $a'=a$ invariant under Galilean Transformations**
$$ \begin{aligned} x' &= x - vt, \quad t' = t \quad \text{(assumed: } dt' = dt\text{)} \\[1em] \frac{dx'}{dt} &= \frac{dx}{dt} - \frac{d(vt)}{dt} \\[1em] u' &= u - v \quad \text{(}v\text{ constant)} \\[1em] \frac{du'}{dt} &= \frac{du}{dt} - \frac{dv}{dt} \\[1em] a' &= a - 0 = a \end{aligned} $$

### Problem 1b: Show $F=ma$ invariant under Galilean Transformations
$$ \begin{aligned} F &= ma \\ a' &= a \quad \text{(previous result)} \\ m' &= m \quad \text{(assumed: mass is invariant)} \\ \therefore F' &= m'a' = ma = F \end{aligned} $$



# Michelson Morley
**[Visual Aid - Moving Clocks Run Slow](https://claude.ai/artifact/Gjw41yUXESAb3WudkFYwy8)**

![[Pasted image 20260924145208.png|413]]
### Problem 2a: Parallel arm light travel time 
*show that light travel time is $t_\parallel =\frac{2L}{c}\frac{1}{1-\frac{v^2}{c^2}}$*

In image, blue line shows the light travel path L. 
Since $t=\frac dv$,  $t=\frac{L}{c-v}$ on the way there, $t=\frac{L}{c+v}$ on the way back. 
	We are assuming $c$ is variant based on the direction of the ether wind, an assumption in the original experiment that we now know to be false. 
Total is $t_\parallel=\frac{L}{c-v}+\frac{L}{c+v}$
To get to the shown result  $t_\parallel =\frac{2L}{c}\frac{1}{1-\frac{v^2}{c^2}}$:


$$ \begin{aligned} t_{\parallel} = \frac{L}{c-v} + \frac{L}{c+v} \\[1em] = \frac{L(c+v)}{(c-v)(c+v)} + \frac{L(c-v)}{(c+v)(c-v)} \\[1em] = \frac{L\left[(c+v) + (c-v)\right]}{c^2 - v^2} \\[1em] = \frac{2Lc}{c^2 - v^2} \\[1em] = \frac{2Lc}{c^2\left(1 - \frac{v^2}{c^2}\right)} \\[1em] = \frac{2L}{c}\,\frac{1}{1 - \frac{v^2}{c^2}} \end{aligned} $$


### Problem 2b: Perpendicular arm light travel time 
To understand how we are interpreting the perpendicular arm of the Michelson Morley experiment, think of swimming across a river. 
- The river is $L$ wide
- The current (ether wind) flows sideways at $v$
- You swim at speed $c$ relative to the river
To swim across to the opposite bank directly across from where you started, you have to swim at an angle upstream. Part of your speed $c$ gets spent cancelling the current and only what's left carries you across. 
$$t_1 = \frac{d}{v}=\frac{\text{width}}{\text{speed across}}=\frac{L}{\sqrt{c^2-v^2}}$$See that in the case of $v=0$, the water isn't moving and you can swim back and forth in a straight line. The distance across is $L$, and since $t=\frac dv$, we divide by velocity to get the time we want. ![[Pasted image 20260923210649.png]]

**Solution:**
Show that light travel time is $t_\perp = \frac{2L}{c}\frac{1}{\sqrt{1-\frac{v^2}{c^2}}}$

In the ether frame, the light travels at speed $c$ along a diagonal path.
Let $t_1$ be the time for one leg (mirror to mirror).
In that time the light travels $ct_1$ along the diagonal, the apparatus moves $vt_1$ sideways, and the perpendicular distance is $L$.
By the Pythagorean theorem:

$$
\begin{aligned}
(ct_1)^2 &= L^2 + (vt_1)^2 \\[1em]
c^2 t_1^2 - v^2 t_1^2 &= L^2 \\[1em]
t_1^2 (c^2 - v^2) &= L^2 \\[1em]
t_1 &= \frac{L}{\sqrt{c^2 - v^2}}
\end{aligned}
$$

By symmetry, the return leg takes the same time, so the total is:

$$
\begin{aligned}
t_{\perp} &= 2t_1 \\[1em]
&= \frac{2L}{\sqrt{c^2 - v^2}} \\[1em]
&= \frac{2L}{\sqrt{c^2\left(1 - \frac{v^2}{c^2}\right)}} \\[1em]
&= \frac{2L}{c\sqrt{1 - \frac{v^2}{c^2}}} \\[1em]
&= \frac{2L}{c}\,\frac{1}{\sqrt{1 - \frac{v^2}{c^2}}}
\end{aligned}
$$




## Proper Time/Length
*Must be moving WITH the thing you are measuring to define proper time/length*

Proper time is the time registered by a clock traveling along with an observer, literally the time recorded on your own wristwatch as you move through space. It is the duration of physical time that actually elapses for you between two events that occur at your position.

Proper length is the length of an object measured in the frame where the object is at rest, like by a ruler traveling along with the object. Since the ends of the object aren't moving in the frame, you can measure them at any time and get the same answer. When the object moves past an observer in another frame, that observer must mark both ends at the same moment in their own frame. The two frames disagree about what "the same moment" means, so the observer measures a shorter length, $L = L_0/\gamma$. This is length contraction: a real measurement, and the partner of time dilation, since both follow from $c$ being the same for everyone.

# Problem 5b - Twin Paradox/Spacetime diagram:
**[Visual Aid - Twin Paradox](https://claude.ai/artifact/Cibbv2F3QZuV2f7yHpSTKk)**

![[Pasted image 20260924151357.png|356]]

The diagram is a spacetime diagram of the twin paradox. Frank's worldline is vertical (he is at rest), Mary's worldline travels out and back, and the 45° lines are light signals exchanged between them.

Signals arrive sparsely while Mary recedes, because her clock runs slow in Frank's frame and each signal must also cross a growing distance (**redshift**). They arrive densely as she returns, because the distance is shrinking (**blueshift**).

These are the redshift and blueshift of the **relativistic Doppler effect**, governed by:

$$
f_{\text{obs}} = f_{\text{src}}\sqrt{\frac{1\pm\beta}{1\mp\beta}}, \qquad \beta = \frac{v}{c}
$$

(upper signs for approaching, lower for receding). For $\beta = 0.8$, the factors are 3 and $\tfrac{1}{3}$.

#### Crucial to remember:
Moving clocks run slow to the observer at rest. Motion through space costs motion through time. The faster something moves through space, the slower it moves through time to an observer at rest. 

## Doppler Effect
**[Visual Aid - Doppler Effect](https://claude.ai/artifact/CsUMKVbCoxsz5eJGJ96bN5)**

### Light speed vs frequency
- Speed and frequency are independent
- $c=f\lambda$ for light, so different observers can measure different $f$ and $\gamma$ while their product stays locked exactly at $c$ 
- Analogy: Cars on highway, all going exactly 60mph. If the cars on the on-ramp are allowed to merge more often, more cars go by (higher frequency) while none actually exceed 60mph.
- Frames disagree about time intervals and positions - the Lorentz transformations say how much
- Therefore, frames disagree about how often crests arrive, so they disagree about frequency, and we call that the Doppler shift. 
## Relativistic Velocity Addition
**[Visual Aid - Relativistic Velocity Addition](https://claude.ai/artifact/P291rML5r4NpxQwy9B5zpa)**
