# Test Plan

## Requirement test cases
* Ambient light is low: Amplifier gives HIGH signal and Lamp turns ON
* Ambient light is high: Amplifier gives LOW signal and Lamp turns OFF
* Supply voltage > Operational voltage: Crisp circuits
* Supply voltage < Operational voltage: No output

## Scenario test cases
* Sunny day: Lamp turns OFF
* Cloudy day: Lamp turns ON
* Rainy day: Lamp turns ON
* Fog: Lamp turns ON
* Night and lots of vehicle head lamps: Lamp turns OFF

## Boundary test cases
* Dawn: Lamp turns OFF
* Dusk: Lamp turns ON
