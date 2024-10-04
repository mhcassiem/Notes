Sometimes flow rate issues may occur despite tuning retraction and temperature settings.
Blobs and zits of excess PLA on the exterior of the print model, especially at seams, could indicate that your flow rate is not correctly calibrated
You could change the flow rate value but before adjusting that it is a good idea to measure the eSteps of your extruder.

$$
\frac{100}{{E-Step}_{measured}}\cdot {E-Step}_{configured} = {E-Step}_{new}
$$

E-steps configured:
M502
Look for Recv: echo:Steps per unit:
the Esteps value will be the last number on the next line
E.g
Recv: echo: M92 X80.00 Y80.00 Z400.00 E93.00

Once you've calculated the new E-Step value you need to update your printer with this value.

M92 E{calculated value}
