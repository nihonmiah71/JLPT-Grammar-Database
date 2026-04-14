# Disclaimer

Due to filesize issues the deck with audiofiles can be found on https://drive.google.com/file/d/1P3xBSHHB26fl5I7XyeRaTjwXtzGfPcpA/view?usp=sharing

The light version without the audiofiles is here

You cannot rename the deck otherwise the crawler addon will not work

Note: For advanced learners
To practice your listening skills i.e. to drop the english audio or the construction audio, you can just copy the deck in anki, and then in the copied deck and then go to the browser select all notes rightclick go on notes, click find and replace and then instruct to change the string "sound" to something else like "s@und" in the desired fields and the audio will not be played anymore and you can just focus on the japanese listening

# JLPT Grammar Graph Database

This is not a traditional Anki deck. It is a **relational grammar database** designed to mirror how the human brain actually stores information: through connections, not lists. 

Instead of treating grammar points as isolated objects, this system visualizes the relationships between them as an **interconnected "Family Tree" (Erbbaum)** with adjustable degrees of relation.

## 🔷 System Prerequisites

To use this deck as intended (navigating between related cards, maintaining the link structure, viewing graphs, and exporting audio for mobile study), you **must** install the following Anki add-ons:

* **Link Cards Add-on:** [AnkiWeb ID 1077002392](https://ankiweb.net/shared/info/1077002392) – Enables jumping between linked cards.
* **Anki-Info (Extended Statistics):** [AnkiWeb ID 744725736](https://ankiweb.net/shared/info/744725736) – Required to display card-specific statistics within the template.
* **Relation Degree Graph & Crawler:** [AnkiWeb ID 1321136162](https://ankiweb.net/shared/info/1321136162) – **CRITICAL:** This is the dual-purpose engine used for both visualizing the grammar network and crawling connections to generate **Filtered Decks**.
* **Audio Extractor from Selected Cards:** [AnkiWeb ID 348642953](https://ankiweb.net/shared/info/348642953) – Used to export audio for offline mobile immersion.
* **Advanced Browser (Bulk Grader):** [AnkiWeb ID 1021636467](https://ankiweb.net/shared/info/1021636467) – Essential for syncing progress after offline study sessions.

---

## 🧠 The Concept: Grammar as a Network

Traditional learning is often siloed by JLPT levels. This database breaks those walls. A card is considered "related" based on three main pillars:
1. **JLPT Level Proximity:** Proximity within the formal testing hierarchy.
2. **Phonetic Similarity:** Structures sharing the same keywords (e.g., structures using *wake*, *mono*, or *nagara*).
3. **Semantic Overlap:** How closely the meanings or nuances align.

### The "Family Tree" (Relation Degree)
You can explore these connections through a visual graph. This allows you to see the "surface" of Japanese grammar while simultaneously digging into the deep-rooted connections.

🔗 **[View the Relation Degree Graph](https://ankiweb.net/shared/info/1321136162?cb=1775920447065)** (AnkiWeb ID: 1321136162)

This add-on serves as the engine for exploration:
* **Dynamic Tagging:** It scans your database for connected grammar points across multiple levels (degrees).
* **Cluster Creation:** It generates tags for entire "theme families," allowing you to study related concepts (e.g., all nuances of *~mitai*) as a single block.
* **Interactive Visualization:** Map out how one concept branches into others across different JLPT levels.

The " みたい" Family of degree 1, 2, 3:

<img width="979" height="623" alt="image" src="https://github.com/user-attachments/assets/106e3aae-3a6f-413d-b236-fce2b0c9a969" />

Video Link for degree 2:
https://github.com/user-attachments/assets/01ecc6cf-03b4-4220-b0d1-26857b3ef7c2

Video Link for degree 3:
https://github.com/user-attachments/assets/2b9c75aa-e750-413a-bc37-0b184a35c306

---

## 🚀 Key Features (Enhanced Version)

### 1. Visual Graph & Filtering
* **Erbbaum Visualization:** View a network of related grammar points with adjustable degrees of kinship.
* **Network Filtering:** Display specific sub-networks to focus on particular nuances.
* **Browser Integration:** Access a global overview or a detailed single-view directly within the Anki browser.

Big Graph Demo Video click link:
https://github.com/user-attachments/assets/635b9d71-c994-43cc-bddb-f8bd3170f4fc
<img width="645" height="614" alt="image" src="https://github.com/user-attachments/assets/2d311315-ba58-455c-a3bb-81a7acbd0592" />

### 2. Smart Construction & Sentence Parsing
* **Structural Blueprint:** Each card now features a dedicated **Construction** section, visualizing exactly how the grammar point connects to verbs, nouns, and adjectives.
* **Example Context:** High-quality example sentences provide immediate context, highlighting the grammar point in real-world usage.

### 3. Automated Neural Audio Queue
The deck features a sophisticated, triple-layered audio system using Microsoft Edge Neural TTS:
1. **Title Audio:** Hear the grammar point and its meaning immediately.
2. **Construction Audio:** Auditory reinforcement of the connection rules.
3. **Example Audio:** Native-speed playback of all example sentences.

### 4. Efficiency & "The Surface"
* **Bulk Grading:** On Desktop, it is recommended to use the [Advanced Browser Add-on](https://ankiweb.net/shared/info/1021636467) for bulk grading ("Good"). 
* **Quick Reference:** Each entry focuses on the essentials via [JLPT Sensei](https://jlptsensei.com), allowing you to grasp a point in ~3 minutes.

---

## 🛠 How to Use 

### 1. The Relation Crawler & Filtered Decks
This process uses the **Relation Degree Graph & Crawler** add-on to build your study sets.

1. **Select Cards:** Highlight base cards in the Anki Browser.
2. **Start the Crawler:** Press `Ctrl + Alt + R` or use `Edit -> Tag _Process Degree Relations`.
3. **Configure Cluster:** Choose your search depth (Degree).
4. **Create Study Session:** Use the add-on's built-in feature to automatically generate a **Filtered Deck** for the identified grammar cluster.
5. **Interactive Learning:** Use the direct links on the back of each card to jump to related points.

### 2. Mobile Immersion & Syncing Progress
Take your study away from the screen by combining the Crawler with the Audio Extractor.

* **Required Add-on: Audio Extractor** – [AnkiWeb ID 348642953](https://ankiweb.net/shared/info/348642953)

**Workflow for Mobile Learning:**
1. **Filter your Cluster:** Gather a grammar family using the Relation Crawler and creating a tag and then search for it in the browser (same add-on mentioned above).
2. **Extract Audio:** Use the Audio Extractor (`Edit` -> **"Selection: Export Audio"**) to batch-download the audio for those cards.
3. **Mobile Study:** Listen to the files on your phone while commuting or working out.
4. **⚠️ IMPORTANT (Bulk Grading):** Since you learned the material offline via audio, you must sync your progress manually. Go back to the Anki Browser, select the cards you've listened to, and use the **[Advanced Browser Bulk Grader](https://ankiweb.net/shared/info/1021636467)** to mark them as **"Good"**. This is essential to keep your SRS schedule accurate!

---

## 📝 Philosophy
"Relations are abstract and not always mutual. Every grammar point is a standalone object, but the more connections you understand, the broader your mastery becomes. It’s like climbing a mountain—the air gets thin, but the view becomes crystal clear."

---
*Developed for learners who want a deeper, faster, and more logical approach to Japanese mastery.*
