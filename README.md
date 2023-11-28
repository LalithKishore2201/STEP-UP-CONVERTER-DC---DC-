# STEP-UP-CONVERTER-DC---DC-
The boost converter is used to "step-up" an input voltage to some higher level, required by a load.

# OBJECTIVE

The main purpose of this project is to introduce a design and development method of a dc-dc boost converter with constant output voltage. From a fluctuating or a variable input voltage, boost converter is able to step up the input voltage to a higher constant dc output voltage using voltage feedback technique. By this technique, the output of the converter is measured and compared with a reference voltage. The differential of the compared value will be used to produce a pulse width modulation signal to control switch in the boost converter. Simulation results describe the performance of the proposed design.

# METHODOLOGY

A Boost converter steps up a DC voltage from the input to the output. The circuit operation depends on the conduction state of the MOSFET:

On-state: The current through the inductor increases linearly and the diode blocks.

Off-state: Since the current through the inductor cannot abruptly change the diode must carry
the current so it commutates and begins conducting. Energy is transferred from the inductor to
the capacitor resulting in a decreasing inductor current. During steady state the circuit is said
to operate:

• In discontinuous conduction mode if the inductor current reaches zero and

• In continuous conduction mode if the inductor current never reaches zero.

In this circuit average output voltage, is calculated by the formula,
Vo= Vs/(1-D)

# CIRCUIT

<img src="https://github.com/LalithKishore2201/STEP-UP-CONVERTER-DC---DC-/assets/152149631/7be6cdd6-8bec-4a2a-b1ac-da450a6042c9" width="600" height="350">

# OUTPUT

<img src="https://github.com/LalithKishore2201/STEP-UP-CONVERTER-DC---DC-/assets/152149631/1de10e79-8e21-4eb3-bce7-895a811a0b5e)" width="600" height="350">
