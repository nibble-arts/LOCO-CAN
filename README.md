# LOCO-CAN

The software is managed in the [LOCO-CAN_Software](https://github.com/nibble-arts/LOCO-CAN_Software) repository.

The LOCO-CAN project is an electronic control system for the large passenger-carrying garden railway. The communication is based on the CAN bus, which is used in the automotive industry and in automation. The serial signal transmission is very robust and supports multiple masters and multiple slaves.

The modular system consists of different components with specialized tasks. For example, there are modules for operating, for controlling motor controls, light switch modules or sensors for current and voltage measurement or speed values. Actuators that are addressed by a servo module can even be used to control diesel engines or gearboxes.

Due to the flexibility of the CAN bus, additional modules can easily be connected without having to change the existing structure.

The system is not only intended for networking within a traction vehicle, but can also be routed through the train via a four-pole cable. This means that not only can control consoles be connected at any point in the train, but also, for example, lights in wagons can be operated.

# V 2.0
The current development of the system is based on version 2.x. It combines the microcontroller and the CAN bus connector with the specialized function on one board. Due to the use of SMD components, the modules are significantly smaller than in old 1.x versions.

With the universal module, a version with an expansion bus is also available.

## Connectors
The following connectors for the basic IOs are universal used by all modules if needed. The information includes the technical specifications for the connectors and the electrical assignment.

### CAN bus
The CAN-bus is found on all modules, even the WIFI. It connects all modules and provides both communication and supply.

**4-pin 2x2**
Plug: MATE-N-LOK 794617-4
Jack: MATE-N-LOK 3-794618-4

| pin | usage                      |
|:---:|:---------------------------|
| 1   | GND                        |
| 2   | CAN-L                      |
| 3   | CAN-H                      |
| 4   | +6-30 Volt / max. 5 Ampere |

### Loco interconnection
The Mate-N-LOK connectors are used for internal wiring only. 4-pin MINI-XLR connectors are used to couple vehicles together. The plugs are robust, but at the same time small enough to allow model-like housings around the plugs. The pin assignment matches the internal connectors. On the vehicle the female connectors are used.

| pin | usage                      |
|:---:|:---------------------------|
| 1   | GND                        |
| 2   | CAN-L                      |
| 3   | CAN-H                      |
| 4   | +6-30 Volt / max. 5 Ampere |

### Pulse
Used for speed or rpm measurement.

**2-pin horizontal**
Plug: MATE-N-LOK 2-1445055-2
Jack: MATE-N-LOK 1445022-2

| pin | usage |
|:---:|:------|
| 1   | Pulse |
| 2   | GND   |

### Power
Supply input for the LOCO-system.

**2-pin vertical**
Plug: MATE-N-LOK 794617-2
Jack: MATE-N-LOK 3-794618-2

| pin | usage                      |
|:---:|:---------------------------|
| 1   | +6-30 Volt / max. 5 Ampere |
| 2   | GND                        |

# Deprecated Hardware Versions

## V1.2
Version 1.2 is similar in concept to version 1.0, but has a 16 or 18 pin expansion bus with more connections for the adapters.

The version is software compatible, but uses a 5 Volt supply on the CAN bus connector and is therefore not directly electrically compatible with version 2.0. 

It will not be further developed.

## V1.0
The first version is based on a control unit with a microcontroller and a CAN bus connector and a 10-pin extension bus to which the respective adapters are plugged.

The version is software compatible, but uses a 5 Volt supply on the CAN bus connector and is therefore not directly electrically compatible with version 2.0. 

It will not be further developed.

