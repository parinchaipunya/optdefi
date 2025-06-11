# `optdefi`: A package that helps defining an optimization problem

## Installation

Tentatively, one could download the `optdefi.sty` file and place it in the same folder as your `.tex` file.

## Usage

To use the package, just put `\usepackage{optdefi}` in the preamble of your `.tex` file.

## Environments and Commands

Environments `optim` and `optim*` are used in order to define an optimization problem with and without numbers, respectively.
The following commands are used within the `optim` and `optim*` environments.
- `\setObj` is the first command to use. It defines the *sense*, variables and objective function.
- `\addEqCons` to add an equality constraint.
- `\addIneqCons` to add a less-then inequality constraint.
- `\addInclCons` to add an inclusion constraint.
- `\addLbCons` to add a lower-bound constraint, or a greater-than inequality constraint.

## Example

Please refer to the `sample.tex` file included in the repository.
