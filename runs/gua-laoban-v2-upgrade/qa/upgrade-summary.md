# 瓜老板 v2 动作升级

本次升级保留 idle 和 16 方向 look rows，重做了：

- running-right / running-left：固定脚底基线与帧内安全边界，修复脚出界和串帧。
- waving：转身挑瓜。
- failed：切开生瓜后崩溃。
- waiting：敲瓜、贴耳听声、等待确认。
- running：电子秤称瓜，底部带磁铁。
- review：贴近西瓜严肃复核。

独立视觉 QA：pass。

保留警告：旧 look rows 的部分对角线方向属于轻微提示不足；最终方向检查确认基准方向、象限和循环语义正确。连续性指标中的局部异常没有对应可见的轮廓断裂或道具脱离。
