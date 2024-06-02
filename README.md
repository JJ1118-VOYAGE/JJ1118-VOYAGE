# 项目介绍
    这是一个五子棋的程序，包含：界面实现，棋型评估函数实现，极大极小值搜索和alpha beta剪枝，启发式评估四个部分
 
# 环境依赖
    使用了三个py文件，分别是主文件main.py, ChessAI.py, GameMap.py
    需要的环境有：
    
    import pygame
    from pygame.locals import *
    from enum import IntEnum
    from random import randint
    import time

    五子棋的界面比较简单，使用pygame实现界面
    pygame.locals包含了很多常量，比如按键的名称、颜色的常量等。通过导入所有内容，你可以直接使用这些常量而不需要在代码中加上模块的前缀。
    导入了Python标准库中的IntEnum枚举类型。枚举类型用于创建具有特定值的符号名称，使得代码更易读和维护。
    导入了random模块中的randint函数。randint函数用于生成指定范围内的随机整数。
    导入了Python标准库中的time模块。time模块提供了与时间相关的函数，比如获取当前时间、暂停程序执行一段时间等功能。

# 文件环境
    GameMap.py：
        from enum import IntEnum
        import pygame
        from pygame.locals import *
    
    ChessAI.py：
        from GameMap import *
        from enum import IntEnum
        from random import randint
        import time

    main.py ：
        import pygame
        from pygame.locals import *
        from GameMap import *
        from ChessAI import *
    
   



 
 
 
 

