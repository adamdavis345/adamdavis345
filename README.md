- 👋 Hi, I’m @adamdavis345
- 👀 I’m interested in building an alternative to NURBS/Polygon modeling. This solution yields seamless transitions between curved features and requires less of the user (works as polygons too).

Bend Operation:
Don't bend surfaces (by positioning unruly arrays of points), bend space itself and any _objects_ (_point/s, line/s, plane/s,_ and/or _solid/s_) in it. Beginning with straight _objects_, and repeatedly reruning the bent results through new Bend Operations. Space is bent by being fused on to _control objects_ which then move. This bends any _target objects_ in the space.

Formula:
_unbent ctrl objects + bent ctrl objects + unbent target objects = bent target objects_

- 2 states, unbent, bent. 
- 2 lists, controls, targets. (Lists are of equal length and each hold one of pairs of objects.) 

- 3 lists input = 1 list output. 

Each control object has a 1 - 100 efficacy variable.

Add-ons to the Bend Operation:
- (Levers: allows you to interact with one location as it relates to objects in another location.)
- (Spin: allows you to swirl space into non-converging layers.)

- 💞️ I’m looking to collaborate and help humanity particularly expand the educational and creative potential of computers.

<!---
- 🌱 I’m currently learning Blender and wonder if this could be built as an Add-on.
- 📫 How to reach me ...
--->

