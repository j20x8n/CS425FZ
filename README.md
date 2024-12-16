java cCS425FZ (Audio  Speech Processing) 
Assignment 1 
(value 20%) 
Released date: Tuesday 26
th
 November 2024 
Due date: Sunday 15
th
 December 2024 at 23:59 
This is an open-book, graded assignment. Please cite all references as comments in your 
submissions. You cannot directly reuse a solution from online sources or AI. You must not engage 
with another student, in person or electronically (via phone, social media, etc.), to secure 
assistance with this Assignment. If you do so (even for only one of the questions), you will receive 
an automatic failure (0%), and it will also be reported to the Executive Vice-Dean of MIEC and/or 
Maynooth University Plagiarism board. We will perform similarity checks on submitted 
assignments to check for collaborative efforts. The lecturer reserves the right to interview you 
about your submission in special cases. It should be mentioned that the Turnitin tool provided in 
Moodle can detect AI-generated context. 
The first assignment is to use the programs in Java, processing, Python, or Octave/MATLAB to 
prepare a narrative on digital waveforms and spectral analysis using the FFT and the Spectrogram 
to demonstrate your knowledge of how they work. Make sure that each plot can clearly illustrate 
the shape of the waveform, i.e. if you have to zoom in to get this, do so. A thick coloured block is 
not acceptable. The results from your plotting should be placed into a PowerPoint presentation, 
and along with the plot, a sound file should be inserted into the page (it should be imported as 
mp3 to save space). The documents should also show on the following slide to each plot the 
programming scripts to generate the wave and its graph. The graphs should have titles, labelled 
axes and a caption in the document (e.g. Figure 1, Figure 2). 
Waveforms 
1. Generate and plot one example of the waveform of a sinusoid at a frequency, amplitude, 
and phase of your choice. Show the waveform from time t=0. Select the frequency of the 
sinewave from the set of musical notes 
 https://homes.luddy.indiana.edu/donbyrd/Teach/MusicalPitchesTable.htm 
Make sure to give the frequency of the wave in the title of the plot. 
2. Generate and plot an example of waveforms composed of sinusoids at harmonically 
rela代 写CS425FZ、Java
代做程序编程语言ted frequencies to create either a sawtooth wave, a square wave or a triangle wave. 
3. Read in a wav file of an “effect”/natural sound and plot only 20 seconds of it. 
4. Read in a wav file of a Speech utterance (it could be from the web or recorded by yourself) 
and plot it (approx. 2-5 seconds), put the text of the utterance in the title of the plot. Page 2 of 2 
 
Fourier transform 
5. Plot the magnitude of the Fourier transform (FFT) of a signal composed of more than one 
sinusoid of different frequencies and amplitudes using a rectangular window. Use an FFT 
length of N=256 and then N=2048. 
6. Plot the magnitude of the Fourier transform (FFT) of the same signal composed of more 
than one sinusoid of different frequencies and amplitudes using a Hanning window. Use an 
FFT length of N=256 and then N=2048. 
7. Record at least 1 second of you saying any vowel sound using Audacity or an equivalent 
software. Use the editor to retain only the steady portion of the vowel waveform. Plot the 
magnitude of the Fourier transform of this, picking a suitable value for N (e.g. 256, 512, 
1024 2048) so that it is easy to identify at least two formant peaks form the spectrum. 
Spectrogram 
8. Plot the spectrogram of the speech waveform you used earlier for a short window N=256 
and a long window N=1024. Identify the voiced and unvoiced speech in the plot. 
9. Plot the spectrogram of a sound effect that has distinctive frequency components, e.g. a 
bird sound, a chainsaw, a car starting, clock strike. Pick an appropriate window length for 
the frequency components to be clearly displayed. Make sure to mention the window 
length in the title of the plot 
10. Plot the spectrogram of a short drum loop of your choice with N=256 and N=2048 to show 
that the shorter window means a better time resolution, and thus, the points in time of the 
drum hits are easier to discern. Point this out in the figure in its caption. 
Sources of sound files 
 
Use Audacity to shorten the sound file to the length required. 
 
Note: the Java and processing code only handles 16-but mono wav files properly. If your file is not 
in that format just use Audacity to split a stereo track to mono and export it as a 16-bit wav. 

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
