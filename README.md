AR Ancient Egyptian Artifacts Explorer
Media Informatics Project

Submitted by:

Youstina Raouf — 13001755

Manuel Youssef — 13006600

Chantal Sherif — 13007034

Ebram Hany — 13002244

Date: May 23, 2025

1. Project Overview

This project is an Augmented Reality (AR) treasure hunt game centered around Ancient Egyptian artifacts.
Players use their mobile device camera to scan printed image markers. Each marker reveals a 3D artifact in AR, and players must answer historical quiz questions to collect treasures and progress through the experience.

The main objective is to create an interactive, educational experience that combines historical learning with immersive technology.

2. Design and Implementation
2.1 AR Framework

Developed using Unity with the Vuforia SDK for AR image tracking.

The AR Camera detects physical image targets and anchors 3D models to them in real time.

2.2 Artifacts

Five imported 3D artifacts (e.g., sarcophagus, scarab, statue).

Two Unity-created models: a pyramid and an obelisk.

All models are textured and positioned above image targets for correct spatial alignment.

2.3 Image Targets

Each artifact corresponds to a unique Vuforia-trained image target.

The printed targets are distributed in the physical environment for players to find.

2.4 Interaction Design

Players interact by tapping on AR objects. Upon interaction:

A quiz appears with a historical question.

A correct answer removes the artifact from view and increases the player’s score.

A sound effect plays when an artifact appears and upon successful collection.

2.5 User Interface

A score tracker displays treasures collected.

Text clues guide the player throughout the experience.

Includes a final win screen and a quit option.

2.6 Audio Integration

Sound feedback enhances immersion and provides a sense of achievement when players collect artifacts or answer correctly.

3. User Testing and Feedback

A user questionnaire was distributed to five participants who tested the game. The survey combined rating scales with open-ended questions to evaluate usability, engagement, and learning outcomes.

3.1 Key Findings

1. Gameplay Experience

Some users reported camera lag or marker detection issues.

Others found the sounds and reward system engaging and motivating.

2. Educational Value

Users reported learning new information about Ancient Egyptian culture, including:

Mummification and beliefs about the afterlife.

The structure and symbolism of pyramids.

The significance of obelisks.

The role of Hatshepsut as the first female pharaoh.

3. Suggested Improvements

Improve image recognition speed and reliability under different lighting conditions.

Add more levels and progressively harder questions.

Enhance quiz interface design and visual clarity of clues.

4. Evaluation
4.1 Strengths

Effective integration of educational content with interactive AR gameplay.

Strong sense of immersion through 3D models and responsive user feedback.

4.2 Areas for Improvement

AR tracking sensitivity should be optimized for low-light environments.

An introductory tutorial could improve clarity for first-time users.

5. Conclusion

The AR Ancient Egyptian Artifacts Explorer successfully demonstrates how Augmented Reality can be used to create an interactive and educational experience.
Through user testing and feedback, the project identified both its strengths and potential areas for enhancement. The results highlight AR’s ability to make historical learning engaging, interactive, and accessible to users in a gamified format.
