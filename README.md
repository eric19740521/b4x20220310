# b4x20220310
B4X實驗: 如何 ?? 製作CustomView可視元件Lib (B4J/B4A/B4I)
B4X實驗: 如何 ?? 製作CustomView可視元件Lib (B4J/B4A/B4I)
參考資料:
https://www.b4x.com/guides/B4XCustomViews/?page=1

1.There are two CustomView types ==> 製作CustomView可視元件Lib (B4J/B4A/B4I)
CustomView     非跨平台?? (B4J/B4A/B4I)
CustomView (XUI) 跨平台?? (B4J/B4A/B4I)

2.
The only differences between CustomView and CustomView (XUI) templates are the declarations.
A.Standard
Private mBase As Panel 'ignore
Public Sub DesignerCreateView (Base As Panel, Lbl As Label, Props As Map)
B.XUI 
Private mBase As B4XView 'ignore
Public Sub DesignerCreateView (Base As Object, Lbl As Label, Props As Map) 


2.示範已經做好的jxyzButton/jxyzLabel.如何使用jxyzUI

使用jxyzUI 元件.設計模式/Code模式

字型大小/顯示的文字 都是內定的.可以自訂

3.示範如何製作 xyzUI


4.放到Lib目錄下面


https://github.com/eric19740521/b4x20220310

