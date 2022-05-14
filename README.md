Hi, I’m @adamdavis345

I’m building an alternative to NURBS/Polygon modeling. This solution yields seamless transitions between curved features and requires less from the user (works as polygons too).

Bend Operation:<br/>
Don't bend surfaces (by positioning unruly arrays of points), bend space itself along with any _objects_ (_point/s, line/s, plane/s,_ and/or _solid/s_) in it. Rerunning a straight _objects_ through a hierarchy of multiple Bend operations yields complex curvature. Space is bent by being fused onto _control objects_ which then move (this bends any _target objects_ in the space).

Formula:<br/>
_unbent ctrl objects + bent ctrl objects + unbent target objects = bent target objects_

- 2 states, unbent, bent.
- 2 lists, controls, targets. (For each object listed in one list there is a correlating object listed in the other list.

3 lists input = 1 list output.

<br/>

(Each control object has a 1 - 100 efficacy variable.

Add-ons to the Bend Operation:
- Levers: allows you to deform space in one location by relating it to _objects_ in another location.)
- Spin: allows you to swirl space into non-converging layers.)

<br/>

My next step is finding the right platform to build in, OpenGL? (I have a rudimentary, visual basic, proof of concept codded as a plugin for Rhino.)

<!---
I’m looking to collaborate and help humanity particularly expand the educational and creative potential of computers.
I’m currently learning Blender and wonder if this could be built as an Add-on.
How to reach me ...
--->
