KARPLUS STRONG STRING

This patch provides a quick test implementation of the fundamental Karplus-Strong string synthesis algorithm.
It starts with a short burst of noise, simulating the initial excitation of a string being plucked or struck.
This noise is then fed into a feedback loop, creating a sustained string-like sound.
The loop is formed by routing the noise through a delay line, which represents the length and tension of the string, and then back to the beginning.

Key Points:

> Noise Generation: A brief, sharp noise burst serves as the initial string excitation.
> Feedback Loop: The core of the Karplus-Strong algorithm, where the sound continually circulates through a delay line, emulating the vibration of a string.
> Simplicity:  This is a rudimentary implementation, intended as a starting point for experimentation. This patch sticks to the basic principles of the Karplus-Strong method,
without delving into finer aspects like precise pitch control or advanced timbral modifications.
> Purpose: The aim is to demonstrate the fundamental mechanics of the Karplus-Strong technique, serving as a foundational test bed for further exploration and refinement.

