# 簡易電子琴

## 主要功能

透過呼叫 Windows 系統底層 API (kernel32.dll 的 Beep 函式)，精準發出從中央 C (Do, 523Hz) 到高音 C (高音 Do, 1046Hz) 的標準音階頻率，同時具備「動態自適應縮放」功能，琴鍵大小會跟隨視窗尺寸自動等比例調整。

## 使用方法

1.透過白色button與黑色label模擬出琴鍵外觀，下方標示對應的唱名（Do、Re、Mi、Fa、Sol、La、Si、高音 Do），方便使用者辨識音階位置

<img width="700" height="200" alt="image" src="https://github.com/user-attachments/assets/3caa0f36-4690-45a1-8a53-166dcf47a8ae" />
<br>

2.滑鼠點擊白色琴鍵按鈕，系統便會發出對應音高、長度為 300 毫秒的電子音。

3.支援視窗動態縮放，使用者可按住視窗邊緣並拖曳，放大或縮小視窗，琴鍵與排版會根據長寬比例自動重新計算並等比縮放，為避免變形有限制最大與最小縮放範圍

- 最小： 380 * 100

<img width="380" height="100" alt="image" src="https://github.com/user-attachments/assets/b0e581a7-1de0-4a92-aec3-b839266cc537" />
<br>

- 最大： 1000 * 500

<img width="1000" height="500" alt="image" src="https://github.com/user-attachments/assets/ffb1446b-31bd-400d-bc65-9a4268f1492b" />




