# GitHub上傳指南

以下是將工資計算程式架構文件上傳到GitHub的步驟：

## 1. 創建新的GitHub倉庫

1. 登錄到您的GitHub帳戶
2. 點擊右上角的"+"圖標，然後選擇"New repository"
3. 在"Repository name"欄位中輸入一個名稱，例如"salary-program-structure"
4. 可以選擇添加描述："工資計算程式架構展示"
5. 選擇"Public"（公開）或"Private"（私有）
6. 不要勾選"Initialize this repository with a README"
7. 點擊"Create repository"按鈕

## 2. 上傳文件到GitHub

### 方法一：使用GitHub網頁界面上傳

1. 在新創建的倉庫頁面，點擊"uploading an existing file"鏈接
2. 將`salary-program-structure.zip`解壓縮到本地文件夾
3. 拖放解壓後的文件到GitHub上傳區域，或點擊"choose your files"選擇文件
4. 在"Commit changes"部分，添加提交信息："初始提交：添加工資計算程式架構文件"
5. 點擊"Commit changes"按鈕

### 方法二：使用Git命令行（如果您熟悉Git）

```bash
# 克隆新創建的倉庫
git clone https://github.com/您的用戶名/salary-program-structure.git

# 解壓縮文件到倉庫目錄
# 將解壓後的文件複製到倉庫目錄中

# 進入倉庫目錄
cd salary-program-structure

# 添加所有文件
git add .

# 提交更改
git commit -m "初始提交：添加工資計算程式架構文件"

# 推送到GitHub
git push origin main
```

## 3. 啟用GitHub Pages（可選，用於在線查看HTML頁面）

1. 在倉庫頁面，點擊"Settings"
2. 在左側菜單中，點擊"Pages"
3. 在"Source"部分，選擇"main"分支
4. 點擊"Save"按鈕
5. 等待幾分鐘，您的頁面將在以下URL可用：`https://您的用戶名.github.io/salary-program-structure/program_structure.html`

## 注意事項

- 確保音頻文件`tts_這個工資計_20250421_210258.mp3`與HTML文件在同一目錄中
- HTML文件中的音頻路徑已修改為相對路徑`./tts_這個工資計_20250421_210258.mp3`，確保在GitHub Pages上能正確播放
- 如果您啟用了GitHub Pages，請等待幾分鐘後再訪問頁面，因為部署需要一些時間
