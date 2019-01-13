## Robots-Custom_Command

The following code converts material percentage values to the value of a group of digital output signals custom commands for Robots plugin on ABB robotic arm.

## Inputs:

| Name          |Description     | Type  |
| ------------- | -------------- | ----- |
| Proportion    | Material proportion A / B (0 to 1) | number |
| Resolution    | 2 to power of this number is the Resolution / Number of bits for binary number | integer |
| Command Name | SetGO command name (should match on teach pendant) | string |

## Outputs:

| Name          |Description     | Type  |
| ------------- | -------------- | ----- |
| Command  | Custom command for ABB robots on Robots Plugin | command(C) |

## Description:

- Remaps 'Proportion' to result of 2 to power of 'Resolution'.
- Finds the nearest integer number to previous values.
- constructs custom command.

### Prerequisites

> [Rhino 5](https://www.rhino3d.com/download/rhino/5/latest) + [Grasshopper](https://www.grasshopper3d.com/page/download-1) / [Rhino 6](https://www.rhino3d.com/download)  
> [Robots plugin for Grasshopper](https://github.com/visose/Robots)

## Authors

## Acknowledgments
