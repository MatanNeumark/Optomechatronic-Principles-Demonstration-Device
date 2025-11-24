# Optomechatronic-Principles-Demonstration-Device
This repo showcases my Bachelor End Project (BEP) in the Control System Technology group of the Mechanical Engineering department at the Eindhoven University of Technology.
The project is about the design of a device which visually demonstrates the concepts of mechanical sensitivities of optical components, as illustrated in Figure 1.3. This topic is taught in the Mechanical Engineering Master's course Opto-Mechatronics. The purpose of this device is to supplement the theoretical explanations given during lectures by letting students experience the real-life effects of the sensitivities of optical elements to errors in their position.

<img width="813" height="1097" alt="image" src="https://github.com/user-attachments/assets/8f6a29cb-0cbd-4f8e-a173-3f45cd46caef" />
<br>
<br>

The design methodology follows the V-model shown in Figure 1.1. On the left side of the V, customer inquiry is framed as requirements and specifications, which are then used to come up with a concept with an initial, basic design. The basic system is then broken down into sub-systems with their own set of requirements and specifications. The design of the subsystems is detailed further and is continuously being validated and iterated at each step of the process to ensure it meets previous requirements and specifications. Once the concept, basic design and detailed design are complete, the product is manufactured as indicated at the bottom of the V. Then, on the right side of the V, the components, subsystems and the integrated system are tested and verified against the design requirements and specifications to ensure compliance. 

<img width="788" height="391" alt="image" src="https://github.com/user-attachments/assets/c7e50008-70d7-4853-8e56-11cba8b4c640" />

[2] J. Gausemeier and S. Moehringer, “New guideline VDI 2206 - A flexible procedure model
for the design of mechatronic systems,” in Proceedings of the International Conference
on Engineering Design, ICED, vol. DS 31, 2003.
<br>
<br>

The design, conceptually featured in Figure 2.1 below, features a carriage to which the three optical components are mounted. The carriage has two degrees of freedom: translation in X and rotation α about the X axis. These two degrees of freedom are sufficient to demonstrate the component’s sensitivities to lateral displacement and tilt. Mounting all three optical components on the same plane and close together allows the errors in the position of the outgoing beams to be projected onto a screen parallel to the X Y plane. This, in turn, lets the user see the resulting errors side by side and compare the sensitivities of the optical components. To achieve this, Two lasers are mounted to the right of the carriage such that their beams go through a small hole in the screen with a small angle α and β. By mounting the lasers at an angle, the reflected beams will land on the screen rather than back onto the lasers themselves, which is preferred both for user experience and to avoid damaging the lasers.

<img width="811" height="515" alt="image" src="https://github.com/user-attachments/assets/af636b34-7345-4240-9618-f170be93dee2" />
<br>
<br>

The detailed design of the carriage can be seen in Figure 2.4. Besides the carriage, the design includes two uprights and a base, which together are referred to as the stage. The main function of the stage assembly is to hold the carriage and facilitate its motion. The design also includes magnets in the uprights and carriage to provide a spring force for semi-independent control of translation and rotation. This spring force acts to bring the carriage back to a centred neutral position. Figure 2.4d shows an eccentric magnet mount which allows fine-tuning the zero-tilt angle of the carriage. 

<img width="1025" height="1162" alt="image" src="https://github.com/user-attachments/assets/754498b6-e2ac-4a3e-9953-64760b0be126" />
<br>
<br>

The laser mount is designed to be adjustable in radial-tangential directions by means of two nested eccenters, each with a 2mm eccentricity and a total radial travel of 4mm from the centre position Figure 2.9. These two eccenters provide freedom to translate the laser in X and Y. Rotations α and β are achieved through a  pherical bearing between the large eccenter and an additional ring Figure 2.9b. The spherical bearing gives the assembly 10° of rotation in α and 10° of rotation in β. This three-part assembly is then clamped with a mount that screws to the base of the device. The clamping force propagates through the three layers (spherical bearing ring, large eccenter, small eccenter) and onto the laser, locking the assembly in position.

<img width="1018" height="1165" alt="image" src="https://github.com/user-attachments/assets/d6408dfa-7d96-4a3a-a9a3-5d407d1d14f8" />
<br>
<br>

Figure 2.11 illustrates how the various components are to be assembled.

<img width="1024" height="1137" alt="image" src="https://github.com/user-attachments/assets/e53a7ff1-c179-4cd9-ace0-eb43eeba4005" />
<br>
<br>

The carriage was manufactured using a lathe and a CNC mill, whereas the flat parts (base, stage, screen, laser mount clamps) were cut by a water jet. The rest of the laser mount components (spherical bearing ring and the two eccenters) were SLS printed from PA-12.
Finally, the assembled device can be seen in Figure 3.1, Figure 3.2 and Figure 3.3.

<img width="819" height="1127" alt="image" src="https://github.com/user-attachments/assets/6b557ebc-2088-4c81-a535-5342430b6a56" />
<img width="819" height="549" alt="image" src="https://github.com/user-attachments/assets/de9d575d-72c1-4c74-be37-720e314f80d7" />
<br>
<br>

Figure 3.4 shows the laser beam in the static condition, whereas Figure 4.2 shows the location of the focal point for each optical component once the carriage is translated and rotated. As expected, the lens (left in Fig 4.2) causes the beam to deflect left and right. The concave mirror (centre in Fig 4.2) deflects the beam in response to both rotations and translations, and the mirror (right in Fig 4.2) only deflects the beam when it is rotated.

<img width="818" height="607" alt="image" src="https://github.com/user-attachments/assets/a10f518e-7f66-48dc-8143-cdf9e2e5c7d0" />
<img width="816" height="527" alt="image" src="https://github.com/user-attachments/assets/7c2c0ee6-4c7f-44e9-9df6-0117e646e0ca" />
