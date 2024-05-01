# D-ZOOM

D-ZOOM is a video conferencing application developed by DammyTech. It allows users to host and join video calls seamlessly. This project was built using Next.js and integrates with Clerk authentication and Stream APIs for enhanced functionality.

## Features

- **Video Conferencing:** Host and join video calls with ease.
- **Clerk Authentication:** Secure user authentication powered by Clerk.
- **Stream Integration:** Integration with Stream APIs for enhanced video streaming capabilities.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/dammy-key/D-ZOOM.git
    ```

2. **Install dependencies:**

    ```bash
    cd d-zoom
    npm install
    ```

3. **Configure environment variables:**

    Create a `.env.local` file in the root directory and add the following:

    ```makefile
    NEXT_PUBLIC_CLERK_FRONTEND_API_KEY=your-clerk-frontend-api-key
    NEXT_PUBLIC_STREAM_API_KEY=your-stream-api-key
    ```

    Replace `your-clerk-frontend-api-key` and `your-stream-api-key` with your actual API keys.

4. **Start the development server:**

    ```bash
    npm run dev
    ```

    Visit http://localhost:3000 in your browser to view the application.

## Demo

Check out the live demo of D-ZOOM at [DammyTech](https://D-ZOOM.netlify.app).

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

D-ZOOM is developed by DammyTech.
