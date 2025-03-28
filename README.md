# Slide Types Documentation

## Basic Slides
- `title.tex`: Title slide with presentation info
- `sample.tex`: Basic bullet point slide
- `closing.tex`: Thank you slide with contact info

## Layout Slides
- `two-column.tex`: Two-column layout for comparing content
- `three-columns.tex`: Three-column layout for feature comparison

## Feature Slides
- `big-concept.tex`: Large icon with description
- `quote.tex`: Full-screen quote display
- `big-numbers.tex`: Important statistics with icons
- `process.tex`: Process flow diagram with descriptions
- `mobile.tex`: Device mockup for showcasing apps
- `image.tex`: Image with caption layout
- `table.tex`: Data comparison table
- `icons.tex`: Icon grid display

## Usage
Each slide is designed as a standalone component. To use:

1. Import the slide in main.tex using: \input{slides/slidename}
2. Customize content within the frame
3. Modify colors using the defined color scheme
4. Adjust spacing using standard LaTeX commands

## Styling Guidelines
- Use \frametitle for consistent headers
- Maintain consistent font sizes
- Use predefined colors from colors.sty
- Follow spacing conventions