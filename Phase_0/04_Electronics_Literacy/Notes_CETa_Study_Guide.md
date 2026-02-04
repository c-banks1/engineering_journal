# Associate CET Study Guide - Notes
Texts: *The Associate CET Study Guide* - ETA International Staff - 2016

## The CET Program Description

### In the Beginning: 
Before the CET program there were few official certification programs that would be recognized at the state or federal level, though a few exceptions to that rule were the RN and CNA levels. 

In 1965 the CET program was created by the National Electronic Associations (NEA) 

Initially the adherents of the CET program were well trained prior-military who were already trained through the Labor Dept but wanted a way to show that they knew. The CET program was the obvious answer. 
The initial program was aimed for Radio and TV techs as those were the main people in the civilian electronic field but this would change. 

With that change, it became clear that more fields were opening up and that a computer technician need not understand the operation of a radio tower. The CETa exam was narrowed to accomodate that and centered around schematic assessment, soldering and electrical safety procedures. 

To confirm that technicians had specialty training, Specialty Certifications were created that stated the associate knew more than just the basics in areas from (Avionics to Radar) in the form of their own individual certifications. 

### Associate Status: 
An CET student is not an Associate until they have taken and passed the CET exam. The CET exam was created in order to facilitate a confirmation to employers that the Associate knew their stuff irrespective of formal education. 

The CET exam is not the only exam that was created around this time but it is unique in its scope which others have different purposes, CSS and CST exams being a good example of. 

### Promotion from CETa 

There are a variety of next steps from the CETa exam. You can pursue specialty certifications as was mentioned earlier, but you also can pursue the Journeyman, Senior or Master CET levels. 

## Safety Precautions for Electronics

### Shock Hazard 

Given an electronics technician's close proximity to electricity and electrical equipment, the most obvious hazard is shock. Specifically the consequences of current passing through one's body and causing damage. 

In most scenarios, this is actually not a big risk, most applications use between 5-12V which are required to power transistors in the applications, however some of applications which currently still exist operate between 50-500V in some legacy equipment. 
- Shock hazard at low voltages is not a lot of risk however when you work with larger voltages or wall outlets (120V @ 60Hz) the risk is increased
- Shock hazard is also circumstantial; zapped by a wall outlet but have rubber soled shoes on and not standing in water? Not a big deal, hurts and you may want to take it easy for the rest of the day and see a doctor soon but much less hazard than shocked in a bathtub full of water.

Reaction to shock is also a hazard that is more immediately concerning. This goes along with the circumstantial issue, if you are operating equipment like a saw or blade, and get shocked it can be very dangerous because you may jerk back and harm yourself, same thing if you are standing on a ladder and are shocked and fall. 
- Hazard by position
- Hazard by operating equipment
- Hazard by close contact chemicals
- Hazard to others around you

This does not mean that any amount of shock really isn't a big deal, it just means that most isn't. Some equipment operates at relatively high voltages which can be very danagerous:
- Industrial equipment
- Legacy equipment (tubes, etc.) can operate between 26K - 30K volts
- Modern Plasma screen (300-400V)
- LCD (1500V)

If you are working with relatively high voltages, consider using a High Voltage Probe to determine what the voltages are at. 

##### At What Point is this a Deadly Risk? 

Assume that electricity is dangerous all the time, even a little bit of current can do very bad things to do and stop your heart. 

On average it is assumed 100mA is lethal but you can feel 10mA, so the real hazard zone is somewhere between there with about 100mA being deadly always.  
> - For reference, the Electric Chair operates at 2000V
> - Power lines deliver 230V to a home's power box, they are insulated but still should not be touched if possible.

Wet skin has a resistance of about 100K Ohms, this rises quickly when the skin is dry and if subjected to a bad shock the skin will blacken and become a further insulator for all the comfort that brings. 

End of story is, be respectful to the electricity and treat it like any other dangerous tool (chainsaw, jackhammer, explosives, etc.) 

 ### Specific Hazards 

 #### Hot Chassis

 One of the more typical kind of hazards occurs when house wiring is incorrect. 
 
 <img width="1200" height="800" alt="image" src="https://github.com/user-attachments/assets/e57a1503-f075-48e7-a4a3-17eeb0b503db" />

Above is indicated the correct way to wire a home outlet with the black wire connected to the hot (small) side and the white wire connected to the neutral along with the ground connected to the well, ground. 

Why this is important is because when the hot and neutral sides are reversed, this can allow current to pass through hash filters in applications and destroy equipment. Most of the time these issues go un-noticed or the issue is not a serious one, however if the product is in a dangerous location like a damp basement, it can allow the current to flow to people or objects more easily. 

Check the power cord every time that you are servicing equipment. Specifically look for current leakage, anything above 500 microA is too much and may indicate a problem. 

#### Capacitor Hazards 

Capacitor hazards are surprising simply because of what they are. They operate effectively as battery sources but where they differ from batteries is that the batteries have internal resistance which, if shorted prevent as much current as could go. Capacitors have virtually zero internal resistance and little to no leakage. 

What this means is that a capacitor (large) could hold charge for years and shock unsuspecting people. 

**Solution:** Take the time to discharge every large capacitor with ohm meters before servicing the unit. 

#### Arcing

