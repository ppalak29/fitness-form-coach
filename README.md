# Fitness Form Coach

Real-time workout tracking with automatic rep counting and form feedback. Built for home gym lifters who want to track their progress without a spotter.

## [Try it now](https://ppalak29.github.io/fitness-form-coach)

## Features

### **Automatic Rep Counting**
- Counts reps in real-time using computer vision
- No manual tracking needed
- Audio feedback on each rep

### **Optional Rep Targets**
- Set your goal before starting (e.g., "10 reps")
- Live countdown: "3 left... 2 left... 1 left..."
- Celebration when you hit your target

### **Form Feedback**
- **Squat:** Depth analysis ("GO DEEPER" vs "GOOD DEPTH!")
- **Overhead Press:** Lockout tracking + symmetry check
- Real-time feedback during your set

### **Session History**
- Save every set
- Track progress over time
- View past workouts (date, exercise, reps)

### **Privacy Options**
- Video feed (default) - see yourself
- Skeleton-only mode - no video, just tracking points

## Supported Exercises

✅ **Squat** (side view)
- Tracks knee angle for depth
- "Good depth" at parallel or below

✅ **Overhead Press** (front view)
- Tracks arm lockout
- Checks left/right symmetry

## How to Use

### **Squat:**
1. Open the app on your phone
2. Prop phone 3-5 feet away
3. **Stand SIDEWAYS to camera** (full body visible)
4. Optional: Set rep target (e.g., "10")
5. Stand still for 2 seconds to calibrate
6. Start squatting!

### **Overhead Press:**
1. Open the app on your phone
2. Prop phone at chest height
3. **Face the camera** (upper body visible)
4. Optional: Set rep target
5. Hold still for 2 seconds
6. Start pressing!

### **After Your Set:**
- Click "SAVE SET" to log it
- View history anytime
- Track your progress

## Keyboard Shortcuts

- **R** - Reset rep count
- **Q** - Quit to main menu
- **V** - Toggle video/skeleton mode
- **S** - Save set

## Tech Stack

- **MediaPipe Pose Detection** - Real-time body tracking
- **Vanilla JavaScript** - No frameworks, fast and lightweight
- **GitHub Pages** - Free hosting, no backend needed
- **localStorage** - Session history stored locally (private)

## Privacy

- Everything runs in your browser
- No video uploaded anywhere
- No account required
- Session history stored locally on your device

## Limitations

- **Requires good lighting** - Works best in well-lit areas
- **Camera angle matters** - Follow setup instructions for each exercise
- **Form analysis is basic** - Tracks depth/ROM, not advanced biomechanics
- **2 exercises only** - More coming based on user feedback

## Roadmap

**v2 (Based on user feedback):**
- More form correction based on biomechanics
- Add more exercises (deadlift, bench press, rdls, pull-ups)
- Rest timer between sets
- Workout templates
- Export history to CSV

**v3 (If there's demand):**
- ML-based form analysis
- Bar path tracking
- Video recording of sets
- Social features (share PRs)

## Feedback

Built by a college student who lifts 6x/week. Looking for beta testers!

**Found a bug?** Open an issue or DM me.

**Want a feature?** Let me know what would make this useful for you.

**Using it regularly?** I'd love to hear how it's working for you.

## Acknowledgments

- MediaPipe by Google for pose detection
- Inspired by lifting 6x/week and hating manual rep counting

**[Start Tracking →](https://ppalak29.github.io/fitness-form-coach)**