## [1.2.8] - 2025-07-30

### 🎨 Improved
- **Navigation & Section Headers:** Updated navigation and section header components for better usability and consistency. Includes improved highlighting and structure in `Header.astro` and changes in `TitleSection.astro`.
# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.7] - 2025-07-30

### 🎨 Improved
- **Footer Responsive Centering:** Footer content is now centered on small screens for better mobile usability, while maintaining left/right layout on larger screens.

## [1.2.6] - 2025-07-30

### ✨ Added
- **Mouse Repulsion Effect:** Points in the animated background are now dynamically repelled by the mouse cursor, creating an interactive visual effect.

## [1.2.5] - 2025-07-30

### ✨ Added
- **Animated Background Effect:** Added a performant, canvas-based animated background inspired by mouredev.pro with improved z-index layering for visibility behind content but above background color.

## [1.2.4] - 2025-07-30

### ✨ Added
- Experience section and ExperienceItem now fully multilanguage (i18n)

## [1.2.3] - 2025-07-30

### ✨ Added
- Projects section is now fully translatable (i18n)

## [1.2.2] - 2025-07-30

### ✨ Added
- Footer is now fully translatable (i18n)

## [1.2.1] - 2025-07-29

### ✨ Added
- **Dynamic CV Links:** CV download automatically switches between Spanish and English PDF files based on selected language
- **Dynamic LinkedIn Links:** LinkedIn URLs now include locale parameters (es_ES/en_US) for localized LinkedIn experience
- **Multi-Language Asset Support:** Added separate CV files for Spanish (`amilcar_barahona_es_ve.pdf`) and English (`amilcar_barahona_en_ve.pdf`)

### 🔧 Fixed
- **Language-Aware URLs:** All external links now respect user's language preference
- **Cross-Tab Synchronization:** Dynamic links update automatically when language is changed in another browser tab

### 🎯 Behavior
- **Spanish Mode:** Downloads Spanish CV and opens LinkedIn with Spanish locale
- **English Mode:** Downloads English CV and opens LinkedIn with English locale
- **Instant Updates:** Links change immediately when language toggle is used
- **Persistent Preferences:** Link behavior maintains consistency across browser sessions

## [1.2.0] - 2025-07-29

### ✨ Added
- **Language Toggle:** Switch between Spanish/English with ES/EN slider toggle in header
- **Browser Language Detection:** Auto-detects user's browser language on first visit
- **Translation System:** JSON-based translations for navigation, hero, about, and contact sections
- **Language Persistence:** Stores language preference in localStorage across sessions

### 🔧 Fixed
- **Translation Implementation:** Fixed Badge component translation by using slot content instead of attributes
- **Default Content:** Added English fallback text for all translatable elements
- **Language Flash Prevention:** Integrated language detection with existing fade-in system

## [1.1.2] - 2025-07-29

### 🔧 Fixed
- **Theme Flash Prevention:** Added fade-in effect to prevent visible theme switching on page load
- **Code Cleanup:** Removed unnecessary comments from theme toggle implementation

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
