### 铁驭护盾

> [!NOTE|style:flat|label:Note]
> 铁驭护盾使用和参考了[VoyageDB](https://github.com/DBmaoha)的[Bleedout模式](https://github.com/DBmaoha/Super.Mixed.Game/blob/main/mod/scripts/vscripts/modifiers/modifier_bleedout.gnut)和[铁驭护盾电池](https://github.com/DBmaoha/Super.Mixed.Game/blob/main/mod/scripts/vscripts/pilotutil/pilot_shield_battery.gnut)的大部分代码，非常感谢！

铁驭现在拥有一个血量为100的护盾

> 参考Apex！

**登入你的泰坦**或者**使用电池**都可以恢复你的护盾

绿色池的使用时间为1.0秒<br/>
黄电池的使用时间为1.5秒

> [!WARNING|style:flat|label:Warning]
> 护盾会将**溢出的伤害继承给铁驭**<br/>
> 即为：当你受到了一次**大于护盾剩余生命值的伤害**，护盾在消耗破碎后**剩余的伤害会被直接继承到铁驭**上并导致铁驭受伤或死亡

> [!ATTENTION|style:flat|label:Attention]
> 电子烟类伤害会**绕过护盾额外对铁驭本体造成50%伤害**<br/>
> 电弧手榴弹和电浆爆破弹会直接**摧毁护盾**

> [!TIP|style:flat|label:Tips]
> 电池不仅可以在`GUI菜单`中使用，还可以直接长按`强化键（默认为C）`使用

> [!NOTE|style:flat|label:Note]
> 如果找不到该按键可以去看 **设置** - **按键对应** 内的`启用强化`绑定的是什么按键