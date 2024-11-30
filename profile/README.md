# ChromMood : Emotion to Color

Text to Emotion, Emotion to Color: We transform your words into stories painted with beautiful colors.

## Overview
This service analyzes the emotional content of text and visualizes it through colors. By processing your input text, it determines the emotional tone and assigns corresponding colors that reflect those emotions, creating a unique visual representation of sentiment.

## Features
- **Sentiment Analysis**: Analyzes text to determine emotional content
- **Color Mapping**: Converts emotional scores into meaningful colors
- **Emotion Labels**: Provides specific emotion labels (e.g., Serenity, Trust, Amazement)
- **Visual Feedback**: Shows sentiment scores with color-coded progress bars
- **Real-time Processing**: Instant analysis and visualization

## Color-Emotion Mapping
- Very Positive (Serenity) - Bright Yellow (#FFD700)
- Positive (Trust) - Light Green (#98FB98)
- Slightly Positive (Amazement) - Sky Blue (#87CEEB)
- Neutral Positive (Interest) - Light Purple (#DDA0DD)
- Neutral - Gray (#808080)
- Neutral Negative (Pensiveness) - Dark Navy (#483D8B)
- Slightly Negative (Sadness) - Indigo (#4B0082)
- Negative (Remorse) - Brown (#8B4513)
- Very Negative (Grief) - Dark Red (#800000)

## Technology Stack
- Next.js
- React
- TypeScript
- Transformers.js (Xenova)
- Framer Motion
- Tailwind CSS

## Model
Using DistilBERT model fine-tuned for sentiment analysis:
- Model: "Xenova/distilbert-base-uncased-finetuned-sst-2-english"

## Usage
1. Enter your text in English
2. Click the "Analyze Sentiment" button
3. View the emotional analysis results and corresponding color visualization
4. See detailed sentiment scores with visual indicators

## Note
- Currently supports English text only
- Requires modern web browser for optimal performance
- Analysis is performed client-side for privacy
