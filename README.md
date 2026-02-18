# LM Studio Chat Web Interface

A modern, feature-rich web-based chat interface for LM Studio's local AI model server, built with vanilla JavaScript and designed for seamless local AI interactions.

## 🚀 Features

### Core Functionality
- **Real-time Chat**: Stream responses from LM Studio's local AI models
- **Image Support**: Upload and analyze images with multimodal models
- **Model Selection**: Choose from available local models
- **Server Connection**: Connect to LM Studio's local server via WebSocket

### Enhanced User Experience
- **State Persistence**: Automatic save/load of chats, prompts, and settings via localStorage
- **Library of Prompts**: Save frequently used prompts for quick access
- **Click-to-Insert**: One-click insertion of saved prompts into chat
- **20 Color Themes**: Extensive theme selection for personalized UI experience
- **Responsive Design**: Works seamlessly on desktop and mobile devices

### Advanced Features
- **Markdown Support**: Rich text formatting with code highlighting
- **LaTeX Math**: Mathematical expressions rendering with MathJax
- **Copy Code**: One-click copying of code blocks from responses
- **Chat Management**: Create, rename, and delete conversations
- **Context Preservation**: Maintains conversation history for coherent responses

## 🎨 Available Themes

Choose from 20 carefully designed color schemes:

**Classic Themes:**
- Default (Purple) - Original purple theme
- Dark (Classic) - Professional dark theme
- Light (Clean) - Bright, clean interface

**Colorful Themes:**
- Blue Ocean - Deep blue gradient
- Forest - Green nature-inspired
- Ruby - Rich red accents
- Sunset - Warm orange tones
- Teal - Cyan/blue combination
- Indigo - Deep indigo theme
- Pink - Purple/pink combination
- Cyan - Bright cyan accents
- Amber - Golden yellow theme

**Material Design:**
- Deep Purple - Dark purple material
- Deep Orange - Dark orange material
- Lime - Bright green material
- Brown - Earthy brown tones
- Grey - Monochrome grey
- Blue Grey - Blue-grey combination
- Material - Standard material design

**Special Themes:**
- Neon - Cyberpunk neon colors

## 🛠️ Technical Specifications

### Built With
- **Vanilla JavaScript** - No frameworks, lightweight and fast
- **CSS Grid/Flexbox** - Modern responsive layouts
- **Fetch API** - Modern HTTP requests with streaming support
- **LocalStorage API** - Client-side data persistence
- **File API** - Image upload and preview functionality

### Dependencies
- **Marked.js** - Markdown rendering
- **Highlight.js** - Code syntax highlighting
- **MathJax** - LaTeX mathematical expressions
- **Font Awesome** - Icon library
- **Google Fonts** - Inter font family

### Browser Support
- Modern browsers with ES6+ support
- Chrome, Firefox, Safari, Edge
- Mobile browsers supported

## 📦 Installation

### Quick Start
1. Download the `index.html` file
2. Open it in any modern web browser
3. Connect to your LM Studio server

### Server Requirements
- LM Studio running locally
- Server API enabled
- Models loaded and available

## 🔧 Configuration

### Server Connection
1. Enter your LM Studio server address in the header
2. Click "Connect" to establish connection
3. Select your preferred model from the dropdown

### Theme Customization
1. Use the theme selector in the sidebar
2. Choose from 20 available themes
3. Theme automatically saves and loads on subsequent visits

### Prompt Library
1. Click "Add Prompt" to save frequently used prompts
2. Click any saved prompt to insert into chat
3. Edit or delete prompts using hover actions

## 📱 Usage

### Starting a Conversation
1. Ensure LM Studio server is running
2. Connect to the server via the interface
3. Select your desired model
4. Start typing your message

### Image Analysis
1. Click the image upload button
2. Select an image file
3. Type your question about the image
4. Receive AI analysis of the visual content

### Managing Chats
1. Create new chats via the "New Chat" button
2. Switch between chats using the sidebar
3. Right-click chats to delete (context menu)
4. Chat history automatically saves

### Using the Prompt Library
1. Add prompts via the "Add Prompt" button
2. Browse saved prompts in the library section
3. Click any prompt to insert into the input field
4. Edit prompts using the edit button

## 🎯 Key Features Deep Dive

### State Persistence
The interface automatically saves:
- **Chat conversations** with full message history
- **Prompt library** with all saved prompts
- **Server settings** including URL and selected model
- **Theme preferences** for consistent experience
- **Connection status** for quick reconnection

### Theme System
- **CSS-in-JS Implementation**: Dynamic theme switching without page reload
- **20 Pre-designed Themes**: Each with carefully selected color palettes
- **Smooth Transitions**: CSS transitions for pleasant theme changes
- **Accessibility Focused**: All themes maintain good contrast ratios
- **Complete Coverage**: Every UI element respects theme colors

### Image Processing
- **Client-side Processing**: Images processed locally for privacy
- **Base64 Encoding**: Efficient image data handling
- **Preview Functionality**: Visual confirmation before sending
- **Multimodal Support**: Works with vision-capable models

### Code and Math Support
- **Syntax Highlighting**: Automatic code block highlighting
- **Copy Functionality**: One-click copying of code examples
- **Mathematical Expressions**: LaTeX rendering for complex equations
- **Markdown Rendering**: Rich text formatting support

## 🔍 Architecture

### File Structure
```
index.html          # Complete standalone application
├── HTML Structure  # Semantic markup with ARIA labels
├── CSS Styles      # Modern CSS with custom properties
└── JavaScript      # Vanilla JS with modular functions
```

### Code Organization
- **Global Variables**: Centralized state management
- **Storage Functions**: localStorage interaction utilities
- **UI Functions**: DOM manipulation and rendering
- **Event Handlers**: User interaction management
- **API Functions**: Server communication logic

### Design Patterns
- **Modular Functions**: Clean, single-responsibility functions
- **Event-Driven**: Responsive user interactions
- **Progressive Enhancement**: Works without JavaScript (basic HTML)
- **Accessibility**: Semantic HTML and keyboard navigation

## 🤝 Contributing

### Development Setup
1. Fork the repository
2. Make your changes
3. Test thoroughly across browsers
4. Submit a pull request

### Code Style
- Use semantic HTML
- Follow CSS naming conventions
- Maintain JavaScript readability
- Ensure cross-browser compatibility

### Feature Requests
Submit issues with:
- Clear feature description
- Use case explanation
- Mockups if applicable
- Priority indication

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- **LM Studio** for the excellent local AI server
- **Marked.js** team for markdown parsing
- **Highlight.js** team for syntax highlighting
- **MathJax** team for mathematical rendering
- **Font Awesome** for iconography

## 🔄 Changelog

### Version 1.0.0
- Initial release with core chat functionality
- State persistence implementation
- 20 theme color system
- Prompt library with CRUD operations
- Image upload and analysis support
- Responsive design improvements
- Accessibility enhancements

---<img width="1882" height="905" alt="2026-02-18_20-34-27" src="https://github.com/user-attachments/assets/fac2a470-2f90-43e5-a60b-22b51d4bc6e7" />



**Note**: This is a standalone HTML application that requires no build process or server setup. Simply download and open in any modern browser to use with your LM Studio server.
