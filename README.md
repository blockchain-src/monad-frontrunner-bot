# 🚀 运行 FastLane Frontrunner 机器人
<p align="center">
  <img src="frontrunner-gif.gif" alt="Frontrunner 游戏动画" width="600">
</p>

## 🔴适用于 linux 和 macOS 系统
### 首次安装/设置/运行
```bash
git clone https://github.com/blockchain-src/monad-frontrunner-bot.git && cd monad-frontrunner-bot
chmod +x run.sh && ./run.sh
```

### 后续运行
```bash
source venv/bin/activate && python3 play.py
```
---
## 🔴适用于 Windows 系统

请以管理员身份启动 PowerShell，依次执行以下命令：

```powershell
Set-ExecutionPolicy Bypass -Scope CurrentUser
git clone https://github.com/blockchain-src/monad-frontrunner-bot.git #确保你已经安装了git,才能执行此命令
cd monad-frontrunner-bot
.\run.ps1
```


## ⚠️ 注意事项

- 🔐 **确保私钥的安全性**，不要在公共场合暴露私钥。
- 💰 **确保账户余额足够支付 Gas 费用**，否则操作将失败。

---

