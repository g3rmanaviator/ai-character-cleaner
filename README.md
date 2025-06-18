# AI Text Character Detector

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

A web-based tool for detecting suspicious Unicode characters commonly found in AI-generated or manipulated text. This tool helps identify hidden characters, unusual formatting, and potential text manipulation techniques.

## ✨ Features

### 📁 **Multiple Input Methods**
- **File Upload**: Drag & drop or browse to upload `.txt` and `.docx` files
- **Direct Text Input**: Paste text directly into the built-in editor

### 🔍 **Comprehensive Character Detection**
- **Zero Width Characters**: Invisible characters like Zero Width Space, Non-Joiner, etc.
- **Directional Control**: Left-to-Right/Right-to-Left embedding and override characters
- **Unusual Spaces**: Non-breaking spaces, em/en spaces, ideographic spaces
- **Smart Punctuation**: Curly quotes, em/en dashes, ellipsis
- **Format Characters**: Soft hyphens, combining characters, language marks
- **Full-width Characters**: Full-width punctuation and symbols
- **Special Symbols**: Section signs, bullets, geometric shapes
- **Object Replacement**: Replacement and object placeholder characters

### 📊 **Analysis & Statistics**
- **Character Counts**: Precise count of each suspicious character type
- **Category Breakdown**: Organized display by character category
- **Percentage Analysis**: Shows suspicious characters as percentage of total text

### 🎯 **Interactive Character Filtering**
- **Sentence Context View**: Click any character to see full sentences where it appears
- **Character Hiding**: Hide specific characters from the display
- **Visual Indicators**: Active filters highlighted with yellow background and filter icons
- **Filter Status**: Clear indication of currently active filters
- **Easy Reset**: One-click filter reset functionality

### 📄 **Advanced Text Comparison**
- **Before/After View**: Side-by-side comparison of original vs. cleaned text
- **Syntax Highlighting**: Suspicious characters highlighted with tooltips
- **Format Preservation**: Maintains paragraph structure, line breaks, and tabs from DOCX files
- **Real-time Updates**: Instant visual feedback when applying filters

### 💾 **Export & Copy Options**
- **Copy to Clipboard**: Preserve formatting when copying text
- **TXT Download**: Download cleaned text with preserved formatting
- **Batch Export**: Export both original and cleaned versions
- **Format Retention**: Maintains document structure in exported files

### 🎨 **Modern User Interface**
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Intuitive Layout**: Clear sections for input, analysis, and results
- **Visual Feedback**: Notifications for all user actions
- **Accessibility**: Keyboard navigation and screen reader support

## 🚀 How It Works

### Step 1: Input Your Text
Choose your preferred input method:
- **Upload Files**: Drag and drop `.txt` or `.docx` files onto the upload area
- **Paste Text**: Use the text editor to paste content directly

### Step 2: Analyze
Click the **"🔍 Analyze Text"** button to start the detection process.

### Step 3: Review Results
The tool provides comprehensive analysis including:
- **Summary Statistics**: Total suspicious characters, categories, and risk level
- **Character Categories**: Detailed breakdown of found characters
- **Text Comparison**: Before/after views with highlighted suspicious characters

### Step 4: Interactive Filtering
Click on any detected character in the results to:
- **View Context**: See complete sentences containing the character
- **Hide Character**: Remove the character from the display
- **Reset View**: Return to the original analysis

### Step 5: Export
Use the export options to:
- **Copy**: Copy formatted text to clipboard
- **Download**: Save cleaned text as `.txt` file with preserved formatting


## 🎯 Why This Tool?

### The Problem
AI-generated text often contains subtle Unicode anomalies that are invisible to the human eye but can be detected programmatically. These include:
- Hidden zero-width characters inserted between words
- Unusual spacing and directional control characters
- Non-standard punctuation and formatting characters
- Object replacement characters from copy-paste operations

### The Solution
This tool provides a comprehensive analysis of text to identify these anomalies, helping users:
- **Verify Text Authenticity**: Detect potential AI-generated content
- **Clean Documents**: Remove suspicious characters while preserving formatting
- **Educational Purposes**: Learn about Unicode character manipulation techniques
- **Content Moderation**: Identify potentially manipulated text submissions

## 🏃‍♂️ How to Run Locally

1. **Download**: Clone or download this repository
2. **Open**: Simply open `roo-file.html` in any modern web browser
3. **Use**: No installation, server setup, or dependencies required!

## 🔧 Browser Compatibility

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Guidelines
- Follow existing code style and structure
- Test thoroughly across different browsers
- Update documentation for new features
- Ensure accessibility standards are maintained

## 📄 License

This project is licensed under the MIT License

## 🙏 Acknowledgments

- Unicode Consortium for comprehensive character documentation
- Community feedback and feature suggestions
- Open source libraries that make this tool possible

