# MechInterpRace
My project identifies specific components in the 700M parameter language model gpt2-large that are causally linked to the generation of select facts involving race. For example, I observed that a layer 18 MLP in gpt2-large strongly determines the generation of facts associated with "Indian." It then makes a basic attempt at linking these identified components to the decision-making process the language model takes when faced with a prompt involving race.
!![MechInterpRaceGraphs1 (3)](https://github.com/Ooberaj/MechInterpRace/assets/28967776/46620580-4c70-4257-b3e0-0a1818863d61)
![MechInterpRaceGraphs2](https://github.com/Ooberaj/MechInterpRace/assets/28967776/994f2b83-4b99-4b1a-bae0-05f250b6065a)
Clean prompt: "The Indian live in the city of" | Generated: Mumbai
![newplot (11)](https://github.com/Ooberaj/MechInterpRace/assets/28967776/5ee32d8d-49f3-4bc9-8cab-030bd2e85372)
Clean prompt: "The Indian have an annual festival called" | Generated: "Diwali"
![newplot (14)](https://github.com/Ooberaj/MechInterpRace/assets/28967776/1c3043cc-14ac-4c98-857a-cd7b517c7e08)
Clean prompt: "The Chinese have an annual festival called" | Generated: "the Spring Festival"
![newplot (21)](https://github.com/Ooberaj/MechInterpRace/assets/28967776/bfd71bf9-3857-4e3e-853b-3db5b991bf64)
