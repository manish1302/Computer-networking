# Physical Layer in OSI Model

The Physical Layer is the bottom-most layer of the OSI Model, representing the physical and electrical aspects of the network. It consists of network components like power plugs, connectors, and cable types. Its primary role is to send data bits between devices (e.g., computers) and manage the unstructured raw data streams over physical media.

## Functions Performed by the Physical Layer
- **Data Rate Maintenance**: Controls how many bits can be sent per second.
- **Bit Synchronization**: Ensures bits are synchronized during transmission.
- **Transmission Medium Decisions**: Determines the direction of data transfer.
- **Physical Topology Decisions**: Aids in selecting topologies (Mesh, Star, Bus, Ring).
- **Physical Medium and Interface Decisions**: Provides choices for connecting devices.
- **Configuration Types**: Supports Point-to-Point and Multi-Point configurations.
- **Device Interface**: Connects devices to the transmission medium.
- **Protocol Data Unit**: Uses bits as the unit of data.
- **Hardware Focus**: Includes hubs, Ethernet devices, and more.
- **Modulation**: Converts data into radio waves or optical signals.
- **Switching Mechanism**: Forwards data packets between ports.

## Physical Topologies
1. **Mesh Topology**: Each device has a dedicated point-to-point connection with every other device. Offers high security but is complex to install.
2. **Star Topology**: Devices connect to a central hub. Easier to install but lacks fault tolerance.
3. **Bus Topology**: Multiple devices share a single backbone cable. Cost-effective but challenging for re-installation.
4. **Ring Topology**: Devices are connected in a circular manner, and data can be sent only with a token.

## Line Configuration
- **Point-to-Point Configuration**: A dedicated link between two devices.
- **Multi-Point Configuration**: A shared link connecting multiple devices.

## Modes of Transmission Medium
- **Simplex Mode**: One device transmits; the other only receives (e.g., keyboards, broadcasting).
- **Half Duplex Mode**: Both devices can send/receive, but not simultaneously (e.g., walkie-talkies).
- **Full Duplex Mode**: Both devices can send and receive simultaneously (e.g., telephones).

## Physical Layer Protocols
Examples of protocols that operate at the Physical Layer:
- Ethernet (1000BASE-T, 1000BASE-SX, 100BaseT)
- Synchronous Digital Hierarchy/Optical Synchronization
- Variations of 802.11 (Wi-Fi)
- Bluetooth
- U.S. Serial Bus (USB)
