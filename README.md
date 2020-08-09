# SLIC-LTE rotary-phone
LTE conversion for rotary phone, using LILYGO-T-CALL-SIM7000, and KS0835F SLIC 
Main functions:

- Control ringing using the SLIC (KS0835F built to filter mobile interference out)
- Monitor the switch hook signal from SLIC to control states and count pulses for dialing
- Dial out using the LILYGO board
- Monitor the LTE for incoming calls
- Answer calls when receiver is picked up
- Short number list (0 to 9) for favorite numbers (hardcoded)

Known issues:


Connections to rotary phone:

- Hook up the ring/tip wires to the ring/tip pins of the SLIC module. It provides a local phone line connection,as well as the audio and MIC as the KS0835F is designed for use with mobile phones.





Bill of materials:

- Vintage rotary phone in working condition
- LILYGO T CALL SIM7000
- QCKS0835F SLIC module
- 
- Li-Ion charger board with separate power out
- Li-Ion battery 3.7V, 18650
- Slide switch DPDT
- Phone charger, USB C
- Connection wires, with and without Dupont connectors (AWG24 for power connections)
- Capacitor, electrolyte, 470uF 16V
- Capacitor, ceramic, 100nF 50V
- Perf board for mounting the components


Required tools:

- Soldering equipment (for electronics)
- Computer with Arduino Software (IDE)
