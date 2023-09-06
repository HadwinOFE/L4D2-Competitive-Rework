# **L4D2 Competitive Rework**

**注意事项** - **请勿忽视！**
* 本仓库的主要在 **Linux**上运行，特别是 Ubuntu/Debian
> 本仓库支持 Windows，但不是完全支持 Windows，当然，我们也欢迎您为兼容 Windows 的全面更新做出贡献！
* 本仓库仅支持 Sourcemod **1.11** 及以上版本

## **关于:**

这主要是一个针对 **Linux** 服务器上非常过时的 L4D2 比赛平台的改造项目
其中既包括旧版源码中无法实现的紧急修复，也包括将不兼容的过时文件更新为可用版本

> **内置的比赛模式:**
* **Zonemod 2.8.6**
* **Zonemod Hunters**
* **Zonemod Retro**
* **NeoMod 0.4a** 
* **NextMod 1.0.5**
* **Promod Elite 1.1**
* **Acemod Revamped 1.2**
* **Equilibrium 3.0c**
* **Apex 1.1.2**

---

## **重要说明**
* 我们在 Server.cfg 中添加了 "**mv_maxplayers**"，用于替换 sv_maxplayers，以防止每次更改地图时都被覆盖
  * 卸载config时，该值将与 Server.cfg 中使用的值一致
* 每个 Confogl matchmode 都将执行两个附加文件，即 "**sharedplugins.cfg**"和 "**generalfixes.cfg**"，这两个文件位于**left4dead2/cfg**文件夹中。
  * "**General Fixes**" 只是确保每个比赛模式都能加载此处关于BUG的修复
  * "**Shared Plugins**" 是为你-服务器主机-准备的，您肯定希望在每种比赛模式下始终加载一些插件，您可以在这里添加
    * **注意:** 插件加载的锁定和解锁不再由Config本身处理，因此如果使用此项目，**请不要**在手动添加的configs中定义插件加载的锁定/解锁

---
	
## **鸣谢:**

> **基础/高级工作:**
* A1m`
* AlliedModders LLC.
* "Confogl Team"
* Dr!fter
* Forgetest
* Jahze
* Lux
* Prodigysim
* Silvers
* XutaxKamay
* Visor

> **附加插件/扩展:**
* Accelerator74
* 
* Arti 
* AtomicStryker 
* Backwards
* BHaType
* Blade 
* Buster
* Canadarox 
* CircleSquared 
* Darkid 
* DarkNoghri
* Dcx 
* Devilesk
* Die Teetasse 
* Disawar1 
* Don 
* Dragokas
* Dr. Gregory House
* Epilimic 
* Estoopi 
* Griffin 
* Harry Potter
* Jacob 
* Luckylock 
* Madcap
* Mr. Zero
* Nielsen
* Powerlord
* Rena
* Sheo
* Sir
* Spoon
* Stabby 
* Step 
* Tabun
* Target
* TheTrick
* V10 
* Vintik
* VoiDeD
* xoxo
* $atanic $pirit


> **比赛地图重绘:**
* Derpduck

> **测试/问题报告:**
* 太多了，无法一一列举，请继续努力报告问题！

**注意:** 如果您的作品被使用，而我忘记注明，我表示诚挚的歉意。 
我已尽力将名单上的每个人都包括在内，您只需提一个issue并命名您**制作/贡献**的**插件/扩展**，我就会确保将您的名字正确记入名单
