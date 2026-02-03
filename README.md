# AIx-24: Ғарыштық миссияны басқарудың өзін-өзі қалпына келтіретін интеллектуалдық жүйесін әзірлеу
# AIx-24: Development of a self-healing intelligent system for autonomous space mission management
> **Project for AEROO SPACE AI COMPETITION 2026**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![AI-Model: Reinforcement Learning](https://img.shields.io/badge/AI-Reinforcement%20Learning-green.svg)]()

## 🛰️ Жобаға шолу / Project Overview

**KZ:** "AIx-24 Space AI" — бұл критикалық жағдайларда спутниктің жұмысқа қабілеттілігін автономды түрде қалпына келтіруге қабілетті интеллектуалды басқару жүйесі. Жүйе **Reinforcement Learning (Q-Learning)** алгоритмін қолдана отырып, ресурстарды оңтайландыру бойынша қауіпсіз шешімдерді бірден қабылдайды.

**EN:** AIx-24 Space AI is an intelligent spacecraft control system capable of autonomously restoring satellite functionality in critical environments. Using **Reinforcement Learning (Q-Learning)**, the system makes instantaneous resource optimization decisions to ensure mission continuity.

---

## ⚡ Мәселе және Шешім / Problem & Solution

| Мәселе (Problem) | Шешім (Solution - AIx-24) |
| :--- | :--- |
| **Энергия деградациясы:** Пиктік жүктеме кезінде қуаттың жоғалуы. | ЖИ модульдер арасында тұтыну лимиттерін динамикалық түрде қайта бөледі. |
| **Термиялық тұрақсыздық:** Қызып кету жүйенің істен шығуына әкеледі. | Салқындату жүйелерін автоматты түрде қосу немесе Safe Mode-қа көшу. |
| **Сигналдың кешігуі (Latency):** Жерден басқару тым ұзақ уақыт алады. | Толық автономдық — шешім бортта миллисекундтар ішінде қабылданады. |

---

## 🧠 Техникалық іске асыру / AI Approach

**KZ:** Жүйе **Reinforcement Learning (RL)** негізінде жұмыс істейді:
* **Агент күйі (State):** `[Энергия деңгейі, Температура, Жүйе күйі]`.
* **Әрекеттер (Actions):** `[Күту, Жүктемені өшіру, Салқындатуды қосу, Энергияны қайта бөлу]`.
* **Марапаттау функциясы (Reward):** Агент миссияны мүмкіндігінше ұзақ әрі тұрақты ұстауға үйретілген.

**EN:** The system is based on **Reinforcement Learning (RL)** principles:
* **Agent State:** `[Energy Level, Temperature, System Health]`.
* **Action Space:** `[Idle, Payload Shutdown, Cooling On, Energy Redistribution]`.
* **Reward Function:** The agent is trained to maintain mission stability for as long as possible through a penalty/reward system.

---

## 💼 Бизнес-модель / Startup Component

**KZ:** Біздің өнім спутниктік операторлар мен ғарыш агенттіктеріне арналған **B2B Software-as-a-Service (SaaS)** ретінде позицияланады.
* **Құндылығы:** Құны 500 мың доллардан 100 млн долларға дейінгі аппаратты жоғалту қаупін азайту.
* **Монетизация:** Әрбір ұшырылған аппаратқа лицензия сату.

**EN:** Our product is positioned as a **B2B SaaS** solution for satellite operators and space agencies.
* **Value Proposition:** Reducing the risk of losing assets valued from $500k to $100M+.
* **Monetization:** Software licensing per deployed satellite + customization services.

---

## 📊 Нәтижелер / Results
* **Battery Life:** +35% (критикалық режимде).
* **Thermal Safety:** Қызып кету жағдайлары 50%-ға азайды.

---

## 🚀 Іске қосу нұсқаулығы / Installation & Launch
1. **Репозиторийді клондау:** `git clone https://github.com/AIx-24/AIx-24-Space-AI.git`
2. **Кітапханаларды орнату:** `pip install -r requirements.txt`
3. **Симуляцияны бастау:** `space_ai.ipynb` файлын ашып, барлық ячейкаларды орындаңыз.

---

## 👥 Команда / Team AIx-24
* **Beibit Marlen** — AI Engineer / Lead Developer
* **Saulethanuly Darkhan** — Business Analyst / Space Systems Architect
* **Lyceum 24, Taldykorgan, Jetisu region**
