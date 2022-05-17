PART 1/3

I’m building an alternative to NURBS/Polygon modeling. This solution yields seamless transitions between curved features and requires less from the user (works as polygons too).

![3 moving points bending space - 12 seconds](https://user-images.githubusercontent.com/105538470/168451344-701566c8-8851-46c9-8a03-d0e94bb23d08.gif)

Bend Operation:<br/>
Don't bend surfaces (by positioning unruly arrays of points), bend space itself along with any _objects_ (_point/s, line/s, plane/s,_ and/or _solid/s_) in it, by moving only the minamum number of points nneeded to express the partiqular form. Running a straight _objects_ through a series of Bend Operations yields complex curvature. 

Space is bent by being fused onto _control objects_ which then move (this bends any _target objects_ within the space).

Formula: ***unbent ctrl objects + bent ctrl objects + unbent target objects = bent target objects***

4 lists of _objects_, 2 versions of 2 lists:

Lists:
- control
- target

Versions:
- unbent
- bent 

Input 3 lists, get 1 list output.

<br/>

(For each object listed in one version of a  list there is a corresponding object listed in the other version.

Each control object has a 1 - 100 efficacy variable.

<br/>

Add-ons to the Bend Operation:
- Levers: allows you to deform space in one location by relating it to _objects_ in another location.
- Spin: allows you to swirl space into non-converging layers.)

<br/>

My next step is finding the right platform to build in, OpenGL? (I have a rudimentary, 100 line, Visual Basic, Rhino plugin proof of concept.)


PART 2/3 - 3D MODELING WITH HANDLES like in the predomanant drawing software.
A POSIBLE CUSTIMISATION (CUSTIMIZATION WAS INITIAL AND STILL IS THE PRIPARY OBJECTIVE


PART 3/3 - OPERATING SYSTEM
my limited knowledge of what an operating system is From what I know about operating systems 




<!---
I’m looking to collaborate and help humanity particularly expand the educational and creative potential of computers.
I’m currently learning Blender and wonder if this could be built as an Add-on.
How to reach me ...
--->
