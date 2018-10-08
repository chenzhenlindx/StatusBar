# StatusBar

整理自:[白底黑字！Android浅色状态栏黑色字体模式](https://www.jianshu.com/p/7f5a9969be53)

第三方库:[SystemBarTint](https://github.com/jgilfelt/SystemBarTint)

使用方法:
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