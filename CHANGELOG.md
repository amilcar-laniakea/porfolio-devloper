# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.1] - 2025-07-29

### 🔧 Fixed
- **Contact Navigation:** Fixed contact button in header navigation that was pointing to email instead of page section
- **Missing Contact Section:** Added missing contact section that the navigation was trying to link to

## [1.1.0] - 2025-07-29

### ✨ Added
- **Theme Switch Selector:** Implemented simple switch to toggle between light and dark mode
- **Automatic System Detection:** Application automatically detects browser/operating system theme preference on first load
- **Preference Persistence:** Manual theme selections are saved in localStorage and persist between sessions

### 🔄 Changed
- **Theme Interface:** Replaced 3-option dropdown menu (Light/Dark/System) with intuitive binary switch
- **System Theme Behavior:** "System" theme is now automatic by default, no manual selection needed
- **Theme Icons:** Simplified to only Sun (light) and Moon (dark) with smooth transitions
- **User Interaction:** Single click directly toggles between themes, eliminating menu navigation

### 🎨 Improved
- **UX/UI:** More intuitive experience with direct switch instead of dropdown menu
- **Performance:** Removed unnecessary dropdown menu code
- **Accessibility:** Maintained aria-labels and sr-only for screen readers
- **Animations:** Smooth icon transitions with 300ms duration

### 🔧 Technical Details
- **Component:** `src/components/ThemeToggle.astro` completely refactored
- **Functionality:** Removed System icon and options menu
- **JavaScript:** Simplified theme detection and switching logic
- **CSS:** Optimized styles for new switch behavior

### 🎯 Behavior
- **First Visit:** Automatically detects if browser/OS prefers light or dark mode
- **Manual Interaction:** Single click on switch toggles between light and dark
- **Persistence:** Manual choice is saved and takes priority over system preference
- **Responsive System:** If no manual preference is saved, automatically responds to system preference changes

## [1.0.0] - 2025-07-29

### 🎉 Initial Release
- **Portfolio Base:** Initial portfolio implementation with Astro
- **Dark Theme:** Portfolio with dark theme by default
- **Components:** Base component structure (Header, Footer, Hero, etc.)
- **Navigation:** Functional navigation system
- **Responsive Design:** Adaptive design for different devices
- **View Transitions:** Smooth page transitions with Astro
- **Tailwind CSS:** Styling system with Tailwind CSS configured with dark mode

---

## Types of Changes
- `Added` for new features
- `Changed` for changes in existing functionality
- `Deprecated` for soon-to-be removed features
- `Removed` for now removed features
- `Fixed` for any bug fixes
- `Security` for security updates
