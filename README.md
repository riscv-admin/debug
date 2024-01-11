# Debug

This repository represents an administrative repository for the Debug Task Group.

It should contain documents to facilitate the group function, e.g. meeting minutes and supporting documents.

It should not contain code nor specifications.

## Debug Task Group Charter

The Debug Task Group will write a specification that covers external debug of a
RISC-V system using JTAG. The specification will also cover hardware breakpoints
useful both by external debug and for native debuggers.

External debug refers to debugging a RISC-V system without any help from the
software running on that system. Native debug refers to debugging a RISC-V
system primarily though the software running on that system. Hardware
breakpoints provide a mechanism to hand control to an external or native
debugger when certain conditions (such as executing an instruction at a given
address) occur.

When a design progresses from simulation to hardware implementation, a user's
control and understanding of the system's current state drops dramatically. To
help bring up and debug low level software and hardware, it is critical to have
good debugging support built into the hardware. When a robust OS is running on a
core, software can handle many debugging tasks. However, in many scenarios,
hardware support is essential.
