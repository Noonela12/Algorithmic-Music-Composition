# Algorithmic Music Composition System

## Overview

This project implements an algorithmic music composition system using Markov Chains and Genetic Algorithms to generate musical compositions. The system evolves transition probability matrices for pitches, rhythms, and chords to produce high-quality musical pieces. It includes functionality for generating compositions, evaluating them with genre-specific motives, and exporting results in MIDI and MusicXML formats.

## Features

- **Markov Chains**: Generate musical sequences based on transition probability matrices for pitches, rhythms, and chords.
- **Genetic Algorithms**: Evolve musical compositions through selection, crossover, and mutation.
- **Genre-Specific Motives**: Tailor compositions to specific musical styles by incorporating predefined or generated motives.
- **MIDI and MusicXML Export**: Save compositions in formats suitable for playback and analysis in digital audio workstations or music notation software.

## Requirements

- Python 3.x
- `music21` library
- Other dependencies listed in `requirements.txt`



## Usage

### Generating Compositions

1. **Create Random Genomes**: Generate initial random transition probability matrices.
2. **Generate Composition**: Create a musical composition based on a genome’s matrices.
3. **Evaluate Composition**: Evaluate the composition using genre-specific motives.
4. **Export to MIDI and MusicXML**: Save the generated composition in MIDI and MusicXML formats.

### Running the Genetic Algorithm

1. **Run Evolution**: Perform generational evolution to improve compositions based on fitness scores.

## Genre-Specific Motives

The system supports various genres with predefined or generated motives, including:

- **Blues**: Uses the minor pentatonic scale with blue notes.
- **Jazz**: Incorporates syncopated rhythms and the ii-V-I chord progression.
- **Classical**: Features stepwise motion and functional harmony.
- **EDM**: Focuses on repetitive, rhythmically driving patterns.



