# 简 

作者开发软件滴:https://www.coolapk.com/apk/nico.styTool


1.http://jingyan.baidu.com/article/2a13832890d08f074a134ff0.html(请从第二步看)

2.导入:  import nico.my.StatusBarUtil;


# 状态栏白色（图标，文字）


StatusBarUtil.Bar(Activity activity);


?=StatusBarUtil.Bar(this);


# 状态栏(颜色自己选择)（图标，文字)


StatusBarUtil.Ba(Activity activity);


?=StatusBarUtil.Ba(this);


# 设置状态栏颜色


StatusBarUtil.Bd(Activity activity,int color);


?=StatusBarUtil.Bd(this,getResources().getColor(R.color.white_nico));
