# 个人总结

1. #### HTML 5 Audio/Video 的使用

   - ##### currentTime属性

     > currentTime 属性设置或返回音频/视频播放的当前位置（以**秒**计）。
     > 当设置该属性时，播放会跳跃到指定的位置。

   - 方法

     > 播放 audio.play()  
     >  暂停 audio.pause()  

2. 如何使页面按钮恢复原状？

   > ​		利用一个叫 **transitionend** 的事件，它在 CSS transition 结束后会被触发。我们就可以利用这个事件，在每次打鼓的效果（尺寸变大、颜色变化）完成之后，去除相应样式。
   >
   > 在这个页面中，发生 transition 的样式属性不止一个（box-shadow, transform, border-color），所以需要添加一个判断语句，使每发生一次按键事件时，只去除一次样式。
   >

3. 要使用Date的实例获取时间

4. 使用贝塞尔曲线实现指针的抖动	

   ```
   transition: all 0.05s;
   transition-timing-function: cubic-bezier(0.1, 2.7, 0.58, 1)
   ```

5. 注意箭头函数的this指向问题

6. input事件：value变化就触发，change事件：value变化完才触发

7.  css设置模糊；用filter: blur(10px)

8. css使用变量`var(name)`

9. 获取html节点：使用:root

10. 

11. 

12. 

13. 