# jluo0401_9103_tut12_GroupA

## Individual Approach to Animating the Group Code

### Selected Animation Driver
**Driver Chosen**: Audio  
I introduced audio as the primary driver of animation to create a more interactive and dynamic visual experience.

### Details of the Individual Approach
To animate the group code, I integrated audio-driven properties by using amplitude data from the audio file to manipulate visual elements dynamically. Below are the specific ways I expanded upon the group code:

1. **Audio Loading and Playback Control**:
   - **Audio Loading**: I implemented the `preload()` function to load an audio file using `loadSound()`, ensuring the audio is ready to play when the sketch starts.
   - **Play/Pause Button**: I introduced a play/pause button to control audio playback with a `mousePressed` event that toggles between play and pause states. This provides an interactive way for users to start and stop the audio.

2. **Volume Control Using Slider**:
   - **Slider for Volume Adjustment**: I added a volume slider using `createSlider`, allowing real-time adjustment of audio volume. This slider is mapped to the audio’s volume using `setVolume`, enabling users to control sound intensity dynamically.

3. **Amplitude Analysis**:
   - **Amplitude Mapping**: I used the `p5.Amplitude()` function to obtain amplitude data from the audio, which I mapped to a variable `mv` to drive various visual properties, such as vertical oscillation. This mapping enables visuals to respond dynamically to the music.

4. **Dynamic Visuals with Audio**:
   - **Vertical Oscillation in Green Squares**: By linking amplitude data to the vertical positioning of elements in `drawGreenSquares`, I created an oscillating effect that makes it appear as though these elements are “dancing” to the music. 

### Animated Properties and Uniqueness from Group Code
   - **Vertical Oscillation in Green Squares**: The green squares now exhibit a vertical oscillation effect based on audio amplitude, making them responsive to the audio. I am the only group member who designed interactive visuals by linking the green squares to the audio.

### Inspiration and Technical Explanation
The inspiration for the "dancing" effect in the visuals came from group discussions. Although no specific images were used as visual references, I drew technical inspiration from the following projects:

   - **Volume Slider Visualization**: The p5.js example with a volume slider [here](https://editor.p5js.org/mbardin/sketches/tEHQnMxt7) influenced the way I implemented interactive volume control. This example guided the creation of a responsive slider that allows users to control audio levels in real-time.
   
   - **Sound Visualization**: The p5.js sound visualization project [here](https://js6450.github.io/p5SoundVis.html) provided a creative basis for synchronizing audio with animations, allowing visual elements to change in sync with the audio amplitude.

### Summary of Changes
Overall, I made extensive changes to the group code, including the addition of audio loading, playback controls, volume adjustment, amplitude-based animation, and audio-responsive oscillation effects. These changes enable the visuals to interact dynamically with the audio, creating an immersive audiovisual experience.