# LLM Agent POC - Modern Chat Interface

A modern, responsive chat interface for LLM (Large Language Model) interactions with a sleek dark theme design.

## Features

- 🎨 Modern dark theme with vibrant gradients
- 💬 Clean chat interface with distinct user/assistant messages
- 🔧 Multiple LLM provider support:
  - OpenAI
  - AI Pipe (OpenRouter-style)
  - Anthropic Claude
  - Google Gemini
- 🔍 Integrated web search capabilities
- 💻 Code execution support
- 📱 Responsive design for all devices

## Tech Stack

- Frontend:
  - HTML5
  - CSS3 (Modern styling with gradients and animations)
  - JavaScript
  - Bootstrap 5.3.3
  - Bootstrap Icons

## Setup

1. Clone the repository
2. Configure your API keys in the interface:
   - LLM Provider API key
   - (Optional) Google Search API key and CSE CX for web search

## Project Structure

```
├── app.py              # Main application logic
├── index.html          # Frontend interface
├── style.css           # Modern dark theme styling
└── vercel.json         # Vercel deployment configuration
```

## Deployment

This project is configured for deployment on Vercel. The `vercel.json` configuration handles:
- Python backend routing
- API endpoints
- Static file serving

## Features in Detail

### Chat Interface
- Modern dark theme with vibrant gradients
- Clear message labeling for user and assistant
- Animated message transitions
- Code block support with syntax highlighting

### User Experience
- Real-time response streaming
- Clear visual feedback for system status
- Intuitive input interface
- Mobile-responsive design

### API Integration
- Multiple LLM provider support
- Web search capabilities
- Code execution environment

## Development

To run the project locally:

1. Set up your environment variables
2. Install the required dependencies
3. Run the Python application
4. Open `index.html` in your browser

## License

This project is licensed under the MIT License - see the LICENSE file for details.
