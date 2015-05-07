# Unity3D Live Input FFT Analysis
> The goal of this script is to handle live audio input analysis as most efficiently as possible within Unity. 

The inspiration and most of the base code hails from the Unity answers forum post [Real time Microphone (line input) FFT analysis](http://answers.unity3d.com/answers/394158/post.html).

## Notes on the current code

> The current code is not currently working as live input. It can process input at about 50 milliseconds with a bit of a stutter every time the buffer switches. However, in this case the audio only needs to be analyzed, not actually heard, but it does seem to choke in that moment.


> If you're looking for non-realtime audio analysis (e.g. running audio analysis on saved audio files that are playing back), this script works well with very little latency.