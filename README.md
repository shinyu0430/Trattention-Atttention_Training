# Trattention-Attention_Training

![](https://imgur.com/PtP6Lva.jpg)

## 1. Introduction
In recent years, due to the excessive exposure of children to environmental stimuli and factors such as genetic inheritance and personality, many children are prone to lack of focus and easily get distracted by external influences. A long-term study in the UK, tracking over 10,000 children, discovered that the performance of attention at the age of seven could predict their academic achievement in high school at the age of sixteen. Children with good attention skills tend to have better developmental potential in their academic pursuits compared to those with attention difficulties.

Moreover, Kenneth Rubin advocates for "intrinsic motivation" and suggests that engaging children in playful activities can foster focus, creativity, social skills, and empathy. Guiding children through game-based approaches can further stimulate their interests and cultivate attention while they are in a joyful state of mind. We believe that by incorporating game-based approaches, children can participate autonomously and achieve positive experiences in enhancing their attention skills. In conclusion, our team aims to design a system that combines smart devices to help children improve their attention skills in a stress-free and enjoyable manner.

## 2. Creative Description
This system combines the MAD GAZE bone conduction smartwatch, EEG headsets, and tablets to provide children with attention training games. The system utilizes a user-friendly interface to ensure that children can easily and effectively use the system. By integrating multiple smart devices, innovative gameplay experiences using the smartwatch, and measuring attention levels through EEG, we can compare the changes in attention levels before and after training.

## 3. Overview of System Features

1. EEG Detection System:
   The system monitors attention levels by having users wear EEG headsets while reading short articles. After reading, users are asked simple questions to assess their comprehension. The EEG data is analyzed to obtain attention level values, which are then uploaded to the database to track changes in attention levels.

2. Bone Conduction Gesture Training:
   The system is based on three theories:
   - The Pomodoro Technique: Training memory while improving focus.
   - Stroop Test: Users selectively filter out unnecessary information.
   - Shulte Grid Theory: Training visual, auditory, and kinesthetic stability.

   The system incorporates the Mad Gaze Watch bone conduction smartwatch to enhance users' attention levels. Unlike traditional games, this system focuses on interactive experiences, hand-eye coordination, and attention cultivation. The training is divided into three categories: pattern matching, Shulte grid, and memory card flipping, each with different difficulty levels.

3. User Accounts:
   Users are required to fill out personal information such as name, gender, and age before logging in for the first time. This data is stored in the database for users to view their game data and attention level values.

4. Visualization of User Data:
   To facilitate user understanding, this feature visually presents "EEG data from attention tests," "training results," "recent training duration comparisons," and "comparisons of the highest duration with other users' averages" in graphical charts. This allows users to quickly assess their progress in improving attention levels.

## 4. System Highlights
Educational Application of Sensory Interaction Technology:
This system focuses on smart devices and innovative designs to create a new sensory training mode. By combining bone conduction gestures with tablet-based operations, users can train their alternating attention skills—shifting attention between different targets to complete tasks. For example, users alternate their attention between gesture controls and completing games to enhance their training.

Precise Measurement with Wearable Devices:
This system utilizes the NeuroSky EEG headset, which is portable, cost-effective, and highly accurate. Compared to research-grade EEG devices, NeuroSky's EEG sensors have an accuracy rate of over 96%. The system uses NeuroSky's algorithms to determine the user's attention level based on the eSense Attention Index (ranging from 0 to 100).

User-Centered Design Approach:
Designed with a focus on the user, the system incorporates user testing to optimize the user experience. The interface is designed to be simple, user-friendly, and intuitive, minimizing barriers to use. The system aims to create a highly user-friendly game design that makes attention training engaging and enjoyable, eliminating the perceived distance and coldness often associated with such training programs.

## 5. System Development Tools and Technologies

![](https://imgur.com/tLAQJ2p.jpg)

The app utilizes Firebase Authentication for user login authentication, allowing authorized users to access and operate the system. The app uploads data to Firebase storage, including personal information, game records, and attention analysis records. The app is developed using Java programming language with Android Studio as the code compiler.

## 6. Target Users
The main target audience for our system is children aged 8-12 who experience attention difficulties. We aim to assist these children in improving their attention skills through the use of our system.The system is primarily intended for indoor use. Users wear the NeuroSky EEG headset to measure their attention levels while reading, and they use a tablet to access the training games and view the results. The development environment for this system involves Mad Gaze Watch Android SDK and Android Studio, suitable for tablet devices.
