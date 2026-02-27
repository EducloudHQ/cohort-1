## Project name: iLens

# Project Description
iLens is a mobile application that transforms screenshots from static images into actionable interfaces. The product was born from a real, universal frustration: information that is visible inside an image but impossible to act on — a link you cannot tap, an event flyer with a registration URL, a Google Meet invite trapped in a screenshot.

## How It Works

Step 1
User takes a screenshot (any app, any content)
Step 2
iLens detects the screenshot via Media Store Observer
Step 3
On-device AI analyzes image — determines if actionable content exists
Step 4
If actionable: overlay appears with relevant action buttons
Step 5
If not actionable: iLens stays silent. No noise, no interruption.


# Developer's name
Ribert Kandi Junior

# Github
https://github.com/Coding-Wave-Academy/iLens


# iLens — 10 Digestible Layers

1. Screenshot Detection (Media Store Observer)
2. Image Preprocessing (crop, clean, compress before analysis)
3. OCR & Text Extraction (ML Kit on-device)
4. QR / Barcode Detection
5. Content Parser (URLs, phones, dates, addresses via regex + NLP)
6. Intent Classifier (what does the user most likely want to do?)
7. Overlay UI (floating action layer displayed to user)
8. Action Router (executes the chosen action — browser, calendar, maps, dialer)
9. History & Storage (local database of processed screenshots)
10. Cloud Sync & Premium Layer (optional backup, cross-device, advanced AI)
