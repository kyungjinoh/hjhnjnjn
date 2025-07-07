# Allergy Detector App

A React-based web application for detecting and tracking food allergies using AI-powered analysis.

## Features

- **AI-Powered Allergy Analysis**: Uses Groq API for intelligent ingredient analysis
- **User Authentication**: Firebase-based user management
- **Allergy Logging**: Track reactions and symptoms
- **Dashboard**: Comprehensive allergy management interface
- **Discord Integration**: Community support through Discord server

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/kyungjinoh/hjhnjnjn.git
cd hjhnjnjn
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory and add your Groq API key:

```env
REACT_APP_GROQ_API_KEY=your_groq_api_key_here
```

**Important**: Replace `your_groq_api_key_here` with your actual Groq API key.

### 4. Start the Development Server
```bash
npm start
```

The application will be available at `http://localhost:3000`

## API Key Configuration

This application requires a Groq API key for AI-powered allergy analysis. To get your API key:

1. Visit [Groq Console](https://console.groq.com/)
2. Sign up or log in to your account
3. Generate a new API key
4. Add the key to your `.env` file as shown above

## Discord Community

Join our Discord server for support and community discussions:
[Discord Server](https://discord.gg/cmaaNdfz7C)

## Technologies Used

- React
- TypeScript
- Firebase (Authentication & Firestore)
- Groq API (AI Analysis)
- Lucide React (Icons)
- React Router DOM

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License.
