# Obj2Ifc

A  converter from one or more Wavefront OBJ sources to an IFC model.

## Usage

`Obj2Ifc.exe -objfiles inputmodel.obj -ifcFile output.ifc`

Multiple obj files can be provided as inputs to a single IFC.

Run `Obj2Ifc.exe --help` for more options

### Units

Values implemented for the Units option are:

- [x] Meters
- [x] MilliMeters

```
Obj2Ifc.exe -objfiles inputmodel.obj -ifcFile output.ifc -u MilliMeters
```

## Done

- [x] Correct coordinate systems
- [x] Units
	- [x] Meters and millimeters
- [x] Ifc Geometries 
	- [x] TriangulatedFaceSet
	- [x] IfcFacetedBrep
- [x] Properties
	- [x] attaching properties to the object via command parameters
	- [x] arbitrary property set name
	- [x] Types
	  - [x] Real, R, r
	  - [x] Label, L, l

## Contacts

Feel free to use github issues for getting in touch.