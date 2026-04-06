### What is accelerometer?
Accelerometer is a sensor which measures acceleration as the name says. However it is not merely the change in velocity, it is the force which the sensor measures per unit mass.It can't distinguish between actual velocity change and the gravity. Also the acceleration is measured along an axis and hence fails to captureanugular movement which is the work of a gyroscope.
A few examples to understand it better can be --- a phone kept on a table shows no chnage in velocity however the accelrometer reads 9.8m/s2 becoz of the normal force that is pushing it upwards.
When u tilt your phone, there is not much change in velocity rather the component of gravity acting on the sensor changes and thus the acceleration. A person experiencing a free fall shows 0 acceleration beocz there is no pressing or pushing force acting on the person.
### The mass-spring-damper model
Every accelerometer is made up of a spring, a mass hanging to the spring and a damper which reduces vibration.When the snesor body moves,the mass stays there becoz of inertia and thus looks displaced as compared to the sensor.The is wht the accelerometer measures, the displacement of the proof mass.
It combines the 2 equations f=ma and f=kx, thus a=kx/m, hence a becomes a function of displacement.
### Working principle
Uses MEMS (micro electro mechanical system) i.e the elctrical and mechanical componenets together and capacitive sensing. Now lets try to visualize the structure of an accelerometer. There is one proof of mass which looks like a double sided comb having sensing fingers on both the sides and these fingers dont touch, however get correctly placed between the gaps of electrodes. The mass is tethered to a substrate. Every snesing finger sits between two electrodes , forming 2 capacitors. Due to motion when the mass moves, the distance between the finger changes wrt the electrodes. This if u consider a pair of electrodes and a finger in the middle, at a given moment, the capacitance of one increases while the other decreases becoz of the chnage in the distance between ecah pair of plates. This forms the differential capacitance. This capacitance passes through many phases before the ADC converts it into digital signal which becomes the sensor output. Also a thing to note is that such a structure containing mass, electrodes and substrate can measure acceleration in only one direction. Thus to get in all the 3 axes, 3 such structures are used. 
Below shown are some visualizations for better understanding.

![Image](https://github.com/user-attachments/assets/e99b2ad9-d860-4217-a3d3-6893d855971a)

![Image](https://github.com/user-attachments/assets/c3c832b4-4774-4bac-aaa9-a7c3e56e218d)

The above readings are from a real accelerometer , the first 3 readings show that mojorly its gravity that is acting , rest ax and ay may be becoz of the bias or noise/environmental error etc.
