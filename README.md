## python版本
3.10.X

## How to Execute Source Code 透過原始碼的執行方法

<details>
<summary><code><b>透過原始碼的執行方法</b>（點我展開）</code></summary>


### Step 1: 取得 source code:

```bash
git clone https://github.com/max32002/tixcraft_bot.git
```

### Step 2: 進入 clone 的資料夾: tixcraft_bot:

```bash
cd tixcraft_bot
```

### Step 3: 安裝第三方套件:

```bash
python -m pip install -r requirement.txt
```

### Step 4: 執行設定介面主桯式:

```bash
python settings.py
```

- 如果不使用設定介面，直接執行主程式:

```bash
python chrome_tixcraft.py
```

- 如果不使用設定介面，直接執行主程式並套用特定的設定檔:

```bash
python chrome_tixcraft.py --input settings.json
```

</details>

## File Description 檔案說明
主要的檔案說明:
- chrome_tixcraft.py : 主程式，用來自動化網頁的操作，使用元件是 selenium。
- nodriver_tixcraft.py : 也是主程式，用來自動化網頁的操作，使用的元件是 nodriver。
- settings.py : 編輯 settings.json 的 GUI 介面。提供圖片 OCR 功能給 chrome 擴充功能。支援定時啟用/停用 Bot。
- settings_old.py : 舊版本的編輯 settings.json 的 GUI 介面，與 settings.py 的差別在介面一個是網頁形式，old 的用的是視窗形式。
- config_launcher.py : 設定檔管理, 方便對多個設定檔案。

