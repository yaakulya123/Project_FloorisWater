# 🌊 Floor_IS_Water - Board-Meets-Digital Hybrid Game

A future where rising oceans push megacities into collapse. Watch as a beautiful 3D isometric city slowly gets consumed by the tide in this mesmerizing digital board game prototype.

![Game Preview](https://img.shields.io/badge/Status-Playable%20Prototype-brightgreen) ![Platform](https://img.shields.io/badge/Platform-Web%20Browser-blue) ![Tech](https://img.shields.io/badge/Tech-HTML%2FCSS%2FJS-orange)

## 🎮 Game Overview

**Tide of Ashes** is a hybrid board-digital game where players must witness the inexorable rise of the ocean as it floods a detailed metropolitan city. The game combines the tactile feel of board games with the dynamic visual effects only possible in digital format.

### 🎯 Core Concept
- **Setting**: A post-climate-change world where megacities face rising sea levels
- **Mechanics**: Watch water spread from all four corners, consuming the city piece by piece
- **Tension**: Cooperative + competitive elements (future expansion)
- **Visual Style**: Beautiful 3D isometric city with realistic lighting and details

## 🏙️ City Features

### Building Types
The 30x30 grid city contains multiple building types with different heights and visual styles:

#### 🟡 **Low Buildings (Suburbs)**
- **Height**: 25px
- **Color**: Orange gradient
- **Features**: 4 window dots, floor divisions
- **Location**: Outer city rings
- **Details**: Residential areas with basic window patterns

#### 🟢 **Medium Buildings (Mid-City)**
- **Height**: 35px
- **Color**: Green gradient
- **Features**: 6 window dots, detailed floor markings
- **Location**: Mid-distance from center
- **Details**: Mixed-use buildings with enhanced lighting

#### 🔴 **Tall Buildings (Downtown)**
- **Height**: 50px
- **Color**: Red gradient
- **Features**: 8 window dots, professional lighting
- **Location**: Near city center
- **Details**: Corporate towers with sophisticated window patterns

#### 🟣 **Special Buildings (Landmarks)**
- **Height**: 60px
- **Color**: Purple gradient with glow effect
- **Features**: Central beacon light, 4 corner windows, pulsing animation
- **Location**: City center only
- **Details**: Iconic landmarks that pulse with energy

#### 🛣️ **Roads**
- **Height**: 5px (sunken)
- **Color**: Dark gray with white markings
- **Features**: Center lane dividers, dashed side lines
- **Pattern**: Grid layout every 6 tiles
- **Details**: Realistic road markings and texture

#### 🌳 **Parks**
- **Height**: 15px
- **Color**: Natural green with tree clusters
- **Features**: Circular tree patterns in various sizes
- **Location**: Randomly scattered in outer areas (15% chance)
- **Details**: Represents green spaces and urban forests

#### 🌫️ **Base Land**
- **Height**: 20px
- **Color**: Gray concrete texture
- **Features**: Subtle surface texture
- **Location**: Undeveloped city areas
- **Details**: Empty lots and construction zones

## 🌊 Water Mechanics

### Flooding Pattern
1. **Initial Flood**: Water simultaneously appears in all four corners of the city
2. **Spread Pattern**: Water randomly spreads to adjacent non-water tiles
3. **Speed Control**: Adjustable timing (100ms - 2000ms+ intervals)
4. **Visual Effect**: Smooth drowning animation when tiles convert to water

### Water Properties
- **Color**: Beautiful blue gradient with shimmer animation
- **Height**: Same as the tile it replaces
- **Animation**: Continuous water shimmer effect
- **Transition**: 1-second drowning animation before conversion

## 🎮 Controls & Interface

### Mouse Controls
- **Click & Drag**: Rotate the 3D city view
- **Rotation Range**: X-axis: 10° to 80° (prevents flipping)
- **Smooth Movement**: Real-time rotation with momentum
- **Touch Support**: Full mobile/tablet compatibility

### Control Panel (Top Left)
- **Start Water Spread**: Begin the flooding simulation
- **Pause**: Stop water spread temporarily
- **Reset Board**: Restore city to original state
- **Speed Up**: Decrease interval by 200ms (faster flooding)
- **Slow Down**: Increase interval by 200ms (slower flooding)

### Status Panel (Top Right)
- **Land Tiles**: Count of remaining non-water tiles
- **Water Tiles**: Count of flooded tiles
- **Speed**: Current flooding interval in milliseconds

## 🎨 Visual Features

### 3D Isometric Design
- **Perspective**: 60° X-rotation, -30° Y-rotation (default)
- **Grid Size**: 30x30 tiles (900 total)
- **Tile Size**: 20x20 pixels
- **Depth**: Variable heights create dramatic cityscape

### Lighting & Effects
- **Gradient Backgrounds**: Each building type has unique lighting
- **Window Patterns**: Radial gradients simulate lit windows
- **Shadow System**: Realistic drop shadows based on building height
- **Shimmer Animation**: Water tiles have flowing light effects
- **Glow Effects**: Special buildings pulse with energy

### Building Details
- **Window Grids**: Different patterns for each building type
- **Floor Divisions**: Repeating lines simulate building floors
- **Surface Texture**: Subtle patterns on all surfaces
- **Realistic Materials**: Each building type has appropriate textures

## 🔧 Technical Specifications

### Technology Stack
- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **3D Rendering**: CSS3 Transforms with `transform-style: preserve-3d`
- **Animations**: CSS animations and transitions
- **Responsive**: Works on desktop, tablet, and mobile

### Performance
- **Grid Size**: 30x30 = 900 tiles
- **DOM Elements**: ~5,400 elements (6 faces per tile)
- **Optimization**: Efficient CSS transforms and minimal reflows
- **Browser Support**: Modern browsers with CSS3 3D support

### File Structure
```
FloorIsWater/
├── index.html          # Main game file
└── README.md          # This documentation
```

## 🚀 How to Play

### Getting Started
1. **Open the Game**: Open `index.html` in any modern web browser
2. **Explore the City**: Click and drag to rotate the view and explore the detailed city
3. **Start Flooding**: Click "Start Water Spread" to begin the simulation
4. **Watch & Control**: Use speed controls to adjust the flooding pace
5. **Reset & Replay**: Reset the board to watch different flooding patterns

### Gameplay Loop
1. **City Generation**: Each reset creates a slightly different city layout (random building placement)
2. **Corner Flooding**: Water begins simultaneously from all four corners
3. **Spread Simulation**: Water randomly spreads to adjacent tiles
4. **City Consumption**: Watch as roads flood first, then buildings by height
5. **Game Over**: When all tiles are flooded, the simulation ends

### Strategic Observation
- **Roads flood first** (lowest elevation)
- **Parks and base land** flood early
- **Low buildings** resist briefly
- **Medium and tall buildings** last longer
- **Special landmarks** are the final holdouts

## 🎲 Future Expansions

### Planned Features
- **Player Tokens**: Physical or digital player pieces
- **Resource Management**: Limited materials to save the city
- **Cooperative Mode**: Work together to save both cities
- **Competitive Mode**: Hoard resources for survival
- **Multiple Cities**: Expand to larger grids with multiple urban centers
- **Climate Events**: Additional disasters beyond flooding
- **Victory Conditions**: Specific goals for city salvation

### Board Game Integration
- **Physical Grid**: 3D printed or cardboard city pieces
- **Digital Events**: Tablet/phone for random event generation
- **Hybrid Mechanics**: Combine physical pieces with digital effects
- **Multiplayer**: Support for 2-4 players with different strategies

## 🎮 Game Design Philosophy

### Visual Storytelling
The game tells the story of climate change through pure visual progression. No text or explicit narrative is needed - the steady consumption of a beautiful city by rising waters speaks for itself.

### Emotional Journey
1. **Wonder**: Initial appreciation of the detailed, beautiful city
2. **Tension**: Anticipation as water begins to spread
3. **Anxiety**: Watching familiar structures disappear
4. **Acceptance**: Recognition of the inevitable outcome
5. **Reflection**: Contemplation of real-world implications

### Accessibility
- **No Text Required**: Entirely visual gameplay
- **Universal Understanding**: Flooding concept is universally recognized
- **Adjustable Speed**: Players can control pacing for comfort
- **Multiple Viewpoints**: 3D rotation accommodates different preferences

## 🛠️ Development Notes

### Technical Decisions
- **Pure CSS 3D**: Chose CSS transforms over WebGL for simplicity and compatibility
- **Grid Layout**: CSS Grid provides perfect tile alignment
- **Gradient Lighting**: Multiple background layers create realistic lighting
- **Animation Performance**: Optimized for smooth 60fps on modern devices

### Design Iterations
1. **Started**: Simple 2-city grid concept
2. **Evolved**: Single 15x15 city with basic blocks
3. **Enhanced**: 30x30 city with detailed buildings
4. **Refined**: Added realistic textures, lighting, and effects
5. **Perfected**: Four-corner flooding with building variety

## 📱 Browser Compatibility

### Recommended Browsers
- **Chrome**: Full support, best performance
- **Firefox**: Full support, good performance
- **Safari**: Full support (desktop & mobile)
- **Edge**: Full support

### Mobile Support
- **Touch Controls**: Drag to rotate on touchscreens
- **Responsive**: Scales appropriately on all screen sizes
- **Performance**: Optimized for mobile GPUs

## 🎯 Educational Value

### Climate Awareness
- **Visual Impact**: Shows consequences of rising sea levels
- **Urban Planning**: Demonstrates vulnerability of coastal cities
- **Systemic Thinking**: Illustrates how local actions have global effects

### Game Design Learning
- **3D CSS**: Advanced CSS transform techniques
- **Animation**: Smooth transitions and effects
- **Responsive Design**: Cross-device compatibility
- **User Experience**: Intuitive controls and feedback

---

## 🏆 Credits

**Game Design & Development**: Board-meets-digital hybrid concept
**Visual Design**: 3D isometric city with realistic lighting
**Technical Implementation**: Pure HTML/CSS/JavaScript

---

*"In the face of rising tides, will humanity cooperate or compete? The choice is yours, but the water keeps rising..."*

🌊 **Tide of Ashes** - Where every decision matters, and time is running out.
