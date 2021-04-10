## TemperatureTube

TemperatureTube is a real-time temperature simulator for a tube, in which a fluid is flowing. It can be used to calculate and visualize the temperature of the outer surface of the tube in models of industrial rooms, machines and units, laboratory equipment. 

The length, diameter and wall thickness of the tube may vary. Flow rate *g* (τ), flow temperature at the inlet to the tube *t* (τ) and ambient temperature *a* (τ) are non-stationary and can changeg  over time according to dependence:

*f* (τ) = *a* + *b* × Sin (*c* × τ).

Such the dependence is universal, it can establish constant and variables values of parameters with a wide or narrow range of variation.

Now the tube is made from Steel, and Water flows inside it. Other materials that can be used to make the pipe (for example, *Plastic*,...), as well as other substances that flow in the pipe (for example, *Air*,...) can be added.

### Simulators Unity version

The Unity version of the simulator is available [here](https://assetstore.unity.com/packages/slug/192521?_ga=2.52409002.2012061589.1617710108-1802814762.1615540003). 

<div align="center"><iframe width="100%" height="50%" src="https://www.youtube.com/embed/c65wOoncqSc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

It focuses on the representation of the temperature field of the tube in the form of a color gradient. Gradient is generated dynamically based on the calculation of the temperature field. The calculation of the temperature field is performed every 0.2 seconds, those 5 times per second. 

The picture shows five tubes of various diameters and wall thicknesses in interior. The dependences of the change in flow rate and water temperature in them are different. Below is another picture from a different angle. 

<div align="center"><img src="https://software-twins.github.io/png/14-37-07.png" alt="TemperatureTube Example" width="640" height="335" /></div>

Tube does not yet show the water that flows inside, because this is not necessary to represent the temperature field of the outer wall.

<div align="center"><iframe width=screen.width / 3 height="360" src="https://www.youtube.com/embed/C4dRCUZlSEM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
