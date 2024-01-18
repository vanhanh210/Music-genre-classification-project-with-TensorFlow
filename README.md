# Music genre classification project with TensorFlow
 
## About Dataset
### Context

Music. Experts have been trying for a long time to understand sound and what differenciates one song from another. How to visualize sound. What makes a tone different from another.

This data hopefully can give the opportunity to do just that.

### Content
- genres original - A collection of 10 genres with 100 audio files each, all having a length of 30 seconds (the famous GTZAN dataset, the MNIST of sounds)
- images original - A visual representation for each audio file. One way to classify data is through neural networks. Because NNs (like CNN, what we will be using today) usually take in some sort of image representation, the audio files were converted to Mel Spectrograms to make this possible.
- 2 CSV files - Containing features of the audio files. One file has for each song (30 seconds long) a mean and variance computed over multiple features that can be extracted from an audio file. The other file has the same structure, but the songs were split before into 3 seconds audio files (this way increasing 10 times the amount of data we fuel into our classification models). With data, more is always better.

### Acknowledgements
The GTZAN dataset is the most-used public dataset for evaluation in machine listening research for music genre recognition (MGR). The files were collected in 2000-2001 from a variety of sources including personal CDs, radio, microphone recordings, in order to represent a variety of recording conditions (http://marsyas.info/downloads/datasets.html).
This was a team project for uni, so the effort in creating the images and features wasn't only my own. So, I want to thank James Wiltshire, Lauren O'Hare and Minyu Lei for being the best teammates ever and for having so much fun and learning so much during the 3 days we worked on this.
### Inspiration
1. what is an audio file?
2. how does an audio file look?
3. can you extract features?
4. can you perform EDA?
5. can you create a super powerful NN on the images?
