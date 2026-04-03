[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Nigel1992)

# RunePresence

Formerly known as RuneScape 3 Discord Rich Presence Integration

![RunePresence Banner](https://github.com/Nigel1992/RS3-Discord-Status/assets/5491930/de469f47-c284-40db-b5a9-95e9d44e117e)

This Python script allows you to display your RuneScape 3 activities on your Discord profile using Rich Presence. It monitors a specific region of your screen for in-game images and updates your Discord status accordingly.

![RunePresence Preview](https://github.com/Nigel1992/RS3-Discord-Status/assets/5491930/af29c507-66f6-4367-9f66-e40b30d6cae7)

## Just want to use it instantly? [Compiled .exe]

1. Simply go to the releases tab and download the latest version.
2. Extract all archive contents into a new folder.
3. Run the .exe and input your info [will be auto saved/loaded (using settings.json)]
4. Enjoy!

## Changelog

#### Pre-release - Version 0.1 (2024-06-30)
- Added a GUI for easier usage.
- GUI will save your input after hitting "Start".

## TO-DO

1. Make the script read the current in-game level of detected skill and use in Discord Status.
2. Let it recognize the skill without the need for screen coordinates.

## Setup [Python Script]

### Prerequisites

1. **Python 3.x** installed on your system.
2. A **Discord account** and a registered application with a **client ID**. [see spoiler for details]

<details>
  <summary>How-to</summary>

### Adding Discord Developer Assets

1. Go to the Discord Developer Portal.
2. Create a new application or select an existing one.
3. Navigate to the “Rich Presence” tab.
4. Scroll down to the “Assets” section.
5. Click on “Add Image(s)” to upload your custom images (these can be icons, logos, or other graphics) (this will be your Logo below "Playing a game").
6. You’ll need to provide a name for each asset. This name will be used when referencing the asset in your code.
7. After uploading, you’ll see your assets listed under “Rich Presence Assets” on the same page.

### Using Your Assets in Code

In your Python script (or any other language), use the asset names you provided in the developer portal.

</details>

### Installation

1. Clone this repository to your local machine.
2. Install the required Python packages using pip:

    ```bash
    pip install pyautogui pypresence
    ```

3. Replace `'REPLACEWITHYOURCLIENTID'` in the script with your actual Discord application's client ID.

### Usage

1. Run the script:

    ```bash
    python Updater.py
    ```

2. The script will monitor the specified region of your screen for the images you've added.
3. When an image is detected, it will update your Discord Rich Presence status with the relevant activity name and a timer.

### Customization

- Adjust the `region` variable in the script to match the coordinates of the area where you expect the RuneScape 3 activity images to appear.
- Update the emojis with the appropriate emoji and activity names for your images.

### Notes

- Make sure your Discord application is running while using this script.
- You can customize the large image key (e.g., `'rslogo'`) to match your Discord assets. See: https://discord.com/developers/applications/YOURAPPID/rich-presence/assets

Made with help from AI. Feel free to modify and enhance this script according to your needs! 😊

Contact me on Discord: nigel.92

## Support This Project

Support this project! All donations go towards your chosen charity. You can pick any charity you'd like, and I will ensure the funds are sent their way. Please note that standard payment processing fees (Ko-fi & PayPal) will be deducted from the total. As a thank you, your name will be listed as a supporter/donor in this project. Feel free to email me at thedjskywalker@gmail.com for proof of the donation or to let me know which charity you've selected!
