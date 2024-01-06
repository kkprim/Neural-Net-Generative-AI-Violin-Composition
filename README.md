# Neural Network Generative AI Violin Composition
### The AI Violinist: Crafting Notes Beyond Human
<img src="images/AI_Violinist.png" alt="AI_Violinist" width="600" height="500"/>

Welcome to this cool project where I'll be mixing the art of violin music with the latest in machine learning. It's all about blending traditional tunes with new-age tech.


## The Idea
Diving into the world of music generation but with a twist – I'm using some really advanced AI stuff to do it.


## The Goal
**Teaching machines to create violin music on their own**. This isn't just playing around with music and tech. It's paving the way for new forms of artistic expression where AI plays a leading role in the orchestra. This project is a showcase of AI's potential in creative fields, hinting at a future where art and technology blend seamlessly.


## The Data
- **What I've Got**:
  - 1,500 30-second violin preview tracks
  - 688 spectrograms
  - 150+ MIDI files

- **Where It's From**: Big thanks to Spotify API for these gems, ensuring variety and top-notch quality in this musical dataset.

- **Where to Find It**: [Link to Data Folders](https://drive.google.com/drive/folders/1Ub8uVjoJIKPxxRVdAay-ybWZ2NvIV5Xq?usp=sharing)



## The Challenges & Limitations
- **The Power Struggle**: The main challenge? Not enough computing juice. Training models like WaveNet and LSTM can be a bit of a resource hog.

- **Multiple Complex Models**: Juggling WaveNet, LSTM, and Jukebox isn't a walk in the park. It's a delicate balance of power and precision. But if that weren't enough, it's also necessary to blend complex music information retrieval tasks to build appropriate audio input for the models to use.

- **Harmonizing with Failure**: It's a tale of trial and error, where each misstep is a note in the learning melody. Check out the 'Failed_Models_Spectrograms.ipynb' for comprehensive documentation.



## The Tech Behind the Tunes
1. **Pitch Detection with CREPE:** The pitch-perfect detective. CREPE steps in to accurately detect pitch in audio, a key element for music analysis.

2. **Rhythm & Tempo Analysis:** The beat maestro. Here, I'll dissect the rhythm and tempo, ensuring the generated tunes have that toe-tapping quality.

3. **WaveNet**: This is the audio wizard, a neural network that's all about crafting realistic sound waves.

4. **LSTM (Long Short-Term Memory)**: It's the brain that understands patterns and sequences in music, making sure everything flows.

5. **Jukebox (Pre-Trained by OpenAI)**: Think of it as standing on the shoulders of giants - I'm using this pre-trained model to add some extra flair to our creations.



## The Wrap
This project shows that AI can not only understand music but also create it, and the results are pretty impressive, even with significant resource limits.
- **The Final Audio**: [Listen Here](https://www.veed.io/view/0c383325-4e70-4e4a-9fac-367afb475b81?panel=share)



## The Next Steps
- **Boosting The Tech**: More power! I'll need to beef up the computational capabilities to push these models further.

- **Refining MIDI Conversion Techniques**: It's all about making them better, smarter, and more creative.

- **A Symphony of Sounds**: Why stop at violins? There's a whole world of instruments and styles to explore.


## Contact Me!
#####  Kari Primiano #####
- Email: Kkprim@gmail.com
- Linkedin: linkedin.com/in/kari-primiano
- GitHub: github.com/kkprim


# Notebook Directory
``` bash
├── AI_Violinist_Intro.ipynb                <- Data capture/project overview
├── Model_1_WaveNet.ipynb                   <- Baseline/WaveNet Models
├── Model_2_LSTM.ipynb                      <- First LSTM Model
├── Model_3__Complex_LSTM.ipynb             <- Second LSTM Model
├── Visual_Analysis_Model_Comparison.ipynb  <- Model Evaluation
├── Pretrained_Model_Jukebox.ipynb          <- Generating Final Music
└── Failed_Models_Spectrograms.ipynb        <- Failed attempts
```

# Github Directory
``` bash
├── Images                                  <- Images created by DALL-E
├── .gitattributes                          <- Attributes for pathnames
├── .gitignore                              <- Contains list of files to be ignored from GitHub
├── requirements.txt                        <- Contains environment setup for each notebook
├── Presentation_Slides.pdf                 <- Slide Presentation of the project
├── README.md                               <- Contains README file to be reviewed
└── notebooks                               <- All notebooks (intro, modeling, analysis)

```
