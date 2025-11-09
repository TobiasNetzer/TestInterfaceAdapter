# Work in progress

# *compact* Test Interface Adapter

The Test Interface Adapter is designed for adapting low-pin-count test fixtures to standard equipment and for enabling low-volume in-circuit testing.  
Instead of expensive integrated solutions, this approach uses standard external instruments, like a digital multimeter with some type of remote control interface like USB, RS232 or Ethernet to take measurements from the DUT (Device Under Test).  
Various external stimulus sources like power supplies or function generators can be switched to the DUT through the adapter.  
For programming applications, a passthrough port for a standard 10-pin header is available.
To simplify communication with the DUT, there are galvanically isolated UART, RS485 and I²C communication interfaces.

### Features:

- **32-channel relay matrix**
- **16 normally open relay contacts**
- **4 external stimulus inputs**, via 2A capable relays
- **Programmer passthrough port** for in-circuit programming applications
- **External probe input**, routable to matrix channel 1
- **Isolated half-duplex RS485 interface**
- **Isolated UART interface**
- **Isolated I²C interface**

### Docs:

- [Schematic](docs/Schematic.pdf)
- [Assembly Drawing](docs/Assembly_Drawing.pdf)

![image](docs/PCB_Render_Top.png)
![image](docs/PCB_Render_Bot.png)
![image](docs/Render.png)