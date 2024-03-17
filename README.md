## Text to Icon Converter

This project is a simple web application that converts text input into corresponding emoji icons. It allows users to encode text into emoji icons and decode emoji icons back into text. Additionally, it provides a history feature to keep track of recent conversions.

### Features

- **Encode Text to Icons**: Users can input text, and the application will convert each character into a corresponding emoji icon.
- **Decode Icons to Text**: Users can input emoji icons, and the application will convert them back into text.
- **History**: The application keeps track of recent conversions, allowing users to easily access and reuse previous inputs and outputs.
- **Dark Mode Toggle**: Users can switch between light and dark themes for better readability.

### Technologies Used

- **HTML/CSS/JavaScript**: The frontend of the application is built using HTML for structure, CSS for styling, and JavaScript for functionality.
- **Firebase**: Firebase is used for user authentication and data storage. User accounts are authenticated using Firebase Authentication, and conversion history is stored in the Firebase Realtime Database.
  
### Usage

1. Input Text: Enter the text you want to encode or the emoji icons you want to decode into the input field.
2. Encode/Decode: Click the corresponding button to encode or decode the input text.
3. Copy Output: Click the "Copy" button to copy the output text.
4. View History: Click the "History" button to view recent conversion history.
5. Dark Mode Toggle: Click the moon icon to switch between light and dark themes.

### How to Run

1. Clone this repository to your local machine.
2. Open the `index.html` file in your web browser.
3. Start converting text to emoji icons and vice versa!

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.