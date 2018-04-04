# python——第六章_字典_01

标签（空格分隔）： 未分类

---
```
alien_0 = {'color':'green', 'points': 5}

print(alien_0['color'])
print(alien_0['points'])

new_points = alien_0['points']
print("You just earned " + str(new_points) + " points!")

print(alien_0)

alien_0['x_position'] = 0
alien_0['y_position'] = 25
print(alien_0)
```
字典是一种动态结构，里面包含键-值对，一个键对应一个值，与键相关联的值可以是*数字、字符串、列表甚至是字典*，键-值对数量可以有无数个，可以随时添加新的键-值对。
键值对之间由“，”分隔；键和值之间由“：”分隔；最外一层用花括号“{}”。
