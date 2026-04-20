# ScriptingExercise-u232954
Erik Verdier Montero (u232954)

The compiled game build is available in Releases.

## Extra Features Implemented

### 1. Heart Effect System
- Added a heart prefab that appears when a sheep is hit by hay
- Heart floats upward, rotates, and shrinks before disappearing
- Sheep also shrink when hit, creating a "poof" effect

### 2. Sound Effects
- Shooting sound when hay machine fires
- Hit sound when sheep is saved
- Fall sound when sheep drops off the edge

### 3. Score System (Game State Manager)
- Tracks number of sheep saved
- Tracks number of sheep dropped
- Game ends after 3 sheep fall
- Press ESC to return to title screen

### 4. UI Manager
- Real-time display of saved and dropped sheep
- Game over window appears when game ends

### 5. Title Screen
- Start button loads the game scene
- Quit button exits the application
- Buttons change color when mouse hovers over them

---

## New Scripts Created
- `TweenScale.cs` - Handles scaling animations
- `DestroyTimer.cs` - Destroys objects after delay
- `SoundManager.cs` - Manages all audio playback
- `GameStateManager.cs` - Manages game state and scoring
- `UIManager.cs` - Updates UI elements
- `StartButton.cs` - Loads game scene
- `QuitButton.cs` - Exits application
- `ChangeColorOnMouseOver.cs` - Button hover effects

---

## Modified Scripts
- `Sheep.cs` - Added heart instantiation, sounds, and scoring
- `HayMachine.cs` - Added shooting sound
- `SheepSpawner.cs` - Added DestroyAllSheep method


Extras were implemented by following the second part of the tutorial series, "Introduction to Unity Scripting – Part 2".
