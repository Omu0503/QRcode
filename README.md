# Smart Packaging QR Code Detection App

This repository contains the source code for an iOS application designed to enhance the smart packaging of perishable fruits. The app detects whether a fruit is edible based on the label attached to it. The labels are in two colors: red and algae-green. The app uses QR code detection to read the labels and OpenCV for color detection.

<div style="display: flex; justify-content: space-between;">
  <img src="/IMG_2112.PNG" alt="Information Page" style="width: 48%;"/>
  <img src="/IMG_2118.PNG" alt="Photo Page" style="width: 48%;"/>
</div>

## Features

- **QR Code Detection**: Reads QR codes on fruit packaging.
- **Color Detection**: Identifies label color using OpenCV embedded through Objective-C in a Swift environment.
- **Edibility Check**: Determines if the fruit is edible based on the label color.

## How it was built?

- The app was coded in **Swift**.
- OpenCV, the library used for image processing, was embedded using objective-C.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/smart-packaging-qr-detection.git
