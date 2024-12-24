# OOPDS_collaboration
OOPDS assignment_dec_2024



Assignment "Warship simulator"

- read from txt file
- display battlefield
- randomized location of battleships
- looping ship movement (ship 1 > ship 2 > ship 3)
- data hiding for ships on opposing team
- ship actions (look, shoot, destroy)
- ship inheritance, polymorphism
- ship lives counter

Requirements anal

--Simulation reqs

-input format and struct
-battlefield dimensions and initialization
-ship types 
-ship actions
-turn-based mech 

--Design

--Class Design
-base class (ship)
  -abstract class vir meth
-derived class
  -moving
  -shooting
  -seeing
  -ram
-Specialized ship 
  -battleship
  -cruiser
  -destroyer
  -frigate
  -corvetter
  -amphibious
  -supership

--Data struct
  -linked list ofr ship actions
  -queue for destroyed shio
--Algo
  -ship action optimization
  -turn scheduing
  -battlefield update and printing




  IMPLEMENTATION

  -class def in .h
  -class implementation in .cpp
  -main prog in main.cpp
