# NASA Photo of the Day

NASA Photo of the Day is a simple web application that fetches and displays the Astronomy Picture of the Day from NASA's API. This project was created by Mark Gowen.

## Features

- Users can view the Astronomy Picture of the Day from NASA's API.
- Users can view information about the photo, including its title, date, and explanation.

## Installation

To run this project locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the necessary dependencies by running the following command in the project directory:

```bash
npm install
```

3. Obtain an API key from NASA's [Open APIs](https://api.nasa.gov/) website.
4. Create a `.env` file in the root of the project and add the following line, replacing `YOUR_API_KEY` with your actual API key:

```bash
API_KEY=YOUR_API_KEY
```

5. Run the following command to start the development server:

```bash
npm start
```

6. Open `http://localhost:3000` in your web browser to view the app.

Note: Make sure to keep your API key private and never share it publicly.

## Technologies Used

- [React](https://reactjs.org/) - a JavaScript library for building user interfaces.
- [Axios](https://github.com/axios/axios) - a promise-based HTTP client for making API requests.
- [Styled Components](https://styled-components.com/) - a CSS-in-JS library for styling React components.

## Deployment

This project is deployed using [Vercel](https://vercel.com/). Any changes pushed to the `main` branch of this repository will automatically trigger a new deployment.

## Credits

This project was created by Mark Gowen. Thank you to NASA for providing such a great API!

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use and modify this code for your own purposes.
