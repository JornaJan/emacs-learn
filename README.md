# Emacs Learn

### 安装 Emacs
`brew install --cask emacs`

进入Emacs
![Emacs 初始化界面](./pics/1.jpg)

在使用Emacs之前 需要解决Mac按键冲突问题

- Meta 映射问题 
![Emacs Meta按键映射修改按键](./pics/2.jpg)

- Mac输入法切换需要使用Ctrl+Space Emacs需要使用Ctrl+Space做映射 
![Emacs Ctrl+Space按键映射修改按键 只需要取消勾选选项](./pics/3.jpg)

# 基本操作常用按键

**组合按键**
- C (Ctrl) eg: C-n 指的是 Ctrl+n 光标向下移动
- M (Alt) Mac中映射为option eg: M-x 指的是 Meta+x 命令扩展 在Mac中可使用 option+x
- S (Shift)

#### 光标移动

- C-n 向下一行
- C-p 向上一行
- C-f 向右移动一个字符
- C-b 向左移动一个字符
- M-f 将光标右移一个单词
- M-b 将光标左移一个单词
- C-a 回到行首位
- C-e 回到行尾
- M-< 回到顶部
- M-> 回到底部
- C-v 向下翻屏
- M-v 向上翻屏
- C-l 将光标所在行移动到屏幕中央
- M-m 将光标移动到行首的第一个非空白字符

#### 查找和替换操作

- C-s 向前查找
- C-r 向后查找
- C-M-s 向前正则查找
- C-M-r 向后正则查找
- M-% 查找并替换 （y表示替换并跳到下一个 n表示忽略并跳到下一个 q表示结束 !表示替换全部）

#### 文本选择操作

- C-Spc-e 选中从当前位置到行尾的文本
- C-Spc-a 选中从当前位置到行首的文本
- C-Spc-n 从当前位置开始往下选中的文本
- C-Spc-p 从当前位置开始往上选中的文本
- C-Spc-f 从当前位置开始往右选中一个字符
- C-Spc-b 从当前位置开始往左选中一个字符
- M-Shift-f 从当前位置往右选中一个单词
- M-Shift-b 从当前位置往左选中一个单词
- M-Shift-e 选中从当前位置开始到当前句尾的文本
- M-Shift-a 选中从当前位置开始到行首的文本
- C-Spc-v 向下选中一屏
- M-Shift-v 向上选中一屏
- C-x h 全选整个屏幕
