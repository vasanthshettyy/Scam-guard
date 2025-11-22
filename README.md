# ScamGuard - AI-Powered Investment Pitch Analyzer

ScamGuard is a web application that helps investors analyze investment pitches for potential scams or red flags using AI. The tool can process both text and image inputs, making it easy to evaluate investment opportunities from various sources.

## Features

- **Text Analysis**: Paste investment pitch text for instant analysis
- **Image Analysis**: Upload images of investment pitches (screenshots, documents, etc.)
- **Risk Assessment**: Get a risk score and detailed analysis of potential red flags
- **Real-time Feedback**: Immediate insights into investment opportunities
- **User-friendly Interface**: Clean, modern UI with intuitive controls

## Tech Stack

- **Frontend**: React, Vite, TailwindCSS
- **AI/ML**: Tesseract.js (OCR for image processing)
- **Animations**: GSAP for smooth UI transitions
- **Development**: Vite for fast development and building

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v7 or higher) or Yarn

### Installation

1. Clone the repository:
   ```bash
   git clone [your-repository-url]
   cd scamguard-app
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

### Running the Application

1. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

2. Open your browser and navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
# or
yarn build
```

## Usage

1. **Text Analysis**:
   - Go to the "Text" tab
   - Paste your investment pitch text
   - Click "Analyze Text"

2. **Image Analysis**:
   - Go to the "Image" tab
   - Upload an image containing investment pitch text
   - Click "Analyze Image"

3. **Review Results**:
   - View the risk score
   - Check for detected red flags
   - Read the detailed analysis


## Acknowledgments

- Built with ❤️ using modern web technologies
- Special thanks to the open-source community for the amazing tools and libraries
