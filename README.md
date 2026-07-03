# SmartSlideGenerator

SmartSlideGenerator is a C#/.NET MVP that generates PowerPoint presentations automatically from structured input.

## Goal

The goal of this project is to transform structured content into a PowerPoint presentation.

For now, the project focuses on the core generation pipeline without AI integration.

## Current MVP

The current version can:

- Read a structured text file
- Read a JSON file
- Convert the input into a `PresentationPlan`
- Generate a `.pptx` PowerPoint file
- Apply a simple visual template
- Generate a demo presentation about ATMView

## Current Pipeline

```text
Text or JSON input
↓
Parser / Reader
↓
PresentationPlan
↓
PowerPointExporter
↓
PowerPoint file