It isn't thought about much but electricity has the ability to jump across space. Air is a conductor too, a poor one, but it is a conductor and if the voltage is high enough, voltage can jump across a range to make a person part of its circuit. 

This issue grows in concern for both operator and equipment the more you increase the voltage. For reference 3kV can jump about 1/4 of an inch. 

#### Other Hazards 

Environmental factors are a consistent consideration. Damp spaces or puddles like what might be in a basement or after a large storm are a threat. 

Modern devices are considerably safer as they operate on much lower voltages (5-12V) and their dangerous components (power supply, filter capacitors, transformers, etc.) are secured behind a box that will need to be opened in order to access those components. 

> Consider a "One-Hand Rule" when working on electrical devices, using one hand with another in a pocket while in contact with the device is safer because it is more difficult to close a circuit.
> Never work alone. Work in parallel with another technician preferably or at least someone who can disconnect the power.

Chemical exposure is another consideration. CETs work with often toxic compounds, ensure you are in a well ventilated area when working or use a respirator. Also ensure that you have eye protection. 

> Fire hazards are a constant concern. When using a torch, or a soldering iron, or if you are in an environment where a short could produce a fire, these are considerations. Electrical fires require their own kind of extinguisher, but in the immediate, electrical burn injuries can produce anywhere from first to third degree burns in the wrong situations. 
> 
> - First Degree: Run burn under cold water and dry. Do not cover the burn
> - Second Degree: Do not run under cold water and try not to break the blisters. Cover with a bandage and consider a doctor/urgent care center if needed.
> - Third Degree: These are matters for doctors. The skin is totally dead and will not repair itself. Cover with a clean bandage and get the technician/person to a hospital.
> 
> Burned skin is more resistant than unburned skin and therefore a person who is burned may have a slightly better time as far as current is concerned. 

On a less serious note, radiation is a consideration. Many individuals won't work in these environments but x-ray tubes are still active in vintage equipment. The effects of non-ionizing radiation are somewhat more nebulous and it is unclear their risk. Time will tell. 

#### NEC

The NEC (National Electrical Code) is the bible of US electricians and CETs. They are a series of rules devised to prevent injuries and fires which operate with electrical systems. 

Their importance is two fold:
1. Safety for workers, operators, customers is important
2. OSHA looks very disfavorably on those who violate these rules and get people injured, often with great monetary consequences.

NEMA (National Electrical Manufacturers Association) also has a series of rules about electrical device installation that may be pertinent to CET operations. 

A big help with these rules and keeping people safe has to do with **Signage**. 

There are many kinds of signs and their meanings but the general rule is, use signage to keep people who should not be a certain area out for their own safety and if there are people who will be in these environments, think about possible failure vectors that could crop up. A person falling (Manhole Sign), a tool falling on someone's head (Hard Hat Required), someone being shocked (High Voltage sign), etc. Imagine stupid things occurring and prevent that by using signs if possible. 

#### ESD (Electro Static Discharge) and Other Operator Failure Modes

Electro Static Discharge is a basically just static, but rather than being a nuisance that happens in dry environments like to most people, they can be extremely hazardous for components where a single static shock can mean the death of a large PCB. 

Ways to prevent ESD is to ground the operator using a ESD wrist wrap that will carry away your charge through a 1 MOhm resistor and neutralize that risk. Another way is wearing booties that are connected to your skin, or working while standing or sitting on a composition pad that does the same thing. 

Another failure mode is bad **soldering/unsoldering**. 

Soldering is a delicate procedure and can destroy parts if one is not careful, particularly when the components that are being soldered are very delicate. 

Repeated soldering exposes the component to high heat which has a nasty effect on components. When operating on devices, do more thinking and testing than replacing or you will likely end up having to get an entirely new device. 

> Note: Keep in mind that legacy components have their own risks involved and handling them in the right way is required to avoid damage. Tubes particularly have a series of unique failure modes and can be risky particularly with implosion risk.

#### Tools and Apparel 

There are rarely places that have too much equipment. Use the right tool for the job, and make sure they are in good condition. A bad tool can be worse than no tool at all. 

Using multimeters with leads that can grip is also a very helpful thing as you can focus on the reading rather than the leads moving. 

Similarly equipment is only rated for certain voltages and currents and some are more sensitive than others. Keep in mind what your tools can and can't do. 

As far as clothing and apparel, use clothing that is with an eye toward efficiency. Do not have loose anything; not hair, not clothes, not jewelry. Likewise, if you are working, wear work boots, steel toed if required. 

#### First Aid 

We touched on this earlier but just to reinforce the message. 

##### CPR: 
There is some uncertainty if this is appropriate but if a person has fallen into respiratory or cardiac arrest, then this is the time to do CPR. If you don't know it however, on the scene is not the time to learn. 

##### General First Aid 

Many trucks will have small first aid kits, nothing elaborate but they will have some equipment that can be used for minor injuries. An ounce of prevention is worth a pound of cure however, be careful on site, manage the risks in your environment, make sure your equipment (on or off the truck) is orderly and secure, if you get a call, pull to the side and answer it or call back later. Be cautious. 

These are basic rules, the specifics of each site will be different, but the objective for CETs is to learn the basics and then to analyze and learn the risks of a particular site. 

## Math for Electronics 
