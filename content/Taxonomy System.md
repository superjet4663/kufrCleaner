---
title: Taxonomy System
created: 2025-04-28T04:11:45.000-04:00
updated: 2025-04-30T19:36:50.820-04:00
draft: false
---

Bismillah Al-Rahman Al-Raheem.

# Taxonomy System

Clean separation of **ontology (tags)** vs **navigation (MOCs or Portals)**. Instead of themes as tags, **use dedicated MOCs**:

📄 `MOC/prophet-marriages.md` or 📄 `Portals/prophet-marriages.md`

- [[Prophet Muhammadﷺ's Marriage to Aisha]]
- [[Marriage to Zainab Bint Jahsh]]

📄 `MOC/slavery-in-islam.md` or 📄 `Portals/slavery-in-islam.md`

- [[Islam and Slavery Overview]]
- [[Prophet Trading Slaves Refutation]]

📄 `MOC/science-in-quran.md` or 📄 `Portals/science-in-quran.md`

- [[Mountains as Pegs]]
- [[Embryology in Quran]]

**Each MOC file** manually clusters related notes by topic.

| **Facet** | **Prefix**    | **Purpose**                                                       | **Examples**                                                        |
| --------- | ------------- | ----------------------------------------------------------------- | ------------------------------------------------------------------- |
| Source    | `#source/`    | Where argument or data is sourced from                            | `#source/quran`, `#source/research-paper`                           |
| Defense   | `#defense/`   | Which Islamic reality/element is being defended                   | `#defense/prophet`, `#defense/slavery`                              |
| Attack    | `#attack/`    | What type of external criticism is being answered or responded to | `#attack/historical-criticism`, `#attack/character-assassination`   |
| Framework | `#framework/` | Intellectual discipline being used for analysis/refutation        | `#framework/aqidah`, `#framework/logic`, `#framework/usul-tafsir`   |
| Audience  | `#audience/`  | Who the argument is targeted towards, target audience (attackers) | `#audience/exmuslim`, `#audience/orientalist`, `#audience/feminist` |

| **Type**                  | **Label**                           | **Purpose**                                 | **Example**                                                      |
| ------------------------- | ----------------------------------- | ------------------------------------------- | ---------------------------------------------------------------- |
| `#type/period`            | **Historical Periods**              | Era notes, timelines, major shifts          | _Islamic Golden Age_, _First Fitna_                              |
| `#type/event`             | **Major Events**                    | Specific events, battles, treaties          | _Battle of Badr_, _Treaty of Hudaybiyyah_                        |
| `#type/person`            | **Biographical Notes**              | Individuals, scholars, figures              | _Imam Al-Ghazali_, _Khalid ibn al-Walid_                         |
| `#type/text`              | **Primary Texts**                   | Books, scriptures, treatises                | _Sahih Bukhari_, _Muwatta Imam Malik_                            |
| `#type/concept`           | **Abstract Concepts**               | Aqidah terms, Fiqh categories, etc.         | _Tawhid_, _Ijma'_, _Naskh_                                       |
| `#type/theory`            | **Philosophical/Usuli Theories**    | Intellectual constructs                     | _Maqasid al-Shariah_, _Theory of Abrogation_                     |
| `#type/argument`          | **Arguments or Refutations**        | Formal logical cases                        | _Refutation of Apostasy Claims_, _Defense of Shariah Penal Laws_ |
| `#type/portal`            | **Portals (Hubs)** or **MOCs**      | Big indexes or clusters                     | _Portal: Quran_, _Portal: Apostasy_                              |
| `#type/comparison`        | **Comparative Studies**             | Islam vs Christianity, Islam vs Secularism  | _Comparison: Jesus in Islam vs Christianity_                     |
| `#type/disambiguation`    | **Clarifications**                  | For terms/concepts with multiple meanings   | _Islam (religion vs political movement)_                         |
| `#type/timeline`          | **Chronologies**                    | Event sequences                             | _Timeline of Prophet Muhammad's Battles_                         |
| `#type/faq`               | **Answer Repository**               | For popular questions and quick refutations | _FAQ: Why did Prophet Muhammad ﷺ marry Aisha (RA)?_              |
| `#type/scholarly-opinion` | **Ikhtilaf and Fiqhi Views**        | Where madhahib differ                       | _Scholarly Views on Apostasy Punishment_                         |
| `#type/movement`          | **Religious/Social Movements**      | Groups and ideologies                       | _Deobandi Movement_, _Muslim Brotherhood_                        |
| `#type/location`          | **Places**                          | Geographical notes                          | _Makkah_, _Madinah_, _Baghdad_                                   |
| `#type/definition`        | **Lisan al-Arab Style Definitions** | Linguistic or Islamic meanings              | _Definition: Ijma'_, _Definition: Jahiliyyah_                    |
| `#type/criticism`         | **Critique or Analysis**            | Attacks against Islam (to be refuted)       | _Criticism: Child Marriage Accusation_                           |

## File Naming Convention (Concise, Machine-Friendly)

For [[Qur'an]] verses/refutations/mentions

```txt
quran-<chapter>-<verse>-<slug>
```