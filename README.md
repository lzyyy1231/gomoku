# gomoku
qhk's 大作业
1.基础部分（50分)
·实现最基础的PVP对战功能
1.1功能实现（30分)
1.能够正确判断对局输赢并结束游戏（30分）
1.2 游戏界面（10分)
1.有简单的游戏开始结束界面提示或计分板（5分)
2.用控制台界面通过各种符号实现五子棋游戏对局棋盘，通过键盘实现下棋操作（5分)
如果实现了图形化界面则该部分分数自动获得
1.3 功能完善（10分)
·异常处理：能够对程序运行过程中出现的各种异常进行提示和处理。（5分)
·例如提示操作越界、违规、存储信息的文件遭到破坏等)
2.进阶部分（50分)
该部分有多个得分点，按照要求实现即可获得对应的分数，但是总和不能超过50分。
2.1人机对战（35分)
1.在和人对弈时能够对弈至少20步（机器方步数）（15分)
2.实现不同难度的人机对战，根据机器方对战的策略进行打分（20分)
2.2 文件操作（15分)
·能够将已进行的对局信息存储到文件中，例如每一局的胜利方，用户在某一局中每一步棋的位置。
（5分)
·能够从文件中读取对局信息。（5分)
·能够将从文件中读取的信息以对局回放的形式展示出来。（5分)
2.3游戏界面（20分）
1.使用图片等图形化界面的形式来实现五子棋对局。（10分)
2.通过鼠标来控制棋子落点。（10分）
2.4 功能完善（15分)
1.数据持久化：通过结构化的数据格式来存储对局信息。（5分)
例如使用json、xml、cSv等格式存储信息。可以使用第三方库.
2.更完善的存储操作：可以存储多个对局的信息，实现对局信息的增删查功能。（10分)
2.5 工程化（10分)
·对项目进行合理的工程化，各个.h和.cpp文件职责清晰.
·使用适当的构建工具（如Makefile或CMake）进行项目的管理。
