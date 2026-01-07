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


