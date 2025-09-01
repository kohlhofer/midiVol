# CLAUDE.md - MIDI Volume Control Landing Page

## Project Context
This is a modern landing page for **MIDI Volume Control**, a macOS application that allows users to control system and Apple Music volume using MIDI controllers. The app is distributed via the Apple App Store.

## Architecture
- **Framework:** Astro static site generator
- **Styling:** Tailwind CSS
- **Deployment:** GitHub Pages
- **Structure:** Component-based with markdown content support

## Key Commands

### Development
```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run preview      # Preview production build
npm run astro        # Access Astro CLI
```

### Deployment
```bash
npm run build        # Build static files
git add dist/        # Add built files
git commit -m "Deploy to GitHub Pages"
git push origin main # Deploy via GitHub Actions
```

## File Structure
```
/
├── src/
│   ├── components/   # Reusable UI components
│   ├── layouts/      # Page layouts
│   ├── pages/        # Route pages
│   └── styles/       # Global styles
├── public/           # Static assets
│   └── images/       # App screenshots and icons
├── astro.config.mjs  # Astro configuration
└── tailwind.config.cjs # Tailwind configuration
```

## Important Notes

### App Information
- **Name:** MIDI Volume Control
- **Platform:** macOS 10.15+ only
- **Current Version:** 4.0
- **App Store:** Primary distribution channel
- **Icon:** Purple gradient with volume knob design

### Key Features to Highlight
1. **System Volume Control** - Real-time MIDI control of Mac system volume
2. **Apple Music Integration** - Independent Apple Music volume control
3. **MIDI Learn** - Automatic controller mapping
4. **Menu Bar Integration** - Live volume sliders and quick access
5. **Launch at Login** - Automatic startup option
6. **Sandbox Security** - App Store ready with minimal permissions

### Content Guidelines
- Target audience: Musicians, producers, audio professionals
- Emphasize ease of setup and professional use cases
- Highlight macOS integration and security
- Focus on immediate, tactile control benefits

### Design Principles
- Clean, modern design matching macOS aesthetics
- Purple color scheme matching app icon
- Large, prominent app icon display
- Clear, action-oriented CTAs
- Professional yet approachable tone

### Assets Available
- `images/AppIcon.png` - High-resolution app icon
- `images/Settings.png` - Settings window screenshot  
- `images/MenuBar.png` - Menu bar interface screenshot
- `context/README.md` - Detailed app documentation
- `context/ReleaseNotes.md` - Version history
- `context/MIDIVolumeControlHelp.md` - User help documentation

### SEO Focus
- Keywords: MIDI, volume control, macOS, audio control, music production
- Target: Musicians and audio professionals using macOS
- App Store optimization for discoverability

## Development Workflow
1. Use component-based architecture for maintainability
2. Optimize images for web (WebP format recommended)
3. Ensure responsive design for all device sizes
4. Test App Store button functionality
5. Validate markup and performance before deployment

## Future Expansion
- Help/FAQ section using existing documentation
- Blog for updates and tutorials
- User testimonials and reviews integration
- Video demonstrations of app functionality