# MarchingSquares

## Description

The Marching-Squares Algorithm is a simple way to graphically render non-standard contours, by considering a grid-based system.
This application uses Perlin Noise to generate an underlying field of values which smoothly transition over the space.
By considering the value at each corner of a given cell, we can approximate (linearly interpolate) where each the transition line passes through a given square.

### Visual Aid
![explanation](https://user-images.githubusercontent.com/64329402/166257222-b6927c4a-7453-415e-a902-cef0ca33b79b.jpg)

For more information about the implementation, see [this YouTube video](https://www.youtube.com/watch?v=0ZONMNUKTfU) published by TheCodingTrain.

## Screenshots
![preview](https://user-images.githubusercontent.com/64329402/164213205-fe7eab28-f281-42e8-bf40-1a4a2502443c.jpg)
![preview2](https://user-images.githubusercontent.com/64329402/166257533-255e93f6-0c78-4310-8e83-8450084c349e.jpg)

## Libraries
- [hsnoise-0.0.2](https://github.com/colinhect/hsnoise) by Colin Hill
- [Gloss](https://github.com/benl23x5/gloss) by Ben Lippmeier
