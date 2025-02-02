# openscan-modifications
 
This repo contains several modifications I have made to the basic OpenScan design of 
the Mini v2 and Midi v2 as well as my design for the Maxi, a 50cm diameter rotor.

Note: Some parts have been printed and test fit however I have not completed
a full scanner and tested it.

Originally I was going to also upload the Fusion360 design files but they are in 
such a mess right now that before publishing them I should create a clean version.

The STLs are divided into 3 categories, FDM, resin, and generic. 
Resin: Since resin prints have higher fidelity they are made using 0.2mm tolerances 
and because heatset inserts cannot be used holes have printed threads in them. I 
have acquired some M3 and M5 helicoil repair kits to see if they will give the 
threaded resin threads strength comparable to heatset inserts.

FDM: Desiged with 0.4mm tolerances and heatset inserts

Generic: Parts that don't need threads/heatset inserts and tolerances shouldn't matter

The basic idea is that there will be 2 bearing blocks assembled which use F695ZZ
bearings to guide the rotor. Each bearing block consists of 2 mid blocks, 2 axles,
and 2 bearing covers. The midblocks for the Mini and the Maxi have different angles
to account for the difference in rotor diameter.

Assembly:
1. Partially assemble the bearing blocks. Place 2 F695ZZ bearings on an axle, place 
the axle on the BOTTOM of the midblocks and screw the bearing cover in place to secure 
the axle. The midblocks do not have right/left versions.

2. Attach the bearing blocks to the stepper mounts. The platform mount should have the
bearing block attached to the front, while the cog mount will have the bearing block
attached to the rear. Attach the steppers, the cog stepper should not be fully tightened
to allow for adjustment later. !(/images/bearing block to mount assembly.png)

3. The Raspberry Pi attaches to the front crossbar platform using M2.5 screws. I 
have acquired a BigTreeTech SKR Pico to drive the steppers but I have not actually 
assembled everything yet.

4. Attach the side pieces to the stepper mounts and the crossbars. 
!(/images/electronics mounted.png)

5. Put the rotor cog on the rear stepper.

6. Place the rotor onto the bearings. Adjust the cog stepper as needed. Assemble the
tops axles, place in the midblocks and mount in place using the bearing covers.
!(/images/rotor placed.png)
!(/images/top bearings placed.png)