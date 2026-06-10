# Oracul
# Project "Oracle"

**Oracle** is an interactive web application designed for self-discovery, internal reflection, and meditative work with your subconscious.
## Project Philosophy
The core philosophy of "Oracle" is based on the idea that technology can serve as a tool for psychological relief and self-analysis. The project does not offer ready-made "precise predictions" of fate, but rather provides a mindful digital space for the personal interpretation of symbols, archetypes, and visual imagery. Each tool helps you look inward and find answers to your questions through the lens of personal associations.

## App Features: 5 Tool-Pages
1. **Main Page (Portal)**
   The central hub of the application, designed as a cosmic portal. It contains 4 animated, clickable cards to access the key practices. The visual atmosphere is set by a dynamic video background featuring a falling star shower.
2. **Card of the Day**
   A digital tool for daily reflection. Includes a full classic Tarot deck (78 cards).
   * **Mechanics:** Features a smart 24-hour timer that restricts repeated card draws to encourage deep reflection on the drawn arcanum.
   * **Visuals:** Spectacular, smooth 3D flip animation when a card is selected.
3. **Numbers of Fate (Numerology)**
   A comprehensive numerological calculator. Based on user input, the app calculates 5 key personality metrics, including an analysis of rare and powerful master numbers, as well as a built-in partner compatibility module.
4. **Magic 8-Ball**
   A digital interpretation of the classic Magic 8-Ball. Contains a database of 20 canonical and adapted answers. A special immersive atmosphere is created by visual effects of dissipating fog and "whispered" answers.
5. **Letter to the Universe**
   A therapeutic practice of expressive writing. Users can articulate their thoughts, fears, or desires and send them into digital space. The interface adapts to the user's real-time zone, smoothly changing the sky theme and color palette (morning, day, evening, night).

## Technical Features & Stack
The project is built at the intersection of modern web design and high-performance requirements
* **Design (UI/UX):** The interface is crafted in the ultra-modern **Glassmorphism** style — translucent textures, soft backdrop-filter blur, and neon glows.
* **Responsiveness:** Fully responsive layout using **Flexbox**, **CSS Grid**, and the adaptive `clamp()` function for flawless display on any device (from small smartphones to 4K monitors).
* **Performance Optimization:**
  * Over 140 graphical assets and card images are optimized and converted to the modern **WebP** format without any quality loss.
  * The background video is compressed using the next-generation **H.265/HEVC** codec, ensuring minimal file size and instant page loading.
* **CSS Animations:** The interface feels "alive" thanks to complex CSS effects: gradient flows, pulsating glows, element rotations, twinkling stars, and flying particles.
* **State Management:** Uses **localStorage** to save timer states and user sessions without the need to deploy a heavy database at the initial stage.

## Roadmap
- [ ] **AI Integration:** Integrating an AI module to generate personalized interpretations of drawn Tarot cards. The AI will analyze not just the standard meaning of the arcanum, but correlate it with the specific text question entered by the client, creating a deep, individual context for the reading.
- [ ] Expand numerological charts and implement natal chart generation.
- [ ] Add immersive audio accompaniment (ambient, nature sounds) for each page.
