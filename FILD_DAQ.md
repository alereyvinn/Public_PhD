# Current FILD DAQs

## FILD1 (FHC)
  - Camera: Phantom
  - Camera computer: operated with fast camera network
  - Videos stored in ~/shares/experiments/aug-rawfiles/FIT
  - Fast channels: shotfile in ~/shares/experiments/aug-shotfiles/FHC
  - Fast channels computer: sxfhc
### Planned updates
We bought a new camera (XIMEA CB019MG-LX-X8G3), fibers and PCIe, only thing missing is the computer. W10 or W11 is preferred, for user-friendly interface.
Computer requirements:
  - Windows 10/11
  - Good internal memory and RAM
  - PCIe X8 Gen 3 slot
  - Operation in remote desktop
Data to be stored in ~/shares/experiments/aug-rawfiles/FIL/FILD1

## FILD2 (FHA)
  - Camera: PCO pixelfly
  - Camera computer: wxfildxp
  - Videos stored in ~/shares/experiments/aug-rawfiles/FIL/FILD2 (can't do it because computer is not connected tot he shares). Alternatively stored in my personal shares.
  - Fast channels: shotfile in ~/shares/experiments/aug-shotfiles/FHC (not working currently)
  - Fast channels computer: sxfa
### Planned updates
  - Update camera computer (wxfildxp)
  - Identify problem with the shotfiles and the computer, and presumably change system to standard AUG

## FILD3 (FHB)
Decomissioned

## FILD4 (FHD)
  - Camera: PCO pixelfly
  - Camera computer: wxfildxp
  - Videos stored in ~/shares/experiments/aug-rawfiles/FIL/FILD4 (can't do it because computer is not connected tot he shares). Alternatively stored in my personal shares.
  - Fast channels: APD camera
  - Fast channels computer: lxfild3
### Planned updates
  - Update camera computer (wxfildxp)
  - Update coil computer (lxfild2) and test DCS connection for automatic retraction
  - Ensure the APD connection and test it to work with the new operating system
    
## FILD5 (FHE)
  - Camera: PCO pixelfly
  - Camera computer: wxfildxp
  - Videos stored in ~/shares/experiments/aug-rawfiles/FIL/FILD5 (can't do it because computer is not connected tot he shares). Alternatively stored in my personal shares.
  - Fast channels: APD camera, decomissioned
### Planned updates
  - Update camera computer (wxfildxp)

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
  - Previously used for FILD5 APD operation. The camera does not exists anymore
  - OS: Oracle
  - IP: 130.183.56.226
  - Not being used currently, could serve as backup. But it is not accessible since we don't have the passwords.

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




