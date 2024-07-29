Puzzle Game
项目简介 (Project Introduction)
这是一款简单的拼图游戏。玩家需要通过键盘方向键来移动图片碎片，将打乱的图片还原成原始状态。游戏支持不同的图片主题，可以在动物、女孩、运动图片之间随机切换。

This is a simple puzzle game. Players need to move the picture pieces with the arrow keys to restore the scrambled picture to its original state. The game supports different image themes and can randomly switch between animal, girl, and sports pictures.

特性 (Features)
随机打乱的拼图 (Randomly scrambled puzzle)
图片主题切换（动物、女孩、运动） (Image theme switching: Animal, Girl, Sports)
胜利检测 (Victory detection)
步数统计 (Step counter)
开始 (Getting Started)
先决条件 (Prerequisites)
Java JDK 1.8 或以上 (Java JDK 1.8 or above)
任意IDE（如 IntelliJ IDEA, Eclipse） (Any IDE such as IntelliJ IDEA, Eclipse)
安装 (Installation)
克隆这个仓库 (Clone this repository)

bash
复制代码
git clone https://github.com/yourusername/puzzle-game.git
打开项目并运行 GameJFrame 类 (Open the project and run the GameJFrame class)

使用说明 (Usage)
运行游戏后，使用键盘方向键移动图片块。 (After running the game, use the arrow keys to move the picture pieces.)
在菜单栏中，可以选择不同的图片主题进行切换。 (In the menu bar, you can select different image themes to switch.)
按键操作 (Key Controls)
上键 (↑): 向上移动图片块 (Move piece up)
下键 (↓): 向下移动图片块 (Move piece down)
左键 (←): 向左移动图片块 (Move piece left)
右键 (→): 向右移动图片块 (Move piece right)
A键: 显示完整图片 (Show complete picture)
W键: 重置拼图 (Reset puzzle)
开发 (Development)
文件结构 (File Structure)
arduino
复制代码
puzzle-game/
├── puzzlegame/
│   ├── image/
│   │   ├── animal/
│   │   ├── girl/
│   │   ├── sport/
│   ├── com_42ccode_com/
│   │   ├── GameJFrame.java
│   │   ├── LoginJFrame.java
├── README.md
└── .gitignore
图片资源 (Image Resources)
puzzlegame/image/animal/: 动物图片 (Animal images)
puzzlegame/image/girl/: 女孩图片 (Girl images)
puzzlegame/image/sport/: 运动图片 (Sport images)
贡献 (Contributing)
欢迎贡献！请遵循以下步骤进行贡献： (Contributions are welcome! Please follow these steps to contribute:)

Fork 本仓库 (Fork this repository)
创建一个新的分支 (Create a new branch)
bash
复制代码
git checkout -b feature/your-feature-name
提交你的更改 (Commit your changes)
bash
复制代码
git commit -m 'Add some feature'
推送到分支 (Push to the branch)
bash
复制代码
git push origin feature/your-feature-name
创建一个 Pull Request (Create a Pull Request)
许可证 (License)
该项目使用 MIT 许可证。 (This project is licensed under the MIT License.)