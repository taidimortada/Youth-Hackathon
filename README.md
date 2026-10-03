🧭 Baosala Tangier

Discover Tangier Differently — اكتشف طنجة بطريقة مختلفة

Baosala Tangier is a mobile-first tourism web app/PWA concept designed to help visitors discover Tangier, Morocco through its heritage, local food, artisan experiences, activities, stays, and authentic traveler experiences.

The project combines trip discovery, itinerary planning, traveler matching, cultural tools, and multilingual support in one interface.

🌍 Project Idea

Traditional tourism platforms often focus on famous attractions and standard tourist routes. Baosala Tangier aims to create a more local, cultural, and personalized experience.

The application helps a visitor:

Discover cultural and historical places in Tangier.

Find Moroccan food and local experiences.

Explore artisan workshops.

Build a personalized trip plan.

Estimate and manage a travel budget.

Discover other travelers with similar interests.

Learn useful Darija expressions.

Convert currencies.

Read notes and experiences from previous travelers.

Use the application in multiple languages.

✨ Main Features

🏠 Home

The home screen provides a quick introduction to Tangier and shortcuts to the main categories:

Heritage

Artisans

Food

Tours

Hotels

Shopping

Currency

Darija

It also includes featured artisan experiences and a Notes from Previous Travelers section.

🔎 Explore

The Explore section allows users to browse places and experiences by category.

Example categories include:

Heritage

Food

Artisans

Tours

Hotels

Shopping

Viewpoints

Day trips

Each place can contain information such as:

Name

Rating

Price

Opening hours

Description

Suggested transportation

Estimated cost

🗺️ My Plan

The trip planner guides the visitor through several choices, including:

Number of days

Starting point

Interests

Travel pace

Guidance preference

Travel group

Preferred atmosphere/vibe

Total budget

Budget distribution

The app can then generate an itinerary based on these preferences.

🤝 Traveler Match

The Match section presents traveler profiles based on example profile data.

Profiles can include:

Name

Origin

Travel dates

Short biography

Budget

Group type

Interests

Preferred travel vibes

The interface also supports swipe-style actions and chat UI concepts.

Important: The profiles currently included in the HTML are demonstration data, not verified real users.

👤 Profile

The Profile section provides a personal profile interface where users can manage their profile information and avatar.

💬 Traveler Notes

The app includes a section for notes from previous travelers.

These notes are currently demo/example content and should be replaced with real user-generated content before presenting them as actual reviews.

💱 Currency Converter

The app includes a currency conversion interface centered around Moroccan Dirham (MAD).

🗣️ Darija Translator

The application includes a Darija language tool intended to help visitors communicate more easily during their stay in Morocco.

🤖 Travel Chatbot

A chatbot interface is included to provide conversational assistance inside the app.

🌐 Multilingual Interface

The interface includes translations for:

🇬🇧 English

🇫🇷 French

🇲🇦 Arabic

🇪🇸 Spanish

🌙 Dark Mode

Users can switch between light and dark themes.

📱 PWA / Mobile-first Design

The application is designed primarily for mobile screens and includes PWA-oriented functionality such as:

Mobile viewport configuration

Theme color

Apple web-app metadata

Service-worker registration

Responsive layouts

Touch-friendly controls

🛠️ Technologies Used

The current version is implemented as a single HTML file containing the application interface, styles, data, and JavaScript logic.

Frontend

HTML5

CSS3

JavaScript

Tailwind CSS

Responsive design

Fonts

The interface uses:

Fraunces

Nunito Sans

Tajawal

External Resources

Tailwind CSS and Google Fonts are loaded through CDN links.

📁 Project Structure

The current project is intentionally simple and can be opened directly in a browser.

Baosala-Tangier/
│
├── baosala_tangier_app_with_user_notes.html
└── README.md

The HTML file contains the main application.

Important JavaScript sections include:

Global state
    ↓
Navigation
    ↓
Home
    ↓
Explore
    ↓
Currency
    ↓
Darija Translator
    ↓
Trip Planner
    ↓
Traveler Match
    ↓
Profile

🚀 How to Run

Method 1 — Open directly

Download or clone the project.

Open:

baosala_tangier_app_with_user_notes.html

Open the file in a modern browser such as Chrome or Edge.

Method 2 — VS Code

Open the project folder in VS Code.

Install Live Server if desired.

Right-click the HTML file.

Select Open with Live Server.

This makes development and testing easier.

🧩 Main JavaScript Functions

