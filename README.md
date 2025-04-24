# UE5ChainExample
Sample of chain representation created with UE5 constrained  
こちらはUE5でコンストレインを用いて作った鎖のサンプルになります。

**The following gif is an example of a running sample.**  
**下記Gifは実際のサンプルを動かした例になります。**  
![Example](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExYnVjeThrYXg4bm11OTgweXZyYW9qb3dmaXM1Y2ZtcHd6azFjcnNxdiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/IQaIzekD2TQAUJXpiw/giphy.gif)

## 鎖の設定について
鎖については**BP_ChainActorをゲームレベル上に配置する形**になります。  
![ChainSetting](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExaTZlNnVqeWFnNW54NTM3Z3Q1dTczY2l3cDVmODk3aG1peXR0OWIwMyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/CnIf71LBmkvMlIHrjR/giphy.gif)  

**鎖のデータをについては各種設定設定項目があります。**  
* **ChainData項目**  
  * ChainKg ← **鎖の重さを指定**  
  * Chain Num ← **鎖の数を指定**  
  * Is Fix End Chain ← **左右を固定するかどうか**
* **ConstraintData項目**
  * Swing Angle ← **曲がる角度**
  * Swing Motion Type ← **角度がまがるかどうか(Free・Limited・Lock)**　　
  * Is Breakable ← **鎖が切れるかどうか**
  * Linear Break Threshold ← **鎖が切れるまでの強度**  
![setting](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExbmc2ZWZ6d3l6MjR2ZmthdW1qN2htbnB0YWt5MnBka296eHlqMXo4ciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/4v71p539ctuzYrDMlc/giphy.gif)
