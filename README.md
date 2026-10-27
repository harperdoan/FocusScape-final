FocusScape

An evolving soundscape for focused study.

FocusScape is an interactive soundscape website designed to support focused study through customisable ambient audio. Users can choose an atmosphere, adjust individual sound levels and generate subtle variations without completely changing their preferred soundscape.

Core Features

* Atmosphere Presets: Rainy Study, Café Focus and Quiet Focus provide different starting sound mixes.
* Individual Sound Controls: Four sliders allow users to adjust rain, café, wind and tone independently.
* New Variation: Generates small random changes based on the current mix.
* Variation Feedback: Displays which sound levels have increased, decreased or remained unchanged.
* Playback Controls: Allows users to start and stop the soundscape.

Extended Technique: Math.random()

The project uses JavaScript’s Math.random() to generate controlled sound variations. Instead of replacing the entire mix, the system applies small random adjustments within defined limits.

This approach balances unpredictability with user control, allowing the soundscape to evolve while maintaining a familiar atmosphere.

Design Rationale

The interface uses a minimal visual style, clear typography and a simple layout to reduce distractions during study.

Atmosphere presets support quick interaction, while individual sliders provide more detailed control. Variation feedback makes the results of randomisation visible and understandable.

Testing and Iteration

The final design builds on six earlier prototypes exploring manual controls, atmosphere presets, automatic variation and feedback.

Peer testing with seven participants highlighted different preferences for manual and automatic control. These findings informed the decision to combine presets, sliders and controlled variation in the final interface.

Technologies

* HTML5
* CSS3
* JavaScript
* Web Audio API

Limitations

The soundscape uses synthesised audio rather than recorded environmental sounds. The project focuses on a small selection of ambient sound layers and does not include saving custom mixes between sessions.

Project Documentation

Detailed design decisions, prototype development, testing findings, technical explanations and GitHub commit evidence are documented in the Assignment 3 section of the Interface Design and Development Work Index.