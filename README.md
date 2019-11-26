# MASG
microphone array speech generator in room acoustic.

## Version Information 

### Release 0.1

[1] The generator used for single sentence test, and verifies the accuracy of the data set generator.

### Release 0.2

[1] The generator is encapsulated as a function, which is executed in the form of call, and is convenient for the generation of large-scale microphone array speech data.
[2] Automatic output of microphone array signal generated by circulation.

### Release 0.3

[1] Using the encapsulated generator function, the speech data set is read automatically and circularly, to generate the microphone array speech in room acoustic.

[2] Support simultaneous generation of microphone array signals with four signal-to-noise ratios (-5dB, 0dB, 5dB, 10dB) and seven reverberation times (200ms, 300ms, 400ms, 500ms, 600ms, 700ms, 800ms).

## References

[1] R. Scheibler, E. Bezzam and I. Dokmanić, "Pyroomacoustics: A Python Package for Audio Room Simulation and Array Processing Algorithms," 2018 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Calgary, AB, 2018, pp. 351-355.

[2] ITU-T (1993). Objective measurement of active speech level. ITU-T Recommendation P. 56
