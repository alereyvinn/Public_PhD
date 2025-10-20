# Current FILD DAQs

## FILD1 (FHC)
  - Camera: Phantom
  - Camera computer: operated with fast camera network
  - Stored in ~/shares/experiments/aug-rawfiles/FIT
### Planned updates
We bought a new camera (XIMEA CB019MG-LX-X8G3), fibers and PCIe, only thing missing is the computer. W10 or W11 is preferred, for user-friendly interface.
A new computer for the control room is needed:
  - Windows 10/11
  - Good internal memory and RAM
  - PCIe X8 Gen 3 slot
Install the fibers from the MEM to the control room

## FILD2 (FHA)
  - Camera: PCO pixelfly
  - Camera computer: wxfildxp
  - Stored in ~/shares/experiments/aug-rawfiles/FIL/FILD2
  - Fast channels: PMT, currently does not work
### Planned updates
  - Update camera computer
  - Identify problem with PMT, and presumably change system to standard AUG

## FILD3 (FHB)
Decomissioned

## FILD4 (FHD)
  - Camera: PCO pixelfly
  - Camera computer: wxfildxp
  - Stored in ~/shares/experiments/aug-rawfiles/FIL/FILD4
  - Fast channels: APD camera
### Planned updates
  - Update camera computer

## FILD5 (FHE)
  - Camera: PCO pixelfly
  - Camera computer: wxfildxp
  - Stored in ~/shares/experiments/aug-rawfiles/FIL/FILD5
  - Fast channels: APD camera, decomissioned
### Planned updates
  - Update camera computer

---
# Computers
Here the full information of all computers used in the FILD diagnostics

### wxfildxp: FILD 2, 4, 5 cameras 

	- For PCO camera recordings of FILD2, FILD4 and FILD5
	- Windows XP
	- PCO cameras controlled with camware software (provided by them)
	- No connection to the shares or the network -> data extracted manually after shots. Currently being stored in my IPP shares, with copies in a USB and personal computer just in case
	- We tried to upgrade the PC to a W10 one, but it is not possible due to the cameras and the PCI. They are too old. Currently in contact with camera providers to buy new ones.
  
Changing the PC to a new one without taking into account the compatibility of the cameras would mean changing the whole 3 systems. If possible, we would like to be able to update the computer to met IPP standards, but without changing the cameras. There's a chance we can do it, if the camera version is compatible with newer computers.

### lxfild
  - Previously used for FILD5 APD operation. This camera does not exists anymore
  - OS: Oracle
  - IP: 130.183.56.226
  - Not being used currently, but could serve as backup. But it is not accessible since we don't have the passwords.

### lxfild2: FILD4 magnetic coil power supply
  - For control of FILD4 magnetic coil power supply
  - OS: Centos 7
  - IP: 130.183.105.44
  - We use a local user, user1, to connect enter the computer and operate
  - No access to the shares

### lxfild3: FILD4 APD
  - Used to FILD4 APD
  - OS: Centos 7
  - IP: 130.183.56.169
  - We use a local user, user1, to connect enter the computer and operate
  - No access to the shares
  - One of the harddrives was broken




