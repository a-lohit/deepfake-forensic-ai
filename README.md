# Multimodal Forensic AI Engine for Deepfake Video Detection

## Problem Statement
The rapid rise of deepfake and AI-generated videos poses serious risks to journalism, legal systems, elections, and personal reputation.

## Solution Overview
This project proposes a multimodal forensic AI engine that classifies videos into:
- Authentic (Real Human Video)
- Deepfake (Manipulated Human Video)
- AI-Generated (Fully Synthetic Video)

The system prioritizes biological realism, temporal consistency, and explainable forensic reasoning suitable for legal contexts.

## Core Analysis Pipeline
- Deepfake lineage tracking using temporal and frame-level artifacts
- Model attribution across GAN, Diffusion, and Hybrid pipelines
- Physiological consistency analysis (blink rate, breathing, micro-movements)
- Audio-visual emotional mismatch detection
- Intent and harm risk prediction
- Legal-grade explainable evidence reporting

## Tools & Platform
- Google AI Studio
- Gemini Multimodal Models
- Prompt Engineering

## How to Reproduce
1. Open Google AI Studio
2. Select a Gemini multimodal model
3. Upload a video file
4. Paste the prompt from `prompts/forensic_engine_prompt.md`
5. Run the analysis and observe the structured output

## Use Cases
- Journalism verification
- Courtroom evidence analysis
- Election misinformation detection
- Identity fraud prevention

## Future Improvements
- Live video verification support
- Automated forensic visualization
- API-based deployment
