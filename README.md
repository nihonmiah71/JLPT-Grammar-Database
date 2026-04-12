# JLPT Grammar Graph Database

This is not a traditional Anki deck. It is a **relational grammar database** designed to mirror how the human brain actually stores information: through connections, not lists. 

Instead of treating grammar points as isolated objects, this system visualizes the relationships between them as an **interconnected "Family Tree" (Erbbaum)** with adjustable degrees of relation.

## ⚠️ Core Requirements

To use this deck as intended (navigating between related cards, maintaining the link structure, and viewing progress data), you **must** install the following Anki add-ons:

* **Link Cards Add-on:** [AnkiWeb ID 1077002392](https://ankiweb.net/shared/info/1077002392) – Enables jumping between linked cards.
* **Anki-Info (Extended Statistics):** [AnkiWeb ID 744725736](https://ankiweb.net/shared/info/744725736) – **Required** to display card-specific statistics like "Last Review" and "Total Reviews" within the template.

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
The deck features a sophisticated, triple-layered audio system using Microsoft Edge Neural TTS for ultra-natural immersion:
1. **Title Audio:** Hear the grammar point and its meaning immediately.
2. **Construction Audio:** Auditory reinforcement of the connection rules.
3. **Example Audio:** Native-speed playback of all example sentences.
*All audio files are played in a seamless, automated sequence (Title → Construction → Examples) to maximize efficiency.*

### 4. Efficiency & "The Surface"
* **Bulk Grading:** On Desktop, it is recommended to use the [Advanced Browser Add-on](https://ankiweb.net/shared/info/1021636467) for bulk grading ("Good"). 
* **Quick Reference:** Each entry focuses on the essentials via [JLPT Sensei](https://jlptsensei.com), allowing you to grasp a point in ~3 minutes.
* **Custom Notes:** Dedicated space for your own personal mnemonics and insights.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/607b23d8-eadf-4214-90f2-2c7eec3fea9c" />
<img width="1366" height="727" alt="image" src="https://github.com/user-attachments/assets/616827be-fb1f-4a2d-8d34-7550f6a094b0" />

---

## 🛠 How to Use (Relation Crawler)

To utilize the relational structure and create custom study clusters, follow these steps in the Anki Browser:

1. **Select Cards:** Highlight one or more "base" cards (grammar points you want to explore from).
2. **Start the Crawler:** Press `Ctrl + Alt + R`. Or go to the `Edit` Submenu and then press `Tag _Process Degree Relations`
3. **Configure the Search:**
    * **Depth (Degree):** Choose how many "steps" away from the original card the crawler should look.
    * **Search Log:** Toggle technical logs for link discovery.
    * **Lesson Overview:** Display a clean list of all grammar points in the cluster.
    * **Filtered Deck:** Automatically create a study session for the found cluster.
4. **Interactive Learning:** Use the direct links on the back of each card to jump to related points and compare nuances.

---

## 📝 Philosophy
"Relations are abstract and not always mutual. Every grammar point is a standalone object, but the more connections you understand, the broader your mastery becomes. It’s like climbing a mountain—the air gets thin, but the view (and the ability to use the language) becomes crystal clear."

---
*Developed for learners who want a deeper, faster, and more logical approach to Japanese mastery.*
