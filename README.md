

```markdown
## Simple Target Simulation with G4beamline

This repository contains a simple target simulation setup using G4beamline.  
The official G4beamline User Manual can be found here:  
[G4beamline User Guide (PDF)] (https://www.muonsinc.com/Website1/Muons/G4beamlineUsersGuide.pdf)

## Installing G4beamline

G4beamline can be installed and run on various platforms. Installation guides and download links are available here:  
[G4beamline Download & Documentation] (https://www.muonsinc.com/Website1/tiki-index.php?page=G4beamline#Documentation)

More details are also available in the [G4beamline User Guide].

## Where to Run

- I personally run my simulations on the LPC cluster <username>@cmslpc-el8.fnal.gov

- For visualization (GUI), it’s recommended to download and run G4beamline locally on your own laptop.

## Setup

Once installed, you need to source the setup script.
source <your-G4Beamline-directory>/bin/g4bl-setup.sh
````

Make sure the path matches where G4beamline is installed on your system.

---

## Running the Simulation

To run the target simulation in batch mode:

```
g4bl GraphiteTarget.g4bl
```
To run with GUI visualization enabled:

```
g4bl GraphiteTarget.g4bl viewer=best
```
---

## Notes

* Modify the `.g4bl` files in this repo to configure different targets or beamline elements.
* Results and output files will be produced in the working directory where you run the commands.
---
