# JLPT Grammar Graph Database

This is not a traditional Anki deck. It is a **relational grammar database** designed to mirror how the human brain actually stores information: through connections, not lists. 

Instead of treating grammar points as isolated objects, this system visualizes the relationships between them as an **interconnected "Family Tree" (Erbbaum)** with adjustable degrees of relation.

## 🔷 System Prerequisites

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

🔗 **[View the Relation Degree Graph](https://ankiweb.net/shared/info/1321136162)** (AnkiWeb ID: 1321136162)

This add-on serves as the engine for exploration:
* **Dynamic Tagging:** It scans your database for connected grammar points across multiple levels (degrees).
* **Cluster Creation:** It generates tags for entire "theme families," allowing you to study related concepts (e.g., all nuances of *~mitai*) as a single block.
* **Interactive Visualization:** Map out how one concept branches into others across different JLPT levels.

---

## 🚀 Key Features (Enhanced Version)

### 1. Visual Graph & Filtering
* **Erbbaum Visualization:** View a network of related grammar points with adjustable degrees of kinship.
* **Network Filtering:** Display specific sub-networks to focus on particular nuances.

### 2. Smart Construction & Sentence Parsing
* **Structural Blueprint:** Each card features a dedicated **Construction** section, visualizing exactly how the grammar point connects to verbs, nouns, and adjectives.

### 3. Automated Neural Audio Queue
The deck features a sophisticated, triple-layered audio system using Microsoft Edge Neural TTS:
1. **Title Audio:** Hear the grammar point and its meaning immediately.
2. **Construction Audio:** Auditory reinforcement of the connection rules.
3. **Example Audio:** Native-speed playback of all example sentences.

---

## 🛠 How to Use 

### 1. The Relation Crawler (Creating Clusters)
1. **Select Cards:** Highlight base cards in the Anki Browser.
2. **Start the Crawler:** Press `Ctrl + Alt + R` or use `Edit -> Tag _Process Degree Relations`.
3. **Configure:** Choose your search depth (Degree) and create a **Filtered Deck**.

### 2. Mobile Immersion & Syncing Progress
Take your study away from the screen by combining the Crawler with the Audio Extractor.

* **Required Add-on: Audio Extractor** – [AnkiWeb ID 348642953](https://ankiweb.net/shared/info/348642953)

**Workflow for Mobile Learning:**
1. **Filter your Cluster:** Gather a grammar family using the Relation Crawler.
2. **Extract Audio:** Use the Audio Extractor (`Edit` -> `Auswahl: Audio exportieren`) to batch-download the audio for those cards.
3. **Mobile Study:** Listen to the files on your phone while commuting.
4. **⚠️ IMPORTANT (Bulk Grading):** After you finish your audio session, don't forget to sync your progress! Since you learned the material offline, go back to the Anki Browser, select the cards you just listened to, and use the **[Advanced Browser Bulk Grader](https://ankiweb.net/shared/info/1021636467)** to mark them as **"Good"**. This ensures your SRS schedule stays up to date with your actual knowledge.

---

## 📝 Philosophy
"Relations are abstract and not always mutual. Every grammar point is a standalone object, but the more connections you understand, the broader your mastery becomes."

---
*Developed for learners who want a deeper, faster, and more logical approach to Japanese mastery.*
