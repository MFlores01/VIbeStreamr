# VIbeStreamr

A Face, Hand, and Full-Body tracking for livestreamers on the web!

VibeStreamr is a prototype app designed to elevate livestreaming experiences with dynamic avatars. Whether you're a VTuber, a content creator, or a gamer, VibeStremr brings your digital persona to life through real-time motion and face tracking, enabling a more engaging and immersive interaction with your audience.

It  features  dynamic camera angles, and  full-body tracking detection using Tensorflow.js and Mediapipe human pose detection models. 

Upload your own VRM avatar models for fun experience!

Sample VRM models located inside the "other vrm model for demo" are not mine and credit goes to the creators on Vroid Hub.

Come and see my own VRM model published on Vroid hub https://hub.vroid.com/en/characters/7715236166954773382/models/7650100852767285676


Use Cases:
  a. Livestreaming: VTubers can use VibeStremr to interact with their audience more dynamically. The app’s real-time tracking capabilities enhance live performances, making them more captivating and engaging.

  b. Gaming & Entertainment: VibeStremr allows VTubers or streamers to adopt VR avatars in gameplay, adding layers of immersion and creativity. Whether you're participating in role-playing or competitive events, this app enriches the streaming experience.
  
  c. Social Media: Content creators can utilize VibeStremr to produce dynamic content for social media platforms like TikTok, Instagram, or even create engaging VR stories.
  
Features:
  a. Motion & Face Tracking: Utilizing Kalidokit library, this prototype uses the pre-trained models such as facemesh, handpose, and holistic, these captures the facial expressions, eye movements, body posture, and hand gestures through a webcam, enabling accurate avatar animation.

  b. 3D Avatar Animation: Using Three.js, the VRM avatar model dynamically responds to real-time movements such as head turns, blinking, and lip-syncing.

  c. Webcam Integration: The webcam captures the video feed, and processes facial landmarks and pose to animate the avatar smoothly.

Pre-Trained Model
The pre-trained models employed in this prototype through the kalidokit library are facemesh, handpose, and holistic.

a. Facemesh: A model that capture detailed facial expressions and movements, like eyebrow raises, eye blinks, and mouth movements.
b. Handpose: A model that identifies 21 key points on each hand, enabling to capture hand gestures and finger movements. 
c. Holistic: A model that combines Facemesh, Handpose, and Pose models to provide full-body motion capture, including face, hands, and skeletal structure. 

Technical Stack:
  Three.js: Renders the 3D avatar environment.
  GLTF/VRM Loaders: Load and animate the VRM avatar models.
  Mediapipe Holistic: Provides real-time tracking of face, pose, and hands.
  Kalidokit: JS Library that translates motion data into smooth avatar animations.

