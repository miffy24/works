# day one: JavaScript Drum Kit
实现模拟一个敲击的页面，用户在键盘上按下ASDFGHJKL这几个键时，页面上与字母对应的按钮变大变亮，对应鼓点的声音响起来。
## 关键要点：
1.键盘事件
2. 播放声音
3. 改变样式
## 遇到的问题，如何使页面恢复原状
利用`transitionend`事件，它在css transition结束后会被触发
