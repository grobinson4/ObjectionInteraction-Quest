# ObjectionInteraction-Quest
Basic VR Object Interaction for Oculus Quest utilizing controllers and hand tracking

## Supported versions
- Unity 2019.3.15f1
- Oculus Integration 17.0

## Supported target devices
- Oculus Quest - Android / Windows Standalone w/ Link
- Oculus Rift/S - Windows Standalone

# Getting Started

## Installation
1. Import Oculus Integration
Download Oculus Integration 17.0 from Asset Store and import it.
- Alternatively just drag and drop the Oculus folder into Assets/

## Project Settings
1. In the `Build Settings` switch platform to Android
- Change Texture Compression to ASTC and Compression Method should be LZ4
- In `Player Settings` Install XR Plug-in Management and check Oculus under Plug-in Providers
- Under the `Player` tab enable `Auto Graphics API`, change Minimum API Level to atleast `Android 6.0 'Marshmellow' (API Level 23)
- In the `Quality` tab change Anisotrophic Textures to `Per Texture`, change Anti Aliasing to `4x Multi Sampling`, Disable Soft Particles


## Author
Gary D. Robinson [@grobinson__](https://twitter.com/grobinson__)


