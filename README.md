## Infinty Prompt
Infinty Prompt is a a chrome extension designed to seamlessly improve and refine text inside any input field on the web using AI
It integrates with the Google Gemini API to enchance clarity, tone and structure while remaning fast, non intrusive and privacy focused

Source code is intentionally private due to security and intellectual property considerations

## Problem Statement
Writing high quality Prompt across different platforms is time consuming and repetitive

Existing AI tools often require:
- Switching tabs
- Copy pasting prompt
- Breaking user workflow

This creates friction and reduces productivity

## Solution
Infinty Prompt works directly inside input fields on any website
- Optimize Prompt in place
- Requires explicit user interaction
- Preserves layout, framework compatibility and user intent
- Feels invisble until you need it

## Key Features
- In place prompt optimization for inputs and text areas
- Floating action icon that appears only when needed
- AI powered refinement using Google Gemini
- Works with modern frameworks ( React, Angular etc )
- Dedicated Chrome Side Panel for extended Prompt Generation
- Replace and Regenerate outputs instantly
- Domain based exclusion support
- Clean, modern and minimal UI
- Privacy first and non intrusive by design

  ## High level Architecture
  The extension follows a modular architecture:
  - **Content Scripts**
  Detect user interaction, inject UI elements and safely replace prompt

  - **Background Service Worker**
  Handles secure AI API communication, validation and error handling

  - **Side Panel Interface**
  Provides an isolated chat style experience for advanced generation

  - **Google Gemini API**
Performs AI Prompt Optimization only on user initiated input

See full details in Architecture-Overview.md

## Prompt Engineering
Infinty Prompt uses structured prompt engineering to ensure:
- Clean and predictable output
- No unnecessary explanations
- Preserved tone and intent
- High reliability across use cases

  See full details in Prompt-Engineering-Strategy.md

  ## Privacy and Security
  User trust is a core principle
  - No background data collection
  - No keystroke logging
  - No analytics or tracking
  - No storage of user prompt
  - API Calls only happen on explicit user action
  - API keys are securely handled and never exposed
 
  Full policy available in Privacy-and-Security.md

  ## Permissions Overview
  All requested Chrome Permissions are:
  - Minimal
  - Purpose driven
  - Transparent

    Detailed breakdown Chrome-Extension-Permissions.md

  ## Testing
  The extension has been tested on
  - chatgpt
  - gemini
  - claude
  - Dynamic, framework heavy websites

  Focus areas
  - DOM stability
  - Event propagation
  - UI positioning
  - Framework compatibility
