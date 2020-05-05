# Wuchi's Throwing Algorithm

A smoothing algorithm that assists the accuracy and trajectory of an interactable object when thrown at a given target.

Originally built and implemented as the core interaction for [Hooplord](https://www.wuchi.online/hooplord), a virtual reality experience centered around basketball shooting mechanics.

![Hooplord Demo](GIF/HooplordThrow.gif)(https://twitter.com/WuchiOnline/status/1248385466593718277)

## Features

- Designed as a fun-to-learn, hard-to-master interaction with decreased user fatigue and frustration when compared to standard throwing implementations.

- Multi-factor detection system that guesses if a throw is intended towards the target object before applying smoothing algorithm.

- Significantly lowers required accuracy by recalculating throw velocities within a proximity threshold of the target object.

- Maintains high accuracy ceiling that rewards precision and consistency.

- Adjusts for players of all heights and wingspans with a modifier based on release height.

- Can be further abstracted and configured for different desired results.

- This version has been refactored to extend the Unity XR Interaction Toolkit, but can easily be adapted for other interaction frameworks.

# Example Project

## Built With

This project showcases a basic implementation using primitives, which utilizes:

* Unity 2019.3.2f1
* Oculus XR Plugin 1.3.3
* Unity XR Interaction Toolkit 0.9.4

Oculus XR Plugin and Unity XR Interaction Toolkit are pre-imported into the project.

## How do I explore the example project?

1. Clone or download the repo: ```git clone https://github.com/WuchiOnline/Wuchi-ThrowAlgo```
2. Open your Unity Hub.
3. Press Add and select the project folder.
4. Open up the example scene, which is located in the WuchiOnline/Scenes folder.
5. The example project natively supports all PC-compatible Oculus headsets. To use any other PC-compatible headset with this project:
- Open the Package Manager
- Install the Unity XR Management package
- Open the Project Settings
- Under the XR Plugin Management section, install the appropriate XR Plugin and Loader.
6. Press Play.

# Author

**Eric Wu** [@WuchiOnline] - [Twitter](https://twitter.com/WuchiOnline) - [GitHub](https://github.com/WuchiOnline) - [LinkedIn](https://www.linkedin.com/in/ericwu90/)

# License

Wuchi's Throwing Algorithm is licensed under the MIT License.