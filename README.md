# SDF Combinators

A simple crate containing 3D and 2D signed distance fields shapes and combinators. Supports analytical gradiants as well.

## What are signed distance fields?

Signed distance fields are a way to represent shapes in a 3D (or 2D) space.
Instead of representing the shape as a set of triangles or polygons, the shape is represented as a function that takes a point in the space as input and returns the distance to the surface of the shape.
If the point is inside the shape the distance is negative, if the point is outside the shape the distance is positive and if the point is on the surface of the shape the distance is zero.

## What are the benefits of using signed distance fields?

- Resolution independent. This means that the same function can be used to represent the shape at any resolution.
- Easy to combine. This means that complex shapes can be created by combining simple shapes.
- Easy to manipulate. This means that shapes can be transformed in various ways without having to change the underlying function.
- Easy to render. This means that shapes can be rendered with high quality and high performance.
- Easy to raymarch. This means that shapes can be raymarched to create complex scenes.

## How do I make a game with signed distance fields?

You can use this crate to create the shapes, but you will need to implement the rendering and raymarching yourself.
The main goal of this crate is to provide the base set of combinators and shapes and then what you do with them is up to you.

## Further reading

- [Inigo Quilez](https://iquilezles.org/www/index.htm)
