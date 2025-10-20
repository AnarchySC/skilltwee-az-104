# 🎮 IRL Skill Trees - Gamified Learning Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Transform your learning journey into an RPG-style adventure! Level up real-world skills with interactive skill trees, quests, and progress tracking.

![Skill Tree Demo](https://img.shields.io/badge/Demo-Live-green)

## 🌟 Features

- **🎯 Interactive Skill Trees** - Visual progression paths with unlockable tiers
- **📋 Quest System** - Hands-on tasks and challenges for each skill
- **💾 Progress Tracking** - Local storage saves your progress automatically
- **🏆 XP & Achievements** - Earn points and unlock new skill tiers
- **📚 Curated Resources** - Links to free learning materials for each skill
- **📱 Responsive Design** - Works on desktop, tablet, and mobile
- **🌙 Dark Mode** - Easy on the eyes for those late-night learning sessions
- **🚀 Zero Dependencies** - Pure HTML/CSS/JS, no frameworks needed

## 🎓 Available Skill Trees

### 1. **Python Developer Path** (`skilltwee-core.html`)
Complete Python learning journey from variables to web frameworks
- **30 Skills** across 6 domains
- Foundation → Core → Advanced → Professional
- Hands-on projects and exercises

### 2. **Python Interactive Lessons** (`skilltwee-foundations.html`)
Step-by-step interactive Python tutorials with live code execution
- Built-in Python interpreter (Skulpt)
- Real-time code validation
- Guided projects

### 3. **AZ-104 Azure Administrator** (`index.html`)
Microsoft Azure certification preparation
- **30 Skills** aligned with exam objectives
- Covers all 5 exam domains
- Practice labs and exam tips

### 4. **AZ-140 Azure Virtual Desktop** (Coming Soon)
AVD specialist certification prep
- **25 Skills** covering AVD architecture
- Real-world scenarios

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from branch" → main → /root
4. Access at: `https://[your-username].github.io/skill-trees/`

### Option 2: Local Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/skill-trees.git

# Navigate to the folder
cd skill-trees

# Open any skill tree in your browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### Option 3: Direct Use
Simply download and open any HTML file in your browser - no server required!

## 🎮 How to Use

1. **Choose Your Path** - Open the skill tree for the topic you want to learn
2. **Start with Tier 1** - Foundation skills are unlocked by default
3. **Click Skills** - View quests, resources, and track progress
4. **Complete Quests** - Check off completed tasks
5. **Master Skills** - Complete all quests to master a skill
6. **Unlock New Tiers** - Master 80% of a tier to unlock the next level
7. **Track Progress** - Watch your completion percentage grow!

## 🛠️ Technical Details

### Structure
```
skill-trees/
├── index.html              # AZ-104 Azure Admin skill tree
├── skilltwee-core.html     # Python developer skill tree
├── skilltwee-foundations.html # Interactive Python lessons
├── README.md               # This file
├── LICENSE                 # MIT License
└── CONTRIBUTING.md         # Contribution guidelines
```

### Technologies
- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Storage**: localStorage for progress persistence
- **Python Interpreter**: Skulpt.js (for interactive lessons)
- **Design**: CSS Grid, Flexbox, CSS animations
- **No Backend Required** - Fully client-side application

### Browser Support
- Chrome 90+ ✅
- Firefox 88+ ✅
- Safari 14+ ✅
- Edge 90+ ✅
- Mobile browsers ✅

## 🎨 Customization

### Creating Your Own Skill Tree

1. Copy any existing HTML file as a template
2. Modify the `skillQuests` object with your content:

```javascript
const skillQuests = {
    'skill-id': {
        icon: '🎯',
        quests: {
            'Category': [
                'Task 1',
                'Task 2'
            ]
        },
        resources: [
            { name: 'Resource Name', url: 'https://...' }
        ]
    }
};
```

3. Update the skill grid HTML:
```html
<div class="skill" data-tier="1" data-skill="skill-id">
    <div class="skill-icon">🎯</div>
    <div class="skill-name">Skill Name</div>
    <div class="skill-desc">Description</div>
</div>
```

### Styling
Modify CSS variables for custom themes:
```css
/* Change gradient colors */
background: linear-gradient(135deg, #yourcolor1 0%, #yourcolor2 100%);
```

🤝 Contributing
We welcome contributions! Please see CONTRIBUTING.md for guidelines.
Ways to Contribute

🌳 Add new skill trees
🐛 Report bugs
✨ Suggest features
📚 Add learning resources
🌍 Add translations
📝 Improve documentation

📈 Roadmap

 Backend integration for cloud saves
 User accounts and social features
 More certification paths (AWS, GCP, etc.)
 Programming languages (JavaScript, Java, C++)
 Soft skills trees (Leadership, Communication)
 Mobile app (React Native)
 Multiplayer challenges
 API for third-party integration

🙏 Acknowledgments

Inspired by video game skill trees and RPG progression systems
Python curriculum based on community best practices
Azure content aligned with Microsoft Learn
Built with ❤️ for the self-learning community
