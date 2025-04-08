Useful commands: 

**1. Setting up the project**

**First Clone the folder**
```
git clone https://github.com/Priyesh-Kun/rhoCentralFOAM_shock_buffeting.git
```

**Change the directory**
```
cd rhoCentralFOAM_shock_buffeting.git
```

**Open openfoam**
```
openfoam2406
```

**2. Running the solver**

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

