# Video-sonification
A Max MSP-based video sonifier.

The incoming video file is down-sampled to a matrix of 6x6 pixels.
Then, after a red / green / blue decomposition, each color component controls a different parameter of an EQ which filters an incoming sound, called 'global sound' in the Main patch:

- red controls the center frequency of the EQ
- green controls the amount of reverb
- blue controls the amount of distortion and the Q factor of the EQ

In the MIXER section you can choose what audio signal to filter.