---
layout: post
author: 白磷
title: Cocos2d Helloworld
---
[返回](./list)

```python
import cocos


class HelloWorld(cocos.layer.Layer):
    def __init__(self):
        super(HelloWorld, self).__init__()
        label = cocos.text.Label(
            "HelloWorld",
            font_name="\xE6\xA8\x99\xE6\xA5\xB7\xE9\xAB\x94\x20\xE6\xA8\x99\xE6\xBA\x96",
            font_size=32,
            anchor_x="center",
            anchor_y="center",
        )
        label.position = 320, 240
        self.add(label)


cocos.director.director.init()
main_scene = cocos.scene.Scene(HelloWorld())
cocos.director.director.run(main_scene)
```