# Design-of-2-bit-even-and-odd-parity-generator-using-pseudo-NMOS-logic-under-skywater130-technology <br/>
---
# Parity generator <br/>
   Parity generator is a combination logic circuit. When data
is transmitted between source and destination there should
not be any loss in data. To detect data losses parity generator
technique is used in transmitter end. Parity is the
extra bit added to digital data on transmission. There are
two types of parity generator even parity generator and odd
parity generator.Even parity generator look for even number
of ones in binary data here parity bit is one when it detect odd number
of ones else it is zero. Odd parity look for odd number of
ones in binary data here parity bit is one when it detect even number of
ones else zero.<br/>
---
# Pseudo NMOS logic<br/>

Pseudo NMOS logic is a type
of static cmos logic where complementary output is driven
between Vdd and ground. This complementary output can
be normalized by cascading an inverter to it. In this logic
the number of transistors required is N plus 1 where N is the
number of inputs. A complete logical expression is implemented using NMOS transistors with one PMOS transistor
which is grounded . Vdd is given to the source terminal in
pmos. As this logic is more prone to static power decipation to avoide this size of pmos will be made smaller than nmos. <br/>

