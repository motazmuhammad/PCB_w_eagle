This is to summarize and practice the book designing circuit boards with eagle

# Chapter1: Simple introduction, no need to read.
# Chapter 2:

## Definitions
  1. lead or terminal: metal extrusion that serves as the component's connection point to a circuit board.
  1. Through-hole: Leads are wires that enter holes in the board
  1. Surface Mount techology(SMT): Leads are metal balls on the bottom of the device
  1. Ball grid array (BGA): Leads are metal balls on the bottom of the device
  1. pad: The location on a board that comes in contact with a component's lead
  1. mil:0.001 inch.
  1. silk screen: a thin nonconductive layer used to print letters.
  1. solder mask: a think nonconductive layer used to protect the PCB.
  1. via: a conductive path between two layers.
  1. Through via: a via that connects the board's top and bottom sides. They don't come in contact with any internal layers.
  1. Buried via: a via that connect internal layers but does not touch any external layer.
  1. Stub via: runs all the way through the board. It connects one or both external layers to any of the internal layers.
  1. blind via: a via that connects an external layer to an interal but does not run through the board ( it can be only seen from one side)
  

# Chapter 3:

3.1,2 are step by step instruction to the software and inverting amplifier no need to write anything about them here

### 3.3.3 

Circuit elements

## Definitions
  Symbol: An element in a schematic editor
  Package: An element int he board editor
  Device: The combination of one or more symbols and a package.
  
Connection elements

## Definitions

Note the following names are used in the schematic editor
  Pin : A symbol's point of connection
  Net : A connection representing a single electrical path.
  Bus: A connection representing multiple electrical paths.
  
Note the following names are used in the board editor
  Pad: a package's point of connection
  Airwire: An unrouted connection between two pads.
  Trace: A routed connection between two pads.
  
  
