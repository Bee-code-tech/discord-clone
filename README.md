
# Discord Clone using Next.js, Tailwind CSS, and Stream SDKs

### Developed by Al-Ameen Babawale

This project is a clone of the popular Discord application, built using [Next.js](https://nextjs.org), [TailwindCSS](https://tailwindcss.com), and the Stream [Chat](https://getstream.io/chat/docs/) and [Video](https://getstream.io/video/docs/) SDKs. This clone replicates the core UI/UX elements of Discord, while integrating real-time chat and video functionalities.

This project is based on a series of blog posts originally published by Stream, but has been honed and adapted for educational purposes.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Tech Stack](#tech-stack)
- [Running the Project](#running-the-project)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview

This project serves as a practice and demonstration of modern web development technologies including React, Next.js, and Tailwind CSS, paired with Stream’s powerful SDKs for chat and video integration. Over the course of development, the project has evolved into a functional, scalable, and highly interactive chat application.

---

## Features

- **Real-time messaging** powered by Stream’s Chat SDK.
- **Audio and video calls** using Stream’s Video SDK.
- **Responsive layout** using Tailwind CSS.
- **Channel and server navigation** inspired by Discord’s UI.
- **Next.js optimization** for improved performance and SEO.

---

## Getting Started

### Prerequisites

To get started with the project, ensure you have the following installed:

- [Node.js](https://nodejs.org/en/)
- [Git](https://git-scm.com/)
- [Yarn](https://classic.yarnpkg.com/en/docs/install) or NPM
- A [Stream account](https://getstream.io/try-for-free/) for API keys.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/bee-code-tech/discord-clone.git
   cd discord-clone-nextjs
   ```

2. **Install dependencies:**

   Using Yarn:

   ```bash
   yarn
   ```

   Or using NPM:

   ```bash
   npm install
   ```

3. **Create a `.env` file:**

   Inside the root directory, create a `.env` file and add your Stream API keys:

   ```bash
   NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
   NEXT_PUBLIC_STREAM_SECRET=your_stream_api_secret
   ```

4. **Run the development server:**

   Using Yarn:

   ```bash
   yarn dev
   ```

   Or using NPM:

   ```bash
   npm run dev
   ```

   The app will be available at `http://localhost:3000`.

---

## Tech Stack

- **Framework:** [Next.js](https://nextjs.org)
- **Styling:** [Tailwind CSS](https://tailwindcss.com)
- **Real-time Chat:** [Stream Chat SDK](https://getstream.io/chat/sdk/react/)
- **Video and Audio:** [Stream Video SDK](https://getstream.io/video/docs/react/)
- **State Management:** React's built-in Context API
- **Deployment:** [Vercel](https://vercel.com)

---

## Running the Project

To run the project locally, follow these steps:

1. Install dependencies by running:

   ```bash
   npm install
   # or
   yarn
   ```

2. Run the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

This will start the app on `localhost:3000`. You can begin testing and customizing the project as you see fit.

### Production Build

For a production build, you can run the following commands:

```bash
npm run build
npm start
```

This will generate an optimized build of your application.

---

## Contributing

Contributions to this project are welcome! If you would like to improve any aspect of the app or add new features, feel free to fork the repository and submit a pull request.

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

