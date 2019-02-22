# PisaBot
A self-balancing robot with a single stepper motor.
This is a novelty (according to my research) for a self-balancing robot which uses a single stepper motor with dual shaft. I named it the PisaBot based on the famous Leaning Tower of Pisa. The inspiration for the robot name is from the constant forwards and backwards rocking motion to keep its balance so the robot is leaning most of the time in either directions along one plane.
            
I designed the chassis in Autodesk Inventor Pro (except for the Pisa Tower cover which i edited from utechlab's design: https://www.thingiverse.com/thing:1129396) and 3D printed the parts. This is the final version after more than a dozen prototypes in order to shrink the overall design and reduce the robot’s height (minus the cover) to keep the centre of gravity as low as possible.

The Arduino code and smartphone app are from JJrobots’ B-ROBOT EVO 2 and unmodified. But the PisaBot can currently only move forwards and backwards since there is no turning mechanism. The “PRO” mode also works to give more power.

List of parts used:

1 x Double Shaft Stepper Motor 42mm Nema 17 1.7A 17HS4401B

2 x LiitoKala 18650 3400mAh rechargeable battery 3.7V Li-ion

1 x 18650 battery case with 2 slots

2 x Hex coupling, 30 mm length, 5 mm hole diameter.

2 x RC wheels 1/10 Off Road Hex 12mm. Tires Outside Diameter: 85mm and Rim Width: 34mm.
2 x Rubber Bumpers Pads
1 x JJrobots Electronic Brain Shield
1 x MPU-6050 (gyroscope and accelerometer)
2 x A4988 stepper motor drivers
1 x Arduino Leonardo
M3 stainless steel button head screws

Download the chassis parts to 3D print:
https://www.thingiverse.com/thing:3045793

The washer (for each bumper on the front and back side of the robot) goes into the rubber bumper hole so that you can use an M3 screw to hold it tightly to the motor mounting plate extension that juts out in the front and back. The selected wheels allow the motor and chassis to stay above ground as high as possible without the outer diameter rubbing against the electronics plate. You could also use some other wheels but keep the outer diameter under 90 mm.