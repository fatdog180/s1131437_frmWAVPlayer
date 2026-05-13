# s1131437_frmWAVPlayer
A C# WinForms application for playing .wav audio files using the System.Media.

# WAV 音效檔播放器 (上課練習 3)

## 專案簡介
這是一個使用 C# Windows Forms 開發的簡易多媒體播放程式。主要練習 `System.Media.SoundPlayer` 類別的應用，可以讀取並控制 `.wav` 格式音效檔的播放狀態。

## 功能說明
* **瀏覽檔案**：使用 `OpenFileDialog` 選擇本機的 WAV 音效檔。
* **播放控制**：包含「播放一次」、「重複播放」(`PlayLooping()`) 以及「停止播放」(`Stop()`) 功能。
* **防呆機制**：點擊結束程式或關閉視窗時，會跳出 `MessageBox` 再次確認是否關閉。

## 執行說明
1. 下載原始碼後，使用 Visual Studio 開啟 `.sln` 方案檔。
2. 點擊「啟動」進行編譯與執行。
3. 點擊「瀏覽」選擇測試用的 WAV 檔案，即可測試各項播放功能。

## 執行畫面截圖
<img width="314" height="166" alt="螢幕擷取畫面 2026-05-13 072409" src="https://github.com/user-attachments/assets/75720fb1-8569-47e0-b65e-002fd82f311f" />
