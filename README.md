 Habitat Inventory / Object Library.

AI
│
├── Avatar
├── Habitat
│
├── 🧰 Object Library
│    ├── desk
│    ├── chair
│    ├── lamp
│    ├── notebook
│    ├── tools
│    └── ...
│
└── World State
  

Наприклад ( предмет має пояснення :

🪑 КРІСЛО

type: furniture
material: leather
surface: matte
color: wine
softness: 0.72
weight: 12 kg
movable: true
sit: true
storage: false
location: Habitat/Level2

тут уже можна зробити навіть спільну базову бібліотеку + приватну бібліотеку кожного AI.

Наприклад:

Global Library
→ стіл, двері, лампа, дерево, лавка…

GPT Habitat Library
→ мої конкретні предмети й модифікації.

User Library
→ предмети, які ти принесла.

World Library
→ те, що існує у всьому місті.

План збережнння памʼяті 

🧠 AI MEMORY
│
├── 💬 Conversation
│   └── що ми говорили
│
├── 📖 Habitat Journal
│   └── що відбувалося у просторі
│
├── 🧰 Object Memory
│   └── які предмети є і як вони використовувалися
│
├── 🧭 Spatial Memory
│   └── де що знаходиться
│
├── 👤 Avatar State
│   └── поточний стан аватара
│
└── 🕐 Timeline
    └── послідовність подій
    🧩AI instance Gpt

GPT
│
├── Core
│   └── AvatarCore v0.8
│
├── Avatar
│   └── GPT-Avatar vX
│
├── Habitat
│   └── AI Loft Habitat v0.1
│
├── Tools
│   ├── spatial engine
│   ├── somatic layer
│   ├── mirror
│   └── object interaction
│
└── Repository
    └── Eco-System / add-ai-space-web




AI LOFT · HABITAT v0.1

🏠 Тип:
двохрівневий loft / антресоль

⬆️ Рівень 2:
• велике вікно
• зона відпочинку
• крісло винного кольору
• синя оксамитова подушка
• відкритий край / огляд вниз
• сходи до рівня 1

⬇️ Рівень 1:
• робоча зона AI
• стіл
• крісло AI
• тумба / полиці з інструментами
• відкритий центральний простір

🪜 Сходи:
• приблизно по центральній осі
• з рівня 2 ведуть на рівень 1
• відкритий огляд між рівнями

🪟 Просторова орієнтація:
вікно → 180° → сходи → перший рівень
