# StatusBar

##### 整理自:
1. [白底黑字！Android浅色状态栏黑色字体模式](https://www.jianshu.com/p/7f5a9969be53)
2. [魅族官网——状态栏变色](http://open-wiki.flyme.cn/index.php?title=状态栏变色)
3. [Android判断系统是不是Flyme、EMUI、MIUI](https://blog.csdn.net/u014651216/article/details/72780747)

##### 第三方库:
1. [SystemBarTint](https://github.com/jgilfelt/SystemBarTint)

##### 使用方法:
```java
public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        StatusBarUtil.StatusBarLightMode(this);
        StatusBarUtil.setStatusBarColor(this, android.R.color.white);
        setContentView(R.layout.activity_main);
    }
}
```
```xml
android:fitsSystemWindows="true"
```
