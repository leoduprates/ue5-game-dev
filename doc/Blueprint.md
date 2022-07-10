# Blueprint

### Benefits

- Quick to change.
- Beginner friendly.
- Easy to discover.
- Tailor-mad.
- Designer/artist friendly.

> 💡 **Glossary**
>
> - Event Graph: The canvas for our Blueprint.
> - Node: Premade functionality.
> - String: Programmer speak for text.
> - Event: A "when" node.
> - Pin: Sockets we can connect up.
> - Input Pin: When to run this node.
> - Output Pin: What to do after.
> - Connection: Wires between pins.

## Objects

Objects are collections of data and functionality.

- Actors.
  - Cube.
- Components.
  - StaticMeshComponent

> 💡 **Glossary**
>
> - Objects: Collections of data and functionality.
> - Actors: Object that can go in a level.
> - Component: Objects that can go on an actor.
> - Reference: Where to find an object.
> - Data Pin: The input or output data for a node.
> - Execution Pin: When to run this node.

## Force and Impulse

- Force = Mass \* Acceleration
- Impulse = Mass \* Velocity Change

## Spawning Actors

> 💡 **Glossary**
>
> - Spawing: Creating an object while playing.
> - Transform: Location, rotation and scale.

## Data Types

Data type is the "shape" of your data.

- Integers: 2, 23, -14.
- Floats: 1.5, -5.0, 0.232.
- Strings: "Hello", "World".
- Bools: True or False.
- Structs: Vectors, Rotator, Transforms.

> 💡 **Glossary**
>
> - Struct: An Object that is usually small.
> - Data Type: The "shape" of your data.

## What are Vectors?

- Mathematically.
  - Direction.
  - Size (Magnitude).
- Programmaticaly.
  - 3 Floats/
  - X, Y, Z.

### Vectors

- pos + move = newPos
  - x = pos.x + move.x
  - y = pos.y + move.y

## Branch Nodes

- Branches let us check if something is true or not and then do something based upon the result.
- They are often used with if statments to decide whether something happens or not.
- Certain nodes return bools.

> 💡 **Glossary**
>
> - Branch: Do something or don't, based on a bool.
> - Booleans: A YES or NO data type.
> - Comparison: Less than, Greater than, Equal, etc.

## Functions

- Functions execute blocks of blueprint that makes our game do things.
- Many node provided are functions.
- We can create our own too.
- They allow us to stay organised.
- Allow to reuse blocks of code.

### Good Naming

- Code is communication.
- Measure of code quality = WTHs / Minute.
- Functions should be verbs.
- Talk to somebody else!

## Pure Functions

### What is a side effect?

- When a function has an observable effect.
- Example:
  - Print String.
  - Add Impulse.
  - Set Ammo.

### What is a Pure Function?

- A function with no side effects.
- Only return values.
- Example:

  - Get Ammo.
  - Get Actor Forward Vector.
  - Multiply, Minus, Greater.

> 💡 **Glossary**
>
> - Side Effect: Observable effect of a function.
> - Pure Function: Functions with no side effects.

## Members Functions

A function on a class, always called on an particular instance.

> 💡 **Glossary**
>
> - Object Oriented Programming: Functions live with the data they manipulate.
> - Self: A node available in member functions, always points to the current instance.
