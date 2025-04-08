Useful commands: 

**To Convert the airfoil.geo file to msh2 file**
```
gmsh airfoil.geo -3 -format msh2 -o airfoil.msh2
```

**To convert gmsh mesh to openfoam mesh format**
```
gmshToFoam airfoil.msh2
```

**To run the solver**
```
rhoCentralFoam
```

