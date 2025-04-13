2025-04-13 12:37

Status:

Tags:

# Composites Summary

## What is a composite?
Definition(General): Combination of two or more individual Materials
Definition(Current Context): Multiphase material that is artificially made
Design goal: Combine materials with the objective of getting more desirable combination of properties.

#### Material Selection Charts:
Chart Showing the Youngs Modulus vs Density
	![[Pasted image 20250413124416.png]]
	Temperature vs Strength
	![[Pasted image 20250413124516.png]]

## Terminology
Composite: multiphase material that is artificially made
	Matrix:
		The continuous phase
		Purpose are to:
		- Transfer stress to dispersed phase
		- Protect dispersed phase from environment
		- barrier to crack propagation
		Types: Metal Matrix Composite - MMC, Ceramic Matrix Composite - CMC, Polymer Matrix Composite - PMC
	Dispersed Phase:
	Purpose:
		MMC: Increase Yield Strength, TS, and creep resist.
		CMC : Increase $K_{Ic}$
		PMC : Increase E, Yield Strength, TS, creep resist.
		Types : particle, fiber, structural, nano

![[Pasted image 20250413125237.png]]
![[Pasted image 20250413130012.png]]
![[Pasted image 20250413130518.png]]

## Fibre Types
- Whiskers - Thin single crystals - very large length to diameter ratios
	- High Crystal Perfection and virtually flaw free - extremely string, strongest known
	- Very expensive and difficult to disperse
	- Some whisker materials : Graphite, silicon nitride, silicon carbide.
- Fibres
	- Polycrystalline or amorphous
	- Typically, polymers or ceramics
	- e.g. alumina, aramid, E-glass, boron, UHMWPE
- Wires
	- Relatively large diameter, often metal wires
	- E.g. Steel, molybdenum, tungsten.
## Fibre Alignment
Aligned and continuous fibres are aligned in one direction in the longitudinal direction

discontinuous fibres are shorter or in random directions.   

## Longitudinal Loading
To measure Youngs modulus, stress needs to be parallel to the fibres(  in the Longitudinal direction)

Longitudinal loading in a composite refers to applying a load along the direction of the fibres or reinforcement. In this case, the strain in the fibre, matrix, and composite is equal (iso-strain condition), and the load is distributed based on their respective stiffness and volume fractions. This is often analysed using the "rule of mixtures" to predict properties like strength and modulus.

### Rule of Mixtures Formula

The rule of mixtures provides an upper-bound estimate for a composite property (e.g., elastic modulus) when the load is applied parallel to the fibers: $$E_c = fE_f + (1-f)E_m$$ Where:

- (E_c): Composite property (e.g., elastic modulus)
    
- (E_f): Property of the fiber
    
- (E_m): Property of the matrix
    
- (f): Volume fraction of the fiber

##  Transversal Loading
Transverse  Youngs modulus is calculated when the stress is in the transverse direction( perpendicular  to the fibres)


Transversal loading in composites refers to the application of a load perpendicular to the direction of the fibers in a composite material. This type of loading is significant because it tests the composite's ability to withstand forces that are not aligned with the primary reinforcement direction.

Key Points in Transversal Loading:

1. **Stress Distribution**: When a transversal load is applied, the stress is distributed across the matrix and fibers. However, the matrix often bears the majority of the load since the fibers are oriented longitudinally.
    
2. **Failure Mechanisms**: Transversal loading can lead to matrix cracking, fiber-matrix debonding, or shear failure. These mechanisms depend on the material properties and the interface strength between the fibers and the matrix.
    
3. **Micromechanical Analysis**: Engineers use micromechanical models to predict the behavior of composites under transversal loading. These models account for stress concentrations and the interaction between fibers and the matrix.
    
4. **Applications**: Understanding transversal loading is crucial for designing composite materials used in aerospace, automotive, and structural applications where multidirectional forces are common.
    

### Inverse Rule of Mixtures Formula

The inverse rule of mixtures provides a lower-bound estimate for a composite property when the load is applied perpendicular to the fibers: $$E_c = \left(\frac{f}{E_f} + \frac{1-f}{E_m}\right)^{-1}$$ Where the terms represent the same variables as above.


## Polymer-Matrix Composites
##### Glass fibre-reinforces Polymer (GFRP)
composites : fibreglass
	Most common
	Some Reasons  for  using glass as  fibres:
	-  Easy to draw fibres from molten state
	- Strong
	- readily available/economic
	- Chemically inert ( for instance, non-corrosive)
	Disadvantages
	- Not very stiff - cannot be used in structural applications
	- Limited to low service temperatures ( < 200 deg C)
##### Carbon Fibre-reinforced polymer (CFRP)
high-performance composite
Some Reasons for using carbon as fibres:
- Highest specific modulus and specific strength of all reinforcing fibre materials
- retain high modulus and strength at elevated temperatures ( >2000 deg C results in oxidation, however)
- Chemically inert near room temperature
- can engineer specific mechanical and physical properties
## Ceramic Matrix Composite
ceramics are heat and oxidation resistant but brittle
fracture toughness of < 5MPa$\sqrt{m}$
Toughness can be improved with embedded fibres, whiskers and particulates -> 6-20 MPa$\sqrt m$
Mechanism: crack propagation halted by dispersed phase
Transformation toughening 

## Metal Matrix Composite
Combination of metal matrix and various reinforcements:
	Continuous fibres:
		Carbon, SiC, boron, aluminium oxide and refractory metals.
	Discontinuous fibres:
		SiC whiskers, Chopped fibres of aluminium oxide and carbon.
	Particulates: 
		SiC and aluminium oxide, cermets.
Expensive, restricted use
High service temperatures: can be reactive (requires protective surface coating on reinforcement)
Processing:(1) consolidation of reinforcement into matrix, (2) shaping( discontinuous fibres - standard metal shaping methods)
Applications: 
	Automobile/aircraft pats ( aluminium alloy - aluminium oxide/carbon) - lightweights and wear resistant
	Turbine engines ( superalloy matrix - refractory metal fibre reinforcement)
		high temperature and oxidation resistance

## Composite Production methods
![[Pasted image 20250413164857.png]]
![[Pasted image 20250413165038.png]]
![[Pasted image 20250413165123.png]]


## Classification : Structural
Laminates - 
-- stacked and bonded fibre-reinforced sheets
- Stacking sequence: e.g., 0/90 deg
- Benefit : balanced in plane stiffness.
Sandwich panels
-- honeycomb core between two facing sheets
- benefits: low density, large bending stiffness
- ![[Pasted image 20250413165425.png]]


## Composite benefits summary

CMCs: increased toughness
PMCs : increased $E/\rho$
MMCs: Increased creep resistance

# References
