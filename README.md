# Random Number Generator

A simple Random Number Generator built using HTML, CSS, and JavaScript. This project generates a random number between 1 and 999 with a clean and user-friendly interface.

## Features

- Generates random numbers between 1 and 999
- Intuitive and easy-to-use interface
- Responsive design for desktop and mobile devices

## Technologies Used

- **HTML**: For the structure of the application
- **CSS**: For styling the user interface
- **JavaScript**: For the random number generation logic

## How to Use

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/adhikarilaxman/Random-Number-Generator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Random-Number-Generator
   ```

3. Open the `index.html` file in your browser to run the application.

4. Click the "Roll" button to get a random number between 1 and 999.

## Code Example

Here is the JavaScript code for generating random numbers:

```javascript
const myButton = document.getElementById("myButton");
const myLabel = document.getElementById("myLabel");
const min = 1;
const max = 999;

myLabel.textContent = "Click the button to generate a number!";

myButton.onclick = function () {
    let randomNum = Math.floor(Math.random() * (max - min + 1)) + min;
    myLabel.textContent = randomNum;
};
```

## Future Enhancements

- Add a feature to allow users to specify their own range
- Include a history of previously generated numbers
- Improve UI/UX design
- Add dark mode support

## Contributing

Contributions are welcome! If you'd like to improve this project, feel free to fork the repository and submit a pull request.


## Author

Developed by [Laxman Adhikari](https://github.com/adhikarilaxman). Feel free to reach out if you have any questions or suggestions!
