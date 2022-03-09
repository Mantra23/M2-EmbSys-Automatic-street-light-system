# AUTOMATIC STREET LIGHTING SYSTEM

Needs no manual operation for switching ON and OFF. When there is a need of light it automatically switches ON.
When darkness rises to a certain level then sensor circuit gets activated and switches ON and when there is other source of light i.e. daytime, the street light gets OFF. 
The sensitiveness of the street light can also be adjusted.

# Identifying features

It automatically switches ON lights when the sunlight goes below the visible region of our eyes. (e.g in evening after Sunset). 
It automatically switches OFF lights when Sunlight fall on it  ( i.e on LDR ) e.g in morning, 
by using a sensor called LDR (Light Dependent Resistor) which senses the light just like our eyes.
By using this Automatic system for street light controlling, we can reduce energy consumption because the manually operated street lights
are not switched off properly even the sunlight comes and also not switched on earlier before sunset. 
In sunny and rainy days, ON  and OFF time differ noticeably which is one of the major disadvantage of using timer circuits or
manual operation for switching the street light system.

# SWOT ANALYSIS

# Strength
Gives the users complete
control over the lighting
system, reduced electricity
consumption, and increased
sustainability

# Weakness
Traditional bulbs are cost-
effective and offer a hassle-
free installation process

# Opportunities
Rising government incentives for
energy-saving products. Rapid
urbanization and the rising need
for mobility could also largely fuel
the growth of this industry.
Scope of attracting corporate
clients is high.

# Threats
Cut throat competition
especially from traditional
lighting segemnts.
Increased cost and
complicated setup process
reduces the overall
demand for products.

# High level requirements

L.D.R (Light Depending Resistance)

I.C NE555 with Base

L.E.D (Light Emitting Diode) 5 pieces. (If using  white color then 4 Pcs)

Variable Resistance of 47 KΩ

P.C.B (Printed Circuit Board of 555 or Vero board.

# Low level Requirements

When light falls on the LDR then its resistance decreases which results in increase of the voltage at pin 2 of the IC 555.
IC 555 has got comparator inbuilt, which compares between the input voltage from pin2 and 1/3rd of the power supply voltage.
When input falls below 1/3rd then output is set high otherwise it is set low. Since in brightness, input voltage rises so we obtain
no positive voltage at output of pin 3 to drive relay or LED, besides in poor light condition we get output to energize.

