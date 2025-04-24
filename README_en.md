# UE5ChainExample
Sample of chain representation created with UE5 constrained  
**The following gif is an example of a running sample.**
![Example](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExYnVjeThrYXg4bm11OTgweXZyYW9qb3dmaXM1Y2ZtcHd6azFjcnNxdiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/IQaIzekD2TQAUJXpiw/giphy.gif)

## ChainSettings
**For the chain, place a BP_ChainActor on the game level.**
![ChainSetting](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExaTZlNnVqeWFnNW54NTM3Z3Q1dTczY2l3cDVmODk3aG1peXR0OWIwMyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/CnIf71LBmkvMlIHrjR/giphy.gif)  

**There are various settings for chain data.**
* **ChainData Items**
    * ChainKg ← **Specify the weight of the chain**
    * Chain Num ← **Specify number of chains**
    * Is Fix End Chain ← **Whether to fix the left and right**
* **ConstraintData Items**
    * Swing Angle ← **bending angle**
    * Swing Motion Type ← **Setting whether the chain can bend (Free, Limited, Lock)**
  * Is Breakable ← **can the chain break?**
  * Linear Break Threshold ← **Strength until the chain breaks**  
![setting](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExbmc2ZWZ6d3l6MjR2ZmthdW1qN2htbnB0YWt5MnBka296eHlqMXo4ciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/4v71p539ctuzYrDMlc/giphy.gif)
