# LOCO-CAN Hardware

The LOCO-CAN project is an electronic control system for the large passenger-carrying garden railway. The communication is based on the CAN bus, which is used in the automotive industry and in automation. The serial signal transmission is very robust and supports multiple masters and multiple slaves.

The modular system consists of different components with specialized tasks. For example, there are modules for operating, for controlling motor controls, light switch modules or sensors for current and voltage measurement or speed values. Actuators that are addressed by a servo module can even be used to control diesel engines or gearboxes.

Due to the flexibility of the CAN bus, additional modules can easily be connected without having to change the existing structure.

The system is not only intended for networking within a traction vehicle, but can also be routed through the train via a four-pole cable. This means that not only can control consoles be connected at any point in the train, but also, for example, lights in wagons can be operated.

# V 2.0
Version 2.x combines the microcontroller with the CAN bus connector with the specialized function on one board. Due to the use of SMD components, the modules are significantly smaller than in version 1.x.

But with the universal module a core module with extension bus is also offered here.

# V1.2
Version 1.2 is similar in concept to version 1.0, but has a 16 or 18 pin expansion bus with more connections for the adapters.

The version is software compatible, but uses a 5 Volt supply on the CAN bus connector and is therefore not directly electrically compatible with version 2.0. 

It will not be further developed.

# V1.0
The first version is based on a control unit with a microcontroller and a CAN bus connector and a 10-pin extension bus to which the respective adapters are plugged.

The version is software compatible, but uses a 5 Volt supply on the CAN bus connector and is therefore not directly electrically compatible with version 2.0. 

It will not be further developed.