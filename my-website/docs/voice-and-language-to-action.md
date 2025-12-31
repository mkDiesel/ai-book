---
sidebar_position: 9
---

# Voice & Language to Action

This chapter explores how voice and language are translated to action, including using Whisper for voice commands and translating natural-language task understanding into ROS 2 actions.

## Voice Commands using Whisper

**Whisper** is an open-source AI model by OpenAI for robust speech-to-text transcription. It can be used in robotics to:
-   **Convert Speech to Text**: Transcribe human voice commands into text that an LLM can process.
-   **Handle Various Accents/Noises**: Provide accurate transcriptions even in challenging acoustic environments.

## Natural-Language Task Understanding

Once voice commands are transcribed, an LLM can process the natural language to understand the user's intent. This involves:
-   **Parsing Commands**: Breaking down complex sentences into actionable components.
-   **Contextual Understanding**: Using surrounding information and knowledge about the robot's capabilities and environment to interpret the command.

## Translating Intent into ROS 2 Actions

The understood intent needs to be translated into executable commands for the robot. In a ROS 2 system, this typically means:
-   **Mapping to ROS 2 Services/Actions**: Converting high-level intent (e.g., "pick up the red cube") into calls to specific ROS 2 services or actions that control the robot's grippers or manipulators.
-   **Parameterization**: Extracting relevant parameters (e.g., "red", "cube") from the natural language command to populate the ROS 2 message fields.
