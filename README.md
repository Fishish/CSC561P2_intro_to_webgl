# Program 2 - WebGL Intro

## Introduction
A program that reads an online input file for a series of triangles and uses WebGL to render those triangles in an HTML canvas element. Triangles are defined by a series of vertices, and then the index values of those vertices to define the shape the triangles make (triangle, square, etc.). Additional data stored in the triangles json objects contains information about the coloring of the triangles. For each triangle, ambient, specular, and diffuse color data is stored that is systematically read by the shader to calculate the color of the triangle.

If a different JSON file needs to be used, the global variable INPUT_TRIANGLES_URL should be changed. The new link should make sure it matches the format specified in the current link for this variable to ensure triangles are rendered correctly.

## Author
Connor Smith, Jiacheng Yang




