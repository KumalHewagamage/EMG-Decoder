# Enabling Communication for Paralyzed Individuals through EMG-based Speech Synthesis

## Problem Statement:
The problem we aim to address is the communication challenges faced by paralyzed individuals in the healthcare sector. Many paralyzed individuals find it difficult to express their thoughts and needs verbally, leading to a diminished quality of life. In Sri Lanka, the attention given to developing solutions for the disabilities of paralyzed individuals has been limited.

## Solution Overview:
Our solution involves the creation of a device that processes EMG signals from paralyzed individuals to decode their neural impulses. Trained machine learning models, using datasets of neural impulses, generate rough sentences based on the patient's intent. Subsequently, a Language Model (LLM) refines these sentences for precise communication. The output is then transmitted through a Text-To-Speech (TTS) Model to the listener.

## Methodology:

### 1. Signal Processing:
EEG or EMG signals are processed to extract relevant neural impulses.

### 2. ML Decoding:
Trained ML models decode neural impulses into rough sentences.

### 3. LLM Refinement:
Language models refine rough sentences for precise communication.

### 4. Audio Transmission:
Processed sentences are transmitted through speakers by TTS.

## Goals:

* Develop a device that can accurately decode neural impulses from EMG signals
* Train machine learning models to generate rough sentences based on patient intent
* Refine sentences using Language Models for precise communication
* Integrate Text-To-Speech Model for audio transmission

## Impact:
Our solution aims to improve the quality of life for paralyzed individuals by enabling them to communicate effectively with healthcare professionals and loved ones. This project has the potential to make a significant impact in the healthcare sector, particularly in Sri Lanka where attention to disabilities has been limited.

## Repository Structure:

* `data`: contains datasets of neural impulses and corresponding sentences
* `models`: contains trained machine learning models and Language Models
* `signal_processing`: contains code for processing EEG or EMG signals
* `ml_decoding`: contains code for decoding neural impulses into rough sentences
* `llm_refinement`: contains code for refining sentences using Language Models
* `tts`: contains code for Text-To-Speech Model

## Contributing:
We welcome contributions from developers, researchers, and healthcare professionals. If you're interested in contributing to this project, please fork the repository and submit a pull request.

## License:
This project is licensed under the MIT License. See LICENSE for details.

## Acknowledgments:
We would like to acknowledge the support of [insert acknowledgments here].
