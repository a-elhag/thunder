# Introduction

![image info](./pictures/Rad.jpeg "Ra'd")
This hunk of wires and circuitery was affectionaly christened **Ra'd** (*thunder in Arabic*) for his sparky and somewhat mercurial behaviour (wasn't breastfed as a child you see).
Went through three **Arduinos** and much heartache, but in the end we managed to tame him.

The project was to build a **Maximum Power Point Tracker (MPPT)** to interface between a solar panel and an electrical load. For the layman, all solar panels have the following power characteristics (shown in red on the graph below). We build hardware to allow us to traverse across the x-axis of the graph and the software constantly monitors the power output and tries to have us reach the peak of the curve. Which in the graph would be at a voltage of 32V, a current of ~4.5A to get us 140W of power.

<p align="center">
  <img src="./pictures/solar-panel-power.JPG" width=500 >
</p>

The problem we face is that this peak's location on the graph changes based on the sun's position in the sky, the ambient temperature, whether there is dust on the panels, clouds, etc... Thus we need to design an **optimization algorithm** that has us always at the peak, regardless of the conditions. A summary of the coding will be given below, for the full project report check out the docs. 

# Coding



#### Team taking a well deserved victory lap after the project was done
![image info](./pictures/BBQ.jpeg "BBQ")
