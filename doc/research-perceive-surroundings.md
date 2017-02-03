
# Basic Research: Perception of the drones surroundings

One of the first work package was to find out how to enable the drone to perceive its surroundings.

![header](../media/header_resistor.jpg)


## Basic considerations

As our drone shall flight without external control, it will require the ability to perceive its surroundings. 
Even if there are many different ways, we all agreed that the easiest way to achieve that would be to use 
some basic distance sensors on a micro-controller. We already have some experiences with arduino, raspberry 
and such in our team, and this working package was perfectly suitable for parallel work, so we started with
it as one of our first steps.


## Finding a suitable sensor type

We found that there are basically two different groups of sensors which could fit our needs:

- Acoustic sensors (ultrasonic)
- Optical sensors ()like infrared or lasers)

They differ significantly in price and capabilities. For example, most infrared sensors are useable for 
small or middle distances (30cm - 150cm). We also found some laser sensors, but their price was always more
than 100€ per unit.
The solution for us was the very cheap HC-SR04 ultrasonic sensor. With a price of less than 3 € per unit and
a distance range of 2cm up to ~ 300cm, it is perfectly suitable for our drone to find out what's upfront.

## The HC-SR04 ultrasonic sensor

The HC-SR04 is a very cheap ultrasonic sensor with a nice distance. Here is how it looks like:

![header](../media/hc_sr_04.jpg)




