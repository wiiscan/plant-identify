# Plant Identifier App

This is a plant identifier app that uses Google's Gemini API to identify plants. Built with Next.js and Tailwind CSS.

## Features

- Identify plants using Google's Gemini API
- Identify plants via image upload
- Identify plants using the camera

## Technologies

- Next.js
- Tailwind CSS
- Google's Gemini API

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/plant-identifier.git
cd plant-identifier
```

2. Install dependencies
```bash
pnpm install
```

3. Configure environment variables
Create a `.env.local` file in the root directory:
```bash
cp .env.local.example .env.local
```
Update the `.env.local` file with your API keys.

4. Start the development server
```bash
pnpm run dev
```

## Environment Variables

Ensure you have the following in your `.env.local`:
```plaintext
OPENAI_API_KEY=your_openai_api_key  
GOOGLE_APPLICATION_CREDENTIALS=/absolute/path/to/service-account.json  
NEXT_PUBLIC_GOOGLE_API_KEY=your_google_api_key  
GEMINI_API_URL=https://gemini-api-url.com/v1/identify  
```

## Contributing

Pull requests are welcome. Open an issue first to discuss major changes.

## License

[MIT](LICENSE)