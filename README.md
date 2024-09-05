# Camper Interface PCA

## Other parts in system

Pi zero 2 W with display
- https://www.raspberrypi.com/documentation/computers/raspberry-pi.html#gpio-and-the-40-pin-header
- https://www.kiwi-electronics.com/nl/7-inch-all-in-one-rpi-zero-display-1024x600-11491?country=NL&utm_term=11491&gad_source=1&gclid=EAIaIQobChMIiey1n4eOiAMVSrODBx1cFD0VEAQYASABEgLn5PD_BwE

## Specs

- Monitoring of starter and household batery voltage
- Enable, disable and monitor household power (Set-reset circuit)
- Enable, disable and monitor pump (push-pull signal)
- Monitor clean and dirty water tank level (4 levels)
- Room temperature sensor
- Motion sensor
- Buttons to control household power and pump
- Serial interface to rp zeor 2
- voeding aansluiting voor de Zero-DISP-7A, RP zero 2 W (USB stekker 5 volt)

## Design

level shifter:
* TXB0106

pi zero:
- I/O voltage 3v3!
- supply voltage 5 volt

processor (PIC16F18056):
- 5 Volt supply!
- Serial
- 10 bit ADC, FVR of 4.096 V
- enough digital IO

power supply:
- external 5 volt;

Programmer:
- Microchip Snap