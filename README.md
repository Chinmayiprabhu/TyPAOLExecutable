# TyPAOLExecutable 

- Introduction
  This repository contains the proof of concept implementation of the work presented in  " A Type System for Data {rivacy COmpliance in Active Object Languages" 
*  Prerequisites
  To run and test the code, the rewriting tool [a link] (https://maude.cs.illinois.edu/w/index.php/Maude_download_and_installation)] is needed. It's downloadable free of charge from 
  the University of Illinois. See the documentation there for installation instructions and further information.
+ TypeChecker in Maude
  This file mainly implements the type system mentioned in the paper. It generates the constraints for the TyPAOL programs. The generated constraints are then used at the runtime, using our Interpreter written in Maude.
- Interpreter in Maude
- This file implements the operational semantics of TyPAOL, which at the time of activation uses the constraints generated from the type checker for the TyPAOL programs
* Test Programs in Maude, use the following instructions
  -  sudo ./maude-Yices2.darwin64
  -  load ./Typechecker.maude
  -  load ./test1.maude
  -  load ./Interpreter.maude
- Ongoing Work
    -This work is ongoing, we are still trying to conduct robust analysis out of the typechecker to prove some properties, make larger test cases and report on the same. 

