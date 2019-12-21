# isosphere
Python implementation for generation of regular unit icosahedrons (sphere made of triangles)
Based on C# code by Andres Kahler
http://blog.andreaskahler.com/2009/06/creating-icosphere-mesh-in-code.html
and based on Matlab code by Wil O.C. Ward, University of Nottingham, UK



Installation: 
You can install the small package

python setup.py install

or you can directly use the python script isosphere/__init__.py

Usage :

v,f =  isosphere(n) 
v : vertex
f : faces
n : isosphere order

drawPatch(v,f)

Draw the isosphere
