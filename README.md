# Single Sound Orchestra

## Overview
A composition created using several different DSP techniques like Karplus-Strong string synthesis, granular synthesis, magnitude spectrum manipulation, Paulstretch, comb filtering, flat magnitude reconstruction, and more. These techniques will all be applied in different combinations with different parameters on the same singular soundclip; a bar from Suzanne Vega's *Tom's Diner.* The end result will be an orchestral piece of music all made from one sound.

## Deliverables
1. (Expected): A song composed entirely of one sound file (Tom's Diner) arranged and edited and operated on in many different ways to create many different musical layers (like an orchestra!)
2. (Advanced): A tool that detects your midi keyboard controller (or computer keyboard input) and allows you to play with presets of your choice (i.e. Karplus-Strong + Paulstretched notes).
3. (Advanced): A tool that allows you to input a midi file and short sound clip (i.e. Tom's Diner), playing that midi file by mapping midi channels to DSP techniques on the sound clip

## Timeline
- Weeks 1-2: Objective 1 done by ~November 6th 
- Week 2: Check in: decide how to move forward with our next objectives, discuss what we learned, what we would like to keep/discard from the final project
- Weeks 3-4: Objective 2 done by ~November 20th
- Weeks 5-6: Polishing and preparing for presentations

## Tools
Python/Jupyter, potentially Max/MSP (specifically for Linnea's objective 2, P4)

## Techniques we will be investigating
- Karplus-Strong String Synthesis
- Magnitude Spectrum Manipulation and Crude Filtering
- Flat Magnitude Reconstruction
- Keeping only the K Magnitude Highest Peaks
- Paulstretch & Other Phase Reconstruction Techniques
- Allpass Filtering / Comb Filtering
- Reverb/Specialization Algorithms
- Degredation
- Granular Synthesis
- Concatenative Synthesis
- Automatic Orchestration
- Autotune

## Objectives

**Linnea Goodwin:**

- Objective 1: Technique Exploration
    - P1 (basic): play around with assigned techniques (Karplus-Strong string synthesis, filtering based on amplitude of magnitude peaks, reverb/spatialization algorithms, concatenative synthesis)
    - P2 (basic): make simple melody
    - P3 (expected): combining assigned techniques
    - P4 (advanced): combine techniques with another group member’s techniques
    - P5 (advanced): research techniques not discussed in class and implement them
    - P6 (basic): share our findings with each other
    - P7 (expected): If we have any techniques from Objective 1 that were made outside of python, convert them to python
- Objective 2: Composition
    - P1 (basic): Listen to everyone’s sounds and figure out what sounds would make for what kinds of instrumentation/orchestral layering (i.e. this sound/technique would make for a good bassline, this would make for a good percussive/rhythmic sound, etc.)
    - P2 (basic): Make some sheet music for a composition informed by the soundfont we created
    - P3 (expected): Make a MIDI file out of the score I composed and send to Isabel and Trinity for use in the MIDI mapping tool
    - P4 (expected): The generalized MIDI mapping tool can only do so much; arrange the score manually with these techniques for a more controlled composition, possibly using techniques not eligible for generalization (i.e. soundfile-specific concatenative synthesis)
    - P5 (advanced): Add support for a virtual piano that can be played with different “instrument” (DSP technique) presets live
        

**Isabel Ferris:**

- Objective 1: Technique Exploration
    - P1 (basic): play around with assigned techniques (Paulstretch/arbitrary phase reconstruction, allpass/comb filtering, degredation, granular synthesis)
    - P2 (basic): make simple melody
    - P3 (expected): combining assigned techniques
    - P4 (advanced): combine techniques with another group member’s techniques
    - P5 (advanced): research techniques not discussed in class and implement them
    - P6 (basic): share our findings with each other
    - P7 (expected): If we have any techniques from Objective 1 that were made outside of python, convert them to python
- Objective 2: Compile the Generalized Composition
    - P1 (basic): Create a MIDI mapper that maps the midi output of each channel to the corresponding DSP technique for that channel (whichever techniques you found in Objective 1 & we will split up Linnea’s)
    - P2 (expected): add support for swapping the single sound (i.e. swap Tom’s Diner for Amen drumroll or something)
    - P3 (advanced): Add support for using a different midi file from the composition of objective 2 (could maybe automatically map different channels to their most well-matching technique?)
    - P4 (advanced): Add a GUI for all of this to create a cool tool
        

**Trinity West:**

- Objective 1: Technique Exploration
    - P1 (basic): play around with assigned techniques (Magnitude spectrum manipulation/crude filtering, flat magnitude reconstruction, automatic orchestration, autotune techniques)
    - P2 (basic): make simple melody
    - P3 (expected): combining assigned techniques
    - P4 (advanced): combine techniques with another group member’s techniques
    - P5 (advanced): research techniques not discussed in class and implement them
    - P6 (basic): share our findings with each other
    - P7 (expected): If we have any techniques from Objective 1 that were made outside of python, convert them to python
- Objective 2: Compile the Generalized Composition
    - P1 (basic): Create a MIDI mapper that maps the midi output of each channel to the corresponding DSP technique for that channel (whichever techniques you found in Objective 1 & we will split up Linnea’s)
    - P2 (expected): add support for swapping the single sound (i.e. swap Tom’s Diner for Amen drumroll or something)
    - P3 (advanced): Add support for using a different midi file from the composition of objective 2 (could maybe automatically map different channels to their most well-matching technique?)
    - P4 (advanced): Add a GUI for all of this to create a cool tool
    

## Related Work

[1]  W. C. Pirkle, “Karplus-Strong Plucked String Model,” in Designing Software Synthesizer Plugins in C++, 2nd ed., United Kingdom: Routledge, 2021, pp. 207–224. doi: 10.4324/9781003052203-13.

[2]  C. Malloy, “Timbral effects the Paulstretch audio time-stretching algorithm,” The Journal of the Acoustical Society of America, vol. 151, no. 4, pp. A158–A158, Apr. 2022, doi: 10.1121/10.0010964.

[3]  P. Dutilleux, M. Holters, S. Disch, and U. Zölzer, “Filters and Delays,” in DAFX, 2nd ed., U. Z&ouml;lzer, Ed., Chichester, UK: Wiley, 2011, pp. 47–81. doi: 10.1002/9781119991298.ch2.

[4]  M. Helmuth, “Letting Pulsars Sing: Sonification With Granular Synthesis,” Journal of the Audio Engineering Society, vol. 72, no. 5, pp. 352–359, May 2024, doi: 10.17743/jaes.2022.0147.

[5]  C. Ó Nuanáin, P. Herrera, and S. Jordá, “Rhythmic Concatenative Synthesis for Electronic Music: Techniques, Implementation, and Evaluation,” Computer music journal, vol. 41, no. 2, pp. 21–37, June 2017, doi: 10.1162/COMJ_a_00412.

[6]  C. Ó. Nuanáin, P. Herrera, and S. Jordá, “k-Best Unit Selection Strategies for Musical Concatenative Synthesis,” in Music Technology with Swing, M. Aramaki, M. E. P. Davies, R. Kronland-Martinet, and S. Ystad, Eds., Switzerland: Springer International Publishing AG, 2018, pp. 76–97. doi: 10.1007/978-3-030-01692-0_6.

[7]  Y. Cui and M. Qin, “Research on Piano Harmony Automatic Orchestration System Based on Deep Learning,” in Application of Big Data, Blockchain, and Internet of Things for Education Informatization, vol. 583, Y. Zhang and N. Shah, Eds., Switzerland: Springer, 2024, pp. 59–69. doi: 10.1007/978-3-031-63139-9_7.

[8]  V. V. Kallinen, E. Moliner, L. Juvela, and V. Välimäki, “Music Source Separation via Stem Discovery,” Sept. 2026, doi: 10.48550/arxiv.2609.30912.

[9]  M. Blackwell and  publisher Bloomsbury, Plunderphonics, 1st edition. New York: Bloomsbury Academic, 2025. doi: 10.5040/9798765119518.

[10] F. CASTELLARES and A. J. LEMONTE, “On a von Mises-type circular distribution,” Anais da Academia Brasileira de Ciências, vol. 97, no. 3, p. e20240869, Jan. 2025, doi: 10.1590/0001-3765202520240869.

[11] M. Karjalainen, V. Välimäki, B. Hernoux, and J. Huopaniemi, “Explorations of wind instruments using digital signal processing and physical modeling techniques,” Journal of new music research, vol. 24, no. 4, pp. 301–317, Dec. 1995, doi: 10.1080/09298219508570688.

[12] “SPECTRAL ANALYSIS, VOCODERS, AND OTHER GOODIES,” in Introduction To Digital Signal Processing, WORLD SCIENTIFIC, 2009, pp. 333–414. doi: 10.1142/9789812790286_0009.

[13] V. Lazzarini, “Frequency-Domain Techniques,” in Computer Music Instruments, Switzerland: Springer International Publishing AG, 2017, pp. 223–271. doi: 10.1007/978-3-319-63504-0_7.

[14] M. Kahrs and K. Brandenburg, “TIME AND PITCH SCALE MODIFICATION OF AUDIO SIGNALS,” in Applications of Digital Signal Processing to Audio and Acoustics, vol. 437, United States: Springer, 1998.

[15] M. Kahrs and K. Brandenburg, “REVERBERATION ALGORITHMS,” in Applications of Digital Signal Processing to Audio and Acoustics, vol. 437, United States: Springer, 1998.
