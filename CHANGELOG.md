# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [1.5.0] - 2025-08-11

### ✨ Added
- **New NestJS E-commerce Project:** Added comprehensive NestJS e-commerce implementation as 2nd project showcasing TypeScript, class-based SOLID principles, and modern backend architecture
- **NestJS Technology Tag:** Created new technology tag with official NestJS logo and red theme styling
- **NestJS Icon Component:** Developed `NestJS.astro` icon component with currentColor support for proper theme integration
- **Enhanced Project Portfolio:** Added 7th project to portfolio with comprehensive documentation and GitHub repository integration

### 🎨 Improved
- **Icon Color System:** Updated NestJS icon to use `currentColor` for proper white icon rendering on red background
- **Background System:** Enhanced main container with theme-aware backgrounds (gray-50 for light mode, gray-900 for dark mode)
- **Animated Background:** Added opacity controls with theme-specific settings (50% for light mode, 70% for dark mode)
- **Project Descriptions:** Enhanced multilanguage descriptions highlighting clean code practices, scalable design patterns, and industry best practices

### 🔧 Technical Enhancements
- **Theme-Aware Styling:** Implemented proper background color system that adapts to light/dark theme toggle
- **Canvas Opacity Control:** Added theme-responsive opacity settings for animated background canvas
- **Component Architecture:** Enhanced Projects component with proper NestJS tag integration and icon rendering
- **Translation System:** Expanded multilanguage support for new NestJS project in both English and Spanish

### 📋 Content Updates
- **Project Portfolio:** Added "Backend Project - NestJS E-commerce Implementation" with emphasis on TypeScript stack and SOLID principles
- **Technology Stack:** Expanded technology showcase with NestJS framework representation
- **Multilanguage Content:** Added comprehensive translations for new project descriptions and technology tags
- **Professional Presentation:** Enhanced project descriptions to highlight technical achievements and development methodologies

## [1.4.0] - 2025-07-31

### ✨ Added
- **New Experience Entry:** Added current freelance position (May 2024 - Present) as Software Engineer with comprehensive technology stack including ReactJS, NextJS, AWS services, and AI automation tools
- **Skills & Technologies Section:** Added dedicated section showcasing core technologies, tools & collaboration, and languages with visual tags and icons
- **New Backend Project:** Added "Backend Project - Native JavaScript Implementation" as 5th project demonstrating vanilla JavaScript best practices and documentation workflows
- **New Technology Tags:** 
  - Documentation/Notebook tag with custom orange styling for documentation-focused projects
  - Enhanced JavaScript tag usage across projects
- **Enhanced Navigation:** Added Skills section to main navigation menu for improved user experience

### 🎨 Improved
- **Skills Section Layout:** Positioned Skills & Technologies section immediately after Hero section for prominent display of technical expertise
- **Technology Stack Display:** Created reusable TechStack component for consistent presentation of skills with proper icon mapping
- **Project Descriptions:** Enhanced project descriptions with improved English and Spanish translations focusing on technical achievements and best practices
- **Experience Timeline:** Updated experience section with most recent freelance work highlighting leadership, project rescue, and AWS cloud services management

### 🔧 Technical Enhancements
- **Component Architecture:** Developed modular TechStack.astro component supporting 40+ technology mappings with proper icon rendering
- **Multilanguage Expansion:** Added comprehensive translations for new Skills section and Backend project in both English and Spanish
- **Icon System Integration:** Enhanced icon rendering system to support new Documentation tag alongside existing technology icons
- **Project Positioning:** Implemented precise project ordering with new Backend project positioned as 2nd item in portfolio

### 📋 Content Updates
- **Professional Experience:** Added detailed descriptions of freelance software engineering work including AI workflow automation, team leadership, and full-stack development
- **Technology Showcase:** Comprehensive display of 25+ core technologies, 15+ collaboration tools, and 3 language proficiencies
- **Project Documentation:** Enhanced project descriptions emphasizing software engineering best practices, architectural patterns, and formal documentation structures

## [1.3.0] - 2025-07-30

### ✨ Added
- **New Projects Section:** Added two new projects to the portfolio:
  - **Lazy Loading - Native JavaScript Implementation:** Comprehensive repository showcasing advanced lazy loading techniques with infinite scroll and image optimization
  - **CI/CD Template - Husky, TypeScript & Linting Integration:** Development template for maintaining code standards in small to medium teams
- **New Technology Tags:** 
  - JavaScript tag with official JS logo icon
  - TypeScript tag with official TS logo icon  
  - Infrastructure tag with custom DevOps-themed icon
- **Enhanced Multilanguage Support:** Added complete English and Spanish translations for new projects and technology tags
- **Icon Components:** Created new SVG icon components for JavaScript, TypeScript, and Infrastructure technologies

### 🎨 Improved
- **Projects Structure:** Enhanced project data structure with proper multilanguage support for technology tags
- **Icon Rendering:** Improved dynamic icon rendering system to handle both component-based and plain .astro file icons
- **Project Descriptions:** Enhanced and refined project descriptions for better clarity and professional presentation

### 🔧 Fixed
- **Astro Icon Compatibility:** Resolved rendering issues with Astro icon component by standardizing icon file structure
- **Import References:** Fixed import paths and component references in Projects.astro

## [1.2.10] - 2025-07-30

### 🐞 Fixed
- **Burger Menu Dark Mode:** Restored original burger menu background color: white in light mode and gray-800 in dark mode, matching initial design. Fixed dark mode switching issue in responsive menu.

## [1.2.9] - 2025-07-30

### 🎨 Improved
- **Navigation Menu & Toggles:** Refactored `Header.astro` to center navigation items with a scroll/rounded background effect, and visually separate language/theme toggles, positioning them absolutely for a cleaner, more consistent look across devices.

## [1.2.8] - 2025-07-30

### 🎨 Improved
- **Navigation & Section Headers:** Updated navigation and section header components for better usability and consistency. Includes improved highlighting and structure in `Header.astro` and changes in `TitleSection.astro`.

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
