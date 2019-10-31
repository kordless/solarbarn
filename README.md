# Solar Barn
Solar Barn is a simple IN PROGRESS guide for building and maintaining your own off-grid solar electrical system. The system you can build from this guide will give you enough power from the sun to charge phones and laptops, run power tools and most non-refrigeration/heating applicances for short periods of time during a widespread outage. It can make the difference from being able to stay in your home during an outage and having to leave your home to find power.

In a recent PG&E outage out here in California, I was able to run my butane heater for heat (with the system running the fan an ignitor) and my on-demand gas hot water heater for hot water. I also used the system to charge a portable Jackery power bank invertor, which was then used to charge and power our electronic devices.

Disclaimer: I'm not responsible for anything you do with any of this, so if you short out anything it's not my fault. This information is provided for educational purposes only and I'm saying that to protect myself from the trolls out there. FYT!

## How Much Power and Cost?
Your power requirements will vary depending on use, so try to plan on the side of buying more panels and batteries than you think you need. If all you are planning on doing is charging a laptop, a phone and a flashlight, you could try buying a single large panel and a single 100ah battery. More below in parts on battery size and suggestions for a more robust "Mini" setup.

Minimum cost for a reliable basic system will run you ~$875 + the work to set it up. Minimum recommended config below.

Q: Why not buy a cheap generator?

A: Fuel costs and transport. Also, generators are notorious for blowing out electronics.

Power requirements beyond simple charging vary widely, but a good rule of thumb is that you can run a hair dryer for about 30 minutes on a single deep cycle battery before charging it or shortening its life (which would be ~1/2 of 100ah at 12 volts). More on battery "draw down" below.

## Parts Overview
The following parts are suggestions only! See the section on scaling for more information on quantities. See the install section for more information on which parts you may need. Links in the different configuration sizes below include my personal Amazon affiliate codes, so if you buy from the links, I get credit on Amazon. 25% of my take will be used to purchase equipment for those without power and housing. If you like this guide, consider donating parts to those in need - I'd rather you support someone who can't afford a solution than giving me the money!

### Solar Panels
Solar panels provide energy from the sun. They cannot be shorted out and most last for ~25 years! Older panels are typically less efficent than newer panels and prices appear to continue to drop slowly on the technology as long as there isn't high market demand for the units. It is suggested you start out with twice as many panels as 100ah batteries, given the changing angle of the sun and clouds play a factor in a panel's ability to charge a given battery bank. Panels come in various watt output and voltages.

### Batteries 
Batteries store the energy from the charger. Remember, batteries can be shorted out and panels can't! Lead acid/gel batteries can last up to 5 years. Lithium/Iron batteries are about 5 times as expensive as AGM (deep cycle) batteris, but can be recharged more times, output more total power (before life is shortened) and in general last longer.

Batteries have voltage (95% of batteries are 12 volts) and amperage ratings. Amps indicate the flow of electricity, sort of like the flow of water through a faucet. For simplification, this guide only covers the use of 100ah batteries, which each store 100 hours of 12 volt power at a 1 ampere (amp) draw. For 100ah lead/gel batteries, you want to only use UP TO 1/2 of the total storage of the battery (which means you should double the number of batteries you need for a given output).

In the case of (2) 100ah 12 volt batteries arranged in series (giving 24 volts) you could use up to 50ah at 24volts of power before risking damaging the batteries. This equals about 1200 watts (24 volts times 50ah) of power (for an hour).

### Charger
Chargers take energy from the panels and push them into the batteries. Most chargers nowadays are about the same as another, except for their displays. Always buy a charger with a display so you can see what is going on with your system.

### Inverter
Inverters take the direct current energy from the batteries and converts it to usable alernating power, such as that you get from a wall outlet (120AC). Inverters can output a square wave form (think pixelated power) or sinusodial (smooth wave) power. Some of the more expensive inverters also can contain chargers and auto-switching system. This guide does not cover integrated charging or switching systems.

I do not suggest buying a non-sinusodial inverter. It can ruin sensitive equipment.

This guide only covers 24 volt inverter systems and setup. If you elect to purchase a single battery, you will need to buy a 12 volt inverter. You should spend at least $500 on a 1000-1500 watt inverter. Don't be fooled by cheap knockoffs...THEY WILL CATCH ON FIRE!

### Breakers, Fuses, Wires and Solinoids, Oh My.
Wires carry power from the panels to the charger and from the charger to the batteries. These wires can be small guage. Larger guage wires are needed to run power from the batteries to the inverter.

Fuses are required for ensuring safe operation of the system. It is suggsted you use a bar fuse for the negative side of the battery bank and a breaker for the positive side.

Solinoids optionally provide a means of automatically engaging power to the inverter from the batteries using a low power activator pair (wires). This guide does not discuss activating the solinoid automatically, but the video guide shows how I acomplish this in my own setup. A simple switch supplying power from the charger output is a low cost and effective solution for keeping the inverter from drawing power from the battery bank until you need it.

## Parts Bundles
The following bundles are recommended if you don't want to calculate your own setup. I use a scale factor of ~2X panels per battery and always suggest buying batteries in pairs to give an even 24 volts per pair.

### The Mini
The mini costs ~$875 for ~3 hours of power at 300 watts, bursting to 600 watts peak (momentary draw). Recharges 1-2 times in a single sunny day. Order the quantity indicated. Order an extra charger for some failure protection. NOTE: Solar panels in the Mini config output ~36 volts and 0.5-4 amps when wired in series.

(3) Panels: [Renogy Solar Panel 100 Watt 12 Volt (Prime)](https://www.amazon.com/dp/B07GF5JY35/ref=psdc_2236628011_t1_B00AQQAAQW)

(2) Batteries: [Weize 12V 100AH Deep Cycle AGM](https://www.amazon.com/Weize-100AH-Cycle-Battery-Solar/dp/B07SW353M8/) 

(1) Charger: [GHB 20A 12V 24V Solar Charge Controller Auto Switch LCD](https://www.amazon.com/GHB-Controller-Intelligent-Temperature-Compensation/dp/B01LZZMDSQ/)

(1) Inverter: [Go Power! GP-SW300-24 300-Watt Pure Sine Wave Inverter](https://www.amazon.com/Go-Power-GP-SW300-24-300-Watt-Inverter/dp/B00153CXVA/)

(3) 2 AWG 2 Guage Cables: [2 AWG 2 Gauge Single 2 feet w/5/16 Lugs](https://www.amazon.com/Single-Copper-PowerFlex-Battery-Inverter/dp/B072MVYZV2/) 
NOTE: Order (3) total 2' cables. (2) black, (1) red.

(1) MC4 T-Branch Cable: [MC4 T-Branch Cable connectors for Solar Panels](https://www.amazon.com/T-Branch-connectors-photovoltaic-Systems-Connector/dp/B07S32Z985)
NOTE: Optional. Buy if planning on upgrading system.

(1) Charge Connector: [WOLFWILL MC4 Connector Solar Panel Adapter Cable to DC 5.5mm x 2.1mm](https://www.amazon.com/dp/B07GFJM8LW/)

# Scaling

