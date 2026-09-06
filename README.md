# 2026 BUMRC Electrical Team Onboarding Project - Boost Converter

For new members or returning members who wish to participate, there will be a boost-converter project for onboarding.

The project will include soldering, git, and KiCad schematic design. If you've never done either, that is okay.

A boost-converter is a switching regulator that **steps up a lower voltage at a higher current to a higher voltage at a lower current**, usually at a specific efficiency (near 80%).

> Here's a good [video](https://www.youtube.com/watch?v=9QM55r5fnUk) explaining how they work.

In this project, we will be using the `MC34063AP` IC from Texas Instruments, find its datasheet [here](datasheets/mc34063a.pdf).

We will also provide for you general components such as capacitors, resistors, diodes, inductors, perfboard, etc.

You can solder either in the Mars Rover Club Lab, in SiLab (need safety training), or at RASTIC (unless you know of another place, feel free to go elsewhere).

> If you don't know how to solder, we can organize a workshop for that.

## Boost Step-Up Converter Constraints:

| Full Name                          | Datasheet Name | Value  |
| ---------------------------------- | -------        | ------ |
| Voltage Input                      | VIN            | 5V     |
| Voltage Output                     | VOUT    | 12V    |
| Max Output Current                 | IOUT    | ???mA  |
| Minimum Switching Frequency        | fMin    | ???kHz |
| Peak-to-Peak Output Ripple Voltage | VRipple | ???mV  |

- Voltage Input, `VIN=5V`
- Voltage Output, `VOUT=12V`
- Max Output Current, `IOUT=???`
- Minimum Switching Frequency, `fMin=???`
- Desired Peak-to-Peak output ripple voltage, `VRipple=???`

> For testing, we will supply a 5V input source and use your boost output to drive a 12V fan.

## Learning Goals:

1. Using the club's Git template correctly
2. KiCad schematic development
3. How to refer to a datasheet and choose component values
4. Hands-on soldering experience with through-hole components
5. How to document your work and explain it in a design review

## Your Job:

### Planning and Calculations
1. Create a KiCad project based on the club KiCad template
2. Follow the datasheet to create a schematic for the boost converter in KiCad using the MRC template
3. Version control your project using Git through the club KiCad template. Git is very important to the electrical team
4. Choose your component values based on the above constraints, and defend them using the datasheet. Document this in a Markdown file called ```calculations.md```

### Documentation and Communication
4. Come up with a plan for laying out the components, it can be a simple sketch.
5. Write documentation explaining everything what you have done in a documentation.md markdown file. Combine all your calculations, screenshots of your schematic, and any information on your layout plan.
6. Present in an informal design review to Logan, and answer questions

### Hands-On Technical Experience
7. Create the boost converter on a perfboard and solder it by hand
8. Test your board, diagnose any issues, and come up with a concluision

## How to Start?

1. Head over to the [kicad-template](https://github.com/BUMRC-Electrical/kicad-template) and follow the instructions there for how to create your own copy of the template project.
2. 

## Useful Resources

1. [kicad-template](https://github.com/BUMRC-Electrical/kicad-template)
2. [guide on markdown syntax](https://www.markdownguide.org/basic-syntax/)
3. [git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)