The current application contains functions for the major screens and interactions.

Examples:

navigate()
changeLanguage()
toggleTheme()
renderMainContent()
renderHomeView()
renderExploreView()
renderCurrencyView()
renderTranslatorView()
renderPlanView()
generatePlanItinerary()
renderMatchView()
renderProfileView()

The application also contains interaction logic for:

Search

Category navigation

Trip planning

Budget sliders

Match actions

Chat messages

Demo booking

Profile editing

Avatar upload

Language switching

Dark mode

🗃️ Data

The application currently uses JavaScript objects and arrays directly inside the HTML file.

For example:

const PLACES_DATA = {
    heritage: [...],
    food: [...],
    workshops: [...],
    ...
};

Traveler matching data is stored in:

const MATCH_PROFILES = [
    ...
];

Traveler notes are stored in:

const USER_NOTES = [
    ...
];

This approach is useful for a prototype because the application can work without a backend.

⚠️ Current Prototype Limitations

This version is a frontend prototype rather than a complete production platform.

Some features are simulated or use local/demo data.

Before production, the project would need:

A real backend/database.

Real user authentication.

Secure Google login.

Real traveler accounts.

Real reviews and notes.

Real booking integrations.

A reliable currency API.

Real-time chat infrastructure.

Maps and location services.

Proper notification infrastructure.

Server-side security and validation.

Image hosting/CDN.

Privacy and account-management features.

A production PWA service worker and manifest.

🔐 Authentication

The current prototype should not be considered a complete authentication system.

If Google Sign-In or another authentication provider is added, authentication should be implemented using the provider's official SDK and a secure backend/session architecture.

Never place private API keys, client secrets, database passwords, or service credentials directly inside the HTML file.

🖼️ Images

The application currently uses image URLs for visual content.

When replacing prototype images:

Use high-quality images relevant to Tangier and Morocco.

Make sure the image can legally be used by the project.

Prefer official tourism sources, your own photographs, or properly licensed stock images.

Avoid assuming that an image found through Google Images is free to use.

🎨 Design Language

Baosala uses a Moroccan-inspired visual identity.

Main visual ideas include:

Moroccan zellij-inspired patterns

Arch-shaped image frames

Navy blue

Terracotta

Sand

Mustard

Emerald green

Moroccan/Arabic typography

Rounded mobile cards

Large touch targets

The goal is to combine a modern mobile interface with visual references to Moroccan architecture and culture.

🧪 Development Workflow

A simple development workflow is:

Idea
  ↓
UI/UX design
  ↓
HTML structure
  ↓
Tailwind styling
  ↓
JavaScript interactions
  ↓
Browser testing
  ↓
Mobile testing
  ↓
User testing
  ↓
Backend integration
  ↓
Production deployment

For future development, the single-file prototype can be separated into:

src/
├── components/
├── pages/
├── data/
├── services/
├── styles/
└── utils/

This would make the application easier to maintain as it grows.

🔮 Future Improvements

Possible next steps include:

Backend

User accounts

Database

Secure authentication

Reviews

Saved trips

User-generated places

Maps

Interactive Tangier map

Walking routes

Places nearby

Transport information

GPS-based recommendations

AI

Personalized itinerary generation

Conversational tourism assistant

Smart recommendations

Translation assistance

Personalized cultural suggestions

Community

Real traveler reviews

Traveler notes

Local guides

Artisan profiles

Community recommendations

Booking

Artisan workshop reservations

Tours

Hotels

Activities

Restaurant recommendations

PWA

Installable application

Offline content

Push notifications

Better caching

App icons and manifest

🎯 Project Vision

Baosala Tangier aims to make discovering Tangier more personal.

Instead of simply asking:

“What are the famous places in Tangier?”

the application aims to answer:

“What kind of Tangier experience is right for me?”

The long-term vision is to connect visitors with the culture, people, crafts, food, stories, and hidden experiences that make Tangier unique.

📄 License

No specific open-source license is currently defined for this prototype.

If the project is published publicly, add an appropriate license file such as:

LICENSE

and clearly define how the code, images, data, and other project assets may be reused.

👥 Project Status

Status: Prototype / Hackathon-ready concept

Platform: Web / Mobile-first PWA concept

Location focus: Tangier, Morocco 🇲🇦

Primary goal: Cultural tourism and personalized discovery

❤️ Baosala

Baosala — Discover Tangier Differently.

البوصلة — اكتشف طنجة بطريقة مختلفة.
