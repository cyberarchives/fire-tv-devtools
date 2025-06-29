# 𝗟𝗼𝗮𝗱𝗶𝗻𝗴𝗦𝗰𝗿𝗲𝗲𝗻𝘀 Creation Guide

Follow these steps to create custom loading screens for your game.

## Requirements

- **Camera**: There must be a camera in the scene (required)
- **Background Music**: Optional component for audio during loading

## Scene Layout

Your loading screen should follow this hierarchy structure:

![Layout Example](https://snoofz.net/public/uploads/2e1f9dfa-c3cd-4730-89ad-222f2b2efa72.PNG)

## Step-by-Step Instructions

### 1. Create the Loading Screen Structure

1. Create an **Empty GameObject** in your scene
2. **Important**: Name it exactly `Loading Screen` - this is required for the system to work properly
3. Add all your loading screen components (UI elements, camera, background music, etc.) as children of this Loading Screen object

### 2. Create the Prefab

1. Drag the `Loading Screen` GameObject from the **Hierarchy** into your **Project Files** (Assets folder)
2. This will automatically create a prefab of your loading screen

### 3. Create the Asset Bundle

1. Download and import [Zuno's Asset Bundle Creator](https://snoofz.net/public/uploads/293962aa-48f0-45aa-8edf-e4eba6296fb5.cs) into your project

2. Open the Asset Bundle Creator from the Unity menu

3. The UI should look like this after setup:

   - **Prefab to Bundle**: Drag your Loading Screen prefab here
   - **AssetBundle Name**: Enter `LoadingScreenBundle` (or your preferred name)
   - **Build Target**: Select your target platform

4. Click **Create AssetBundle** to generate the bundle

## Final Notes

- Make sure the Empty GameObject is named exactly `Loading Screen` - other names will not work
- The camera is mandatory for the loading screen to display properly
- Background music is optional but can enhance the user experience
- Test your loading screen prefab before creating the asset bundle

Your loading screen is now ready to be used in the game!
