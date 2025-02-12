# UnrealGhostFishingGame
 For TTK4854

 Project structure example:

GhostFishingGame/
├── Config/                 # Configuration files (engine, game settings)
├── Content/                # All game assets (textures, sprites, blueprints, levels)
│   ├── Blueprints/         # Gameplay logic (Blueprints)
│   ├── Sprites/            # 2D textures and sprite assets
│   ├── Tilemaps/           # Tilemap data if using tile-based graphics
│   ├── Audio/              # Sound effects and music
│   ├── UI/                 # Widgets, menus, HUD elements
│   ├── Materials/          # Materials for rendering sprites
│   ├── Levels/             # Game levels (if using levels instead of procedural generation)
│   └── Misc/               # Any extra assets (fonts, icons, etc.)
├── Plugins/                # Any additional plugins you add
├── Source/                 # C++ source code
│   ├── GhostFishingGame/   # Main game module
│   ├── GameModes/          # Game rules and logic
│   ├── Player/             # Player controller and pawn logic
│   ├── AI/                 # AI scripts (if any)
│   ├── ROV/                # ROV-specific movement and mechanics
│   ├── Items/              # Collectible fishing nets and upgrades
│   ├── UI/                 # C++ logic for the user interface (if not using only Blueprints)
│   └── ...                 # More gameplay-related code
├── Saved/                  # Autosaves, logs, and backups (ignored in Git)
├── Intermediate/           # Temporary build files (ignored in Git)
├── Binaries/               # Compiled binaries (ignored in Git)
├── .gitignore              # Git configuration (Unreal-specific)
├── GhostFishingGame.uproject  # The main Unreal project file
└── README.md               # Project documentation

