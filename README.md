# UE5ChainExample
こちらはUE5でコンストレインを用いて作った鎖のサンプルになります。

**The following gif is an example of a running sample.**  
**下記Gifは実際のサンプルを動かした例になります。**  
![Example](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExN3ByYmpidDY2ZW11dXRmYWNwenFrdHVmem9oaGl1M2RmaTF5bm9vMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/5SN7weNIusY1TLCkwo/giphy.gif)

## 鎖の設定について
鎖については**BP_ChainActorをゲームレベル上に配置する形**になります。  
![ChainSetting](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExYWFyNThtZmszeWFxd3cyZDk4cjI5OWVsbHpidjh5OWN0dWppNGsxNiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/g3hXHkxrUVCpXHwOoQ/giphy.gif)  

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

![Chainsettings](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExcm14MWNkbGJueWh0ZnNlcGQzM29ncTR4aWU1YWdqZWg5dHJsbmlkOSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/4HFdxSyyvQnkUK9QJw/giphy.gif)
