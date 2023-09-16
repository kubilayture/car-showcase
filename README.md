# Car Rental Website

This project is a simple car rental website developed using Next.js 13.4. The purpose of this project is to display vehicle rental options to users and encourage them to explore potential vehicles. This site only contains the front end and does not provide any user login or backend functionality.

## Features

- View the list of vehicles
- View details of vehicles
- User-friendly and responsive design

## Getting Started

To run the project in a local development environment, you can follow the steps below.

1. Clone the repository:

   ```bash
   git clone https://github.com/kubilayture/car-showcase.git
   ```

2. **Navigate to the Project Directory**: Once the cloning process is complete, navigate to the project directory using the following command:

   ```bash
   cd car-showcase
   ```

3. **Install Dependencies**: To install the necessary dependencies for the app, run the following command:

   ```bash
   npm install
   ```

   Before proceeding to the next step, please make sure to create a imagin studio key for the Article Extractor and Summarizer API on RapidAPI's website. Once you have the key, you'll need to save it as an environment variable in a `.env.local` file in the project root directory.

   ```plaintext
   NEXT_PUBLIC_IMAGIN_API_KEY=your-imagin-key-here
   ```

4. **Run the App**: After successfully installing the dependencies, you can run the AI Summarizer locally using the following command:

   ```bash
   npm run dev
   ```

## Features

- **Search:** Users can search for vehicles by entering the make and model in the search bar.

- **Filter:** Users can filter the search results by year and fuel type.