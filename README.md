# `optdefi`: A package that helps defining an optimization problem

## Usage

Environments `optim` and `optim*` are used in order to define an optimization problem with and without numbers, respectively.
The following commands are used within the `optim` and `optim*` environments.
- `\setObj` is the first command to use. It defines the *sense*, variables and objective function.
- `\addEqCons` to add an equality constraint.
- `\addIneqCons` to add a less-then inequality constraint.
- `\addInclCons` to add an inclusion constraint.
- `\addLbCons` to add a lower-bound constraint, or a greater-than inequality constraint.
