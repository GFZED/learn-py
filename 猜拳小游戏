import random   # 导入随机工具包
player = int(input("请输入您要出的拳 石头（1）/剪刀（2）/布（3） ： "))   # 玩家出拳
computer = random.randint(1,3)   # 电脑随机返回1到三之间的整数，包含1和3
'''获胜条件：石头赢剪刀，剪刀赢布，布赢石头'''
if ((player == 1 and computer == 2)
        or (player == 2 and computer == 3)
        or (player == 3 and computer == 1)):
    print("you got win!")
elif player == computer:
    print("you are the same?do it again!")
else:
    print("unh!you lost the game!")
