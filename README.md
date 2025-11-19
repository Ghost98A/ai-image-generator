# 🎨 AI Image Generator & Editor

A beautiful web application that lets you generate new images from text descriptions or modify existing images using AI models powered by [Subscribe.dev](https://subscribe.dev).

![AI Image Generator & Editor](https://img.shields.io/badge/AI-Image%20Generator-blueviolet) ![Subscribe.dev](https://img.shields.io/badge/Powered%20by-Subscribe.dev-blue)

## ✨ Features

### 🚀 Generate New Images
- Create stunning images from text descriptions
- Choose from multiple AI models:
  - **FLUX Schnell** - Fast, high-quality image generation
  - **Nano Banana** - Multi-image capabilities
- Select aspect ratios: Square, Landscape, Portrait, and more
- Get results in 10-30 seconds

### ✏️ Edit Existing Images
- Upload any image and transform it with AI
- Modify colors, add effects, change scenes
- Two powerful editing models:
  - **FLUX Kontext Max** - Advanced image editing
  - **Nano Banana** - Multi-image fusion and blending

## 🌐 Live Demo

**Deployed App:** https://583522d8b5574fa1a3412f5f1e000bd3.apps.subscribe.dev

## 🚀 Quick Start

### Option 1: Open Directly
Simply open `index.html` in your web browser - no build process required!

### Option 2: Local Server
```bash
# Using Python
python3 -m http.server 8080

# Using Node.js
npx http-server -p 8080
```

Then visit: `http://localhost:8080`

## 🎯 How to Use

### Generate Images
1. Click the **"Generate"** tab
2. Enter a description of the image you want (e.g., "A majestic fire dragon on a mountain peak at sunset")
3. Select your preferred AI model and aspect ratio
4. Click **"🚀 Generate Image"**
5. Wait 10-30 seconds for your image to appear!

### Edit Images
1. Click the **"Edit"** tab
2. Upload an image from your device
3. Describe the changes you want (e.g., "Make the dragon blue instead of red, add lightning effects")
4. Select your editing model
5. Click **"✨ Modify Image"**
6. Your edited image will appear in seconds!

## 🔧 Technology

- **Frontend:** Pure HTML, CSS, and JavaScript (no framework needed!)
- **AI Backend:** [Subscribe.dev](https://subscribe.dev) API
- **AI Models:**
  - FLUX Schnell (Black Forest Labs)
  - FLUX Kontext Max (Black Forest Labs)
  - Nano Banana (Google)

## 📦 Project Structure

```
ai-image-generator/
├── index.html          # Main application file (all-in-one)
├── README.md          # This file
└── .gitignore         # Git ignore rules
```

## 🎨 Customization

The app is built as a single HTML file with embedded CSS and JavaScript. You can easily customize:

- **Colors:** Modify the CSS gradient and color schemes
- **AI Models:** Add more models from Subscribe.dev
- **Aspect Ratios:** Add custom aspect ratio options
- **UI Layout:** Adjust the grid layout for different screen sizes

## 🔑 API Key

The app comes pre-configured with a demo Subscribe.dev API key. For production use or higher limits:

1. Sign up at [Subscribe.dev](https://subscribe.dev)
2. Create a new project
3. Replace the `API_KEY` in the `<script>` section of `index.html`

## 📝 Example Prompts

### For Generation:
- "A majestic fire dragon perched on a mountain peak at sunset, with flames emanating from its body, dramatic lighting, digital art style"
- "A futuristic cityscape at night with neon lights reflecting on wet streets, cyberpunk style"
- "A serene Japanese garden with cherry blossoms, koi pond, and traditional architecture, watercolor painting style"

### For Editing:
- "Make the dragon blue instead of red, add lightning effects"
- "Change the background to a starry night sky"
- "Add magical glowing particles around the subject"

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

MIT License - feel free to use this project for personal or commercial purposes!

## 🙏 Acknowledgments

- Powered by [Subscribe.dev](https://subscribe.dev)
- AI Models by Black Forest Labs and Google
- Built with ❤️ using modern web technologies

## 📞 Support

If you encounter any issues or have questions:
1. Check the [Subscribe.dev documentation](https://docs.subscribe.dev)
2. Open an issue on GitHub
3. Contact support@subscribe.dev

---

**Enjoy creating amazing AI-generated images!** 🎨✨
