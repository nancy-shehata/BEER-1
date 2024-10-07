                                                                                 Beer Selector App

## Overview:

**Beer Selector** is a simple Android application designed to help users choose a beer based on their preferred color. 
By selecting a beer color, the app suggests a brand that matches the selection. This app offers a straightforward user interface with a focus on ease of use and functionality.

## Features

- **Beer Color Selection**: The app provides a dropdown (spinner) that allows users to select a beer color from a list of options such as Light, Amber, Brown, and Dark.
- **Find Beer Button**: Once a color is selected, users can tap the "Find Beer" button to display a corresponding beer brand.
- **Dynamic Brand Display**: The selected beer brand is dynamically updated and displayed in the app.

## UI Elements

1. **Spinner (Beer Color)**: 
   - Allows users to choose a beer color from the predefined list (`Light`, `Amber`, `Brown`, `Dark`).
   - Defined in the `activity_main.xml` file, linked to the `beer_colors` array in `strings.xml`.

2. **Button (Find Beer)**: 
   - Triggers the beer selection process when clicked.
   - Uses the label defined in `strings.xml` (`Find Beer`).

3. **TextView (Beer Brand Display)**:
   - Initially displays "No beer selected," and gets updated based on the user's selection.
   - Updates dynamically when the "Find Beer" button is pressed.

## Technical Details

- **Main Activity**: The core logic for beer selection resides in the `MainActivity.kt` file. When the user selects a beer color and presses the button,
  the app retrieves the selection and updates the TextView with a corresponding beer brand.
  
- **Resources**: 
  - `strings.xml` defines all the string resources, including beer color options and button labels.
  - `activity_main.xml` defines the layout, ensuring the app is easy to navigate with clear elements.

## Getting Started

1. Clone the repository to your local machine.
2. Open the project in Android Studio.
3. Build and run the app on your Android device or emulator.
4. Select a beer color from the dropdown, press the "Find Beer" button, and view the brand recommendation!

## Future Improvements

- Add more beer brands and detailed recommendations based on additional factors (e.g., region, brewery).
- Implement additional features such as saving favorite beers or beer history.
