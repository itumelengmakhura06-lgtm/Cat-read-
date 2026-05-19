# ✨ Copycat Magic English - Interactive Language Learning Game ✨

An interactive web-based English learning game for children that teaches reading, speaking, and spelling through a fun, gamified experience with voice recognition and reward stickers.

## 🎮 Game Features

### Three Learning Stages Per Word
1. **🔊 Listen** - Hear the word pronounced aloud
2. **🎤 Speak** - Record yourself saying the word using voice recognition
3. **✏️ Spell** - Type the correct letters to verify understanding

### Content Categories
- 🐾 **Animals** - Cat, Dog, Bird, Fish, Lion
- 🏠 **House** - Cup, Bed, Chair, Door, Lamp
- 🌱 **Nature** - Sun, Tree, Rain, Rose, Star

### Interactive Features
- 🖼️ **Visual Hints** - Picture hints to help children understand words
- ⭐ **Scoring System** - Earn 5 points per correct word
- 📖 **Sticker Book** - Collect stickers as rewards for completing levels
- 🎙️ **Voice Recognition** - Built-in speech-to-text using Web Speech API
- 🔊 **Text-to-Speech** - High-quality pronunciation guidance

## 📁 Project Structure

```
Cat-read-/
├── index.html                 # Main game file
├── README.md                  # This file
├── .gitkeep-images           # Images folder guide
└── images/                   # Image assets folder
    ├── cat.png               # Word hint images
    ├── dog.png
    ├── bird.png
    ├── fish.png
    ├── lion.png
    ├── cup.png
    ├── bed.png
    ├── chair.png
    ├── door.png
    ├── lamp.png
    ├── sun.png
    ├── tree.png
    ├── rain.png
    ├── rose.png
    ├── star.png
    ├── animals-sticker.png   # Reward stickers
    ├── house-sticker.png
    └── nature-sticker.png
```

## 🚀 Getting Started

### Setup Instructions

1. **Clone or download this repository**
   ```bash
   git clone https://github.com/itumelengmakhura06-lgtm/Cat-read-.git
   cd Cat-read-
   ```

2. **Create the images folder**
   ```bash
   mkdir images
   ```

3. **Add image assets** (See Image Requirements below)

4. **Open in browser**
   - Simply open `index.html` in any modern web browser
   - No installation or build process required

### Image Requirements

#### Word Hint Images (15 total)
- **Size**: 300×300px recommended
- **Format**: PNG or JPG
- **Naming**: lowercase, exact match to word names
- **Location**: `images/` folder

**Required images:**
- animals: `cat.png`, `dog.png`, `bird.png`, `fish.png`, `lion.png`
- house: `cup.png`, `bed.png`, `chair.png`, `door.png`, `lamp.png`
- nature: `sun.png`, `tree.png`, `rain.png`, `rose.png`, `star.png`

#### Sticker Reward Images (3 total)
- **Size**: 200×200px recommended
- **Format**: PNG (transparent background recommended)
- **Location**: `images/` folder

**Required images:**
- `animals-sticker.png`
- `house-sticker.png`
- `nature-sticker.png`

## 🌐 Browser Compatibility

| Browser | Support | Notes |
|---------|---------|-------|
| Chrome | ✅ Full | Recommended - best speech recognition |
| Firefox | ✅ Full | Good support |
| Safari | ✅ Full | Voice recognition may require permissions |
| Edge | ✅ Full | Excellent support |
| Mobile Safari | ⚠️ Limited | Voice recognition may not work on all iOS versions |

## 🎯 How to Play

1. **Select a Level** - Choose Animals, House, or Nature
2. **Listen** - Click "Hear Word" to hear the word pronounced
3. **Speak** - Click "Start Speaking" and repeat what you hear
4. **Spell** - Type the letters you see in the spelling stage
5. **Earn Points** - Get 5 points for each correct answer
6. **Win Stickers** - Complete a category to earn a collectible sticker
7. **Check Progress** - Open "My Sticker Book" anytime to see earned rewards

## 💾 Data Storage

The game uses **LocalStorage** to save progress:
- Completed categories are stored locally on the device
- Sticker progress persists between sessions
- No internet connection required after initial load

## 🔊 Voice Recognition Features

- **Speech Recognition**: Uses Web Speech API to understand spoken words
- **Text-to-Speech**: High-quality voice synthesis for pronunciation guidance
- **Patient Listening**: Gives children time to speak without rushing

## 🎨 Customization

### Change Word Lists
Edit the `categories` object in the `<script>` section of `index.html`:

```javascript
const categories = {
    animals: [
        { word: "CAT", sentence: "I see a cat" },
        { word: "DOG", sentence: "The dog can run" },
        // Add more words...
    ],
    // Add or modify categories...
};
```

### Modify Colors
Update CSS variables in the `<style>` section:
- Background color: `#FFDE4D` (yellow)
- Accent color: `#FFB200` (orange)
- Text color: `#333` (dark gray)

## 🚀 Future Enhancement Ideas

1. **More Categories** - Add categories like Food, Colors, Family, School
2. **Difficulty Levels** - Easy, Medium, Hard with different word complexity
3. **Leaderboard** - Track high scores and progress over time
4. **Sound Effects** - Add celebration sounds and background music
5. **Language Support** - Add Spanish, French, or other languages
6. **Progress Analytics** - Track which words are hardest for learners
7. **Export/Share Progress** - Allow parents to see learning progress
8. **Adaptive Learning** - Repeat words that need more practice

## 🐛 Troubleshooting

### Voice Recognition Not Working
- Ensure you're using a modern browser (Chrome, Firefox, Safari, or Edge)
- Check microphone permissions are enabled
- Try refreshing the page
- On mobile, ensure your device has a working microphone

### Images Not Loading
- Verify image filenames match exactly (lowercase, with .png extension)
- Check that the `images/` folder exists in the same directory as `index.html`
- Ensure image formats are PNG or JPG
- Try opening browser console (F12) to check for 404 errors

### Sticker Book Not Saving
- Check that browser allows LocalStorage
- Clear browser cache and try again
- Disable private/incognito browsing mode

## 📝 License

This project is open source and free to use for educational purposes.

## 👨‍💻 Author

Created by: itumelengmakhura06-lgtm

## 📧 Support

For issues or suggestions, please open an issue on GitHub.

---

**Happy Learning! 🌟**
