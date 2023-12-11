# L-Systems and Spectral Filtering in Ableton Live

### Written by Brian Tice
### University of California, San Diego

This python notebook is used to evaluate the use of L-Systems as a source for spectral filter parameters in a musical collaboration with Tim Gmeiner. We explore the idea that Lindenmayer systems, or L-Systems are used to generate particular sequences of numbers that are then sent to a Max patch written for Ableton Live. Attention to a human centered approach is paramount because we didn't want the algorithmic approach to impede on the human qualities of the music. In other words generative algorithms are merely a tool to add color to the music and are not used to generate music.

Within the context of our musical collaboration, we created an audio patch that utilizes L-systems to define the parameters of a filter applied to the drums. In particular, frequency band levels of a 256 band spectral filter are defined by the results of an L-System. The patch takes integer text input generated from an L-system, and then maps it to spectral band amplitudes of the filter. A visual representation is also generated in the patch. There is also the ability to live code new L-systems, or any sequence for that matter, and send them via an OSC connection to the patch. Lastly, there exist preset L-System results that can be applied via a knob and three preset buttons. Enjoy and please send any feedback to: btice@ucsd.edu

<img width="472" alt="Screen Shot 2023-12-11 at 10 41 27 AM" src="https://github.com/b-tice/l-systems_spectral_filter/assets/120678973/7749a038-c4aa-4490-95c1-15d1e5ed528a">


Credit must be given to CNMAT for their OSC max objects as well as to Zack Settel and Cort Lippe for their paper, "Real-Time Musical Applications using FFT-based Resynthesis", that inspired the Spectral Filter Max for Live patch that we modified for our work. 

<img width="992" alt="Screen Shot 2023-12-11 at 11 56 40 AM" src="https://github.com/b-tice/l-systems_spectral_filter/assets/120678973/e65a0369-2ccd-4745-82d6-7e74a766938f">



