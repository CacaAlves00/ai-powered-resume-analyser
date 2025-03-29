# AI-Powered Resume Analyzer

A platform that allows users to upload their resumes, and an AI (powered by the OpenAI API or TensorFlow.js) analyzes the resume and provides suggestions for improvement based on LinkedIn job postings.

## Features:
- ✅ Authentication with [NextAuth](https://next-auth.js.org/)
- ✅ PDF upload and parsing with [pdf.js](https://mozilla.github.io/pdf.js/)
- ✅ Integration with [OpenAI](https://openai.com/) for intelligent resume analysis
- ✅ Interactive UI built with [Tailwind CSS](https://tailwindcss.com/) and [Framer Motion](https://www.framer.com/motion/)

# AI-Powered Resume Analyzer - Setup Instructions

Follow the steps below to set up and run the AI-Powered Resume Analyzer application on your local machine.

## 1. Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/CacaAlves00/ai-powered-resume-analyser.git
cd ai-powered-resume-analyzer

## 2. Install Dependencies

Next, install the required dependencies for the project:

```bash
npm install


This will install all the necessary packages defined in `package.json`.

## 3. Set Up Environment Variables

You will need to set up environment variables for the project. Create a `.env.local` file in the root of the project and add the following variables:

```bash
NEXT_PUBLIC_OPENAI_API_KEY=your-openai-api-key NEXTAUTH_SECRET=your-nextauth-secret


- Replace `your-openai-api-key` with your actual OpenAI API key.
- Replace `your-nextauth-secret` with a secret string for NextAuth authentication. You can generate a random string for this value.

## 4. Run the Development Server

Once the environment variables are set, run the development server with the following command:

```bash
npm run dev


This will start the app at `http://localhost:3000`. Open your browser and visit the URL to see the application in action.

## 5. Usage

Once the app is running:

1. Sign in using your preferred authentication method.
2. Upload a resume (in PDF format).
3. Wait for the AI to analyze the resume.
4. Receive suggestions and recommendations to improve the resume based on LinkedIn job postings.

Enjoy using the AI-Powered Resume Analyzer!

