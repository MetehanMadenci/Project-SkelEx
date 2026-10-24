# SkelEx — Augmented Reality Anatomy & Interactive Quiz Platform

## About the Project

**SkelEx** is a cross-platform educational application designed to combine augmented reality (AR), 3D anatomical visualization, optical character recognition (OCR), and competitive quizzes in a single learning experience.

Developed with Unity, SkelEx aims to help students explore the human skeletal system through interactive 3D models while reinforcing their knowledge through personalized quizzes and real-time multiplayer competitions.

The application is designed for both **iOS and Android** devices.

## Key Features

### 1. Augmented Reality Skeleton Visualization

- Display 3D skeletal models in a real-world environment.
- Explore individual bones and anatomical structures.
- Select specific bones for detailed examination.
- Hide other skeletal components to isolate selected structures.
- Zoom in on selected bones for closer inspection.

### 2. OCR-Based Question Creation

SkelEx aims to simplify quiz preparation by allowing users to extract questions from printed or digital test materials.

- Capture test questions using the device camera.
- Extract text from images using Optical Character Recognition (OCR).
- Review and edit extracted questions before saving them.
- Organize questions into custom quizzes.
- Reuse saved questions to create new quizzes.

OCR accuracy may vary depending on image quality, handwriting, formatting, and mathematical or anatomical terminology. Extracted questions should be reviewed before being published.

### 3. Ready-Made Quizzes

Users can access available quizzes without having to create every question themselves.

- Browse quizzes prepared in advance.
- Select quizzes by topic or difficulty, where supported.
- Practice skeletal anatomy and related educational subjects.
- Revisit quizzes to reinforce learning.

The availability of ready-made quizzes depends on the content provided by the application or its connected content source.

### 4. Real-Time Multiplayer Quiz Competitions

SkelEx aims to provide a Kahoot!-style quiz experience where students can compete in real time.

- Create or join a quiz room.
- Bring multiple students together in the same virtual room.
- Start a shared quiz session.
- Answer questions within a time limit.
- Automatically evaluate submitted answers.
- Calculate scores based on correctness and, if implemented, response speed.
- Display rankings and a leaderboard.
- Identify the highest-scoring participants at the end of the competition.

A synchronized multiplayer experience requires a networking and session-management system so that participants receive the same questions and time limits.

### 5. Educational Gamification

The combination of AR and competitive quizzes aims to make learning more interactive and engaging.

- Learn anatomical structures through 3D visualization.
- Test knowledge through practice quizzes.
- Challenge classmates in timed competitions.
- Track quiz results and compare participant scores.

## Technologies

| Technology | Purpose |
|---|---|
| Unity | Application development and 3D visualization |
| C# | Application logic and game mechanics |
| AR Foundation | Cross-platform AR functionality |
| ARCore | AR support on compatible Android devices |
| ARKit | AR support on compatible iOS devices |
| Unity UI | Interactive menus and user interface |
| OCR technology | Extracting questions from test images |
| Networking solution | Real-time multiplayer quiz rooms |
| Backend and database | Saving questions, quizzes, users, and results |

The specific OCR engine, networking solution, and backend technology will depend on the final implementation.

## How SkelEx Works

### Anatomy Learning

1. Launch the application on a compatible mobile device.
2. Place the 3D skeletal model in the AR environment.
3. Select a bone to examine.
4. Hide other bones or zoom in on the selected structure.
5. Use the visualized anatomy to support learning.

### Creating a Quiz with OCR

1. Capture a question from a test book using the camera.
2. Extract the question text through OCR.
3. Review and correct the extracted content.
4. Add the question and its answer choices to a quiz.
5. Save the quiz for future use.

### Joining a Live Quiz Competition

1. Create a quiz room or join an existing one.
2. Wait for the participants to enter.
3. Start the synchronized quiz session.
4. Answer each question before the timer expires.
5. View scores and rankings after the answers are evaluated.

## Project Objectives

- Develop an interactive AR-based anatomy learning experience.
- Support detailed exploration of the human skeletal system.
- Reduce the effort required to digitize test questions through OCR.
- Enable students to create and reuse personalized quizzes.
- Support collaborative and competitive learning through multiplayer quiz rooms.
- Encourage active learning through time-limited questions, automatic scoring, and leaderboards.
- Provide a foundation for an integrated educational platform across iOS and Android.

## Target Platforms

- **iOS:** Devices compatible with the required ARKit features.
- **Android:** Devices compatible with the required ARCore features.

Platform support depends on device capabilities and the final configuration of the application.

## Development Status

SkelEx combines several areas of development:

- AR-based skeletal visualization.
- Interactive bone selection and model controls.
- OCR-based question extraction and quiz creation.
- Ready-made quiz management.
- Multiplayer rooms, timed questions, scoring, and leaderboards.

Individual features should be marked as completed, in progress, or planned according to their actual implementation status.

## Academic Project

SkelEx is a graduation project exploring the integration of augmented reality, anatomy education, OCR-based content creation, and competitive digital learning.

## Developer Information

- **Project Name:** SkelEx
- **Project Type:** Graduation Project
- **Fields:** Augmented Reality, Educational Technology, OCR, Gamification
- **Development Engine:** Unity
- **Target Platforms:** iOS and Android
- **Developer:** Metehan Madenci, Simay Akgündüz, Hüseyin Can Benli, Semih Oktay Özcan, Irmak Kılınç
- **University / Department:** Atılım University / Information Systems Engineering
- **Academic Supervisor:** Selma Nazlıoğlu
- **Year:** 2025

