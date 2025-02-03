# National Identity Card Verification System

This project is a web-based **National Identity Card Verification System** for verifying NID (National Identity) numbers in Bangladesh. It utilizes an API to verify the authenticity of a given NID number and displays the results to the user in a neat and user-friendly interface.

## Features

- **NID Number Verification**: Input NID number (10 digits) and date of birth for verification.
- **API Integration**: Connects to an external API to verify NID and fetch relevant data.
- **Responsive Design**: The app is fully responsive, ensuring it works well on mobile, tablet, and desktop devices.
- **Dark Mode**: Users can toggle between light and dark mode for a more comfortable viewing experience.
- **PDF Generation**: Users can generate a PDF of the verification results.
- **Print Option**: Users can print the verification results directly from the application.
- **User-Friendly Interface**: The design is intuitive and simple, allowing easy navigation and quick verification.

## Preview Images

Here are some preview images of the application:

![NID Verification System](https://github.com/shahin0075/NationalIdentityCardVerificationSystem/blob/master/nid.png)

![Screenshot 1](https://github.com/shahin0075/NationalIdentityCardVerificationSystem/blob/master/Apple%20iPhone%2016%20Pro%20Max%20Screenshot%201.png)

![Screenshot 2](https://github.com/shahin0075/NationalIdentityCardVerificationSystem/blob/master/Apple%20iPhone%2016%20Pro%20Max%20Screenshot%202.png)

![Screenshot 3](https://github.com/shahin0075/NationalIdentityCardVerificationSystem/blob/master/Apple%20iPhone%2016%20Pro%20Max%20Screenshot%203.png)

![Screenshot 4](https://github.com/shahin0075/NationalIdentityCardVerificationSystem/blob/master/Apple%20iPhone%2016%20Pro%20Max%20Screenshot%204.png)

## Installation

To get started with this project, follow these steps:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/shahin0075/NationalIdentityCardVerificationSystem.git
    ```

2. **Navigate to the Project Directory**
    ```bash
    cd NationalIdentityCardVerificationSystem
    ```

3. **Open the `index.html` File**
    Open the `index.html` file in your browser to view the application.

## Technologies Used

- **HTML5**: Markup for the page structure.
- **CSS3**: Styling for the user interface, with custom styles for light and dark modes.
- **JavaScript**: Handles form submission, API calls, and DOM manipulation.
- **Bootstrap 5**: For responsive layout and styling.
- **Font Awesome**: For icons.
- **html2pdf.js**: For generating PDF files from the result data.





## Dark Mode Toggle

The application includes a **dark mode** feature that allows users to switch between light and dark themes for better readability depending on their preference.

## How It Works

1. **Enter NID Number**: The user enters a 10-digit NID number and their date of birth.
2. **Submit the Form**: Upon submission, the form sends a request to the API to verify the NID number and fetch personal details such as name, gender, date of birth, address, etc.
3. **Display Results**: The verification results are displayed, showing details about the NID holder.
4. **PDF or Print**: The user can either print the results or download a PDF version of the verification.

## Contribution

Feel free to fork the repository, make changes, and submit a pull request. All contributions are welcome!

## Developer

**Mohammad Sheikh Shahinur Rahman**  
Software Engineer, IT Amadersomaj Inc.

## License

This project is open-source and available under the [MIT License](LICENSE).
