---
layout: post
title: BorderLayout按钮布局
date: 2020-03-02
tag: JAVA
---
 JAVA 窗体程序 BorderLayout按钮布局
### BorderLayout按钮布局
>*1.继承JFrame		

>*2.导入包	

>*3.定义需要的组件	
	
>*4.添加组件

>*5.设置窗体组件
### 完整程序

	/*
	 * BorderLayout按钮布局
	 * 过程
 	* 1.继承JFrame
 	* 2.导入包
 	* 3.定义需要的组件
 	* 4.添加组件
 	* 5.设置窗体组件
 	*/
	import java.awt.*;

	import javax.swing.*;
	public class Demo8_2 extends JFrame{
	//定义组件
	JButton jb1,jb2,jb3,jb4,jb5;
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Demo8_2 w=new Demo8_2();
	}
	public Demo8_2(){
		//创建组件
		jb1=new JButton("中部");
		jb2=new JButton("北部");
		jb3=new JButton("东部");
		jb4=new JButton("南部");
		jb5=new JButton("西部");
		//添加组件
		this.add(jb1,BorderLayout.CENTER);
		this.add(jb2,BorderLayout.NORTH);
		this.add(jb3,BorderLayout.EAST);
		this.add(jb4,BorderLayout.SOUTH);
		this.add(jb5,BorderLayout.WEST);
		//5.设置窗体组件
		this.setTitle("边界布局-IM大朋友");
		this.setSize(600,400);
		
		//设置窗口的初始位置
		this.setLocation(700,400);
		//设置默认的关闭操作是真正关闭（退出虚拟机）
		this.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		//使窗口显示出来
		this.setVisible(true);
		}

	}

![](/images/posts/tfimg/xck2.png)
<br>
转载请注明：[im大朋友的博客](https://jing-hua.github.io/) » [BorderLayout按钮布局](https://jing-hua.github.io/)  » [长按我分享复制链接](https://jing-hua.github.io/)  


