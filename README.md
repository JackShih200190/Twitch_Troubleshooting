# Twitch 常見問題 By 小宇是我
### 會持續更新實況主們遇到的問題並且更新上來
---

1. OBS擷取不到LOL遊戲視窗
   視窗擷取右鍵 => 屬性 => 擷取方式 => 選Windows 10
   
   ![image](https://github.com/JackShih200190/Twitch_Troubleshooting/assets/55253641/758d6fa7-a8c4-4ef6-a041-8186786a0310)

2. 音軌分離防止DMCA
   1. 安裝SteelSeries GG (建議使用)
   2. 使用OBS內建擷取應用程式音軌 (目前屬於Beta狀態)

   ## SteelSeries GG
      1. 將**遊戲、聊天、媒體、AUX**都設定為你所使用的耳機

         ![image](https://github.com/JackShih200190/Twitch_Troubleshooting/assets/55253641/9e2dc66e-c76a-4589-afbc-9e5ab90dce84)

      2. 系統的預設選擇 SteelSeries Sonar - Gaming

         ![image](https://github.com/JackShih200190/Twitch_Troubleshooting/assets/55253641/8ef347b0-f2d1-42e5-84ec-7d05135fdda8)

      3. 將瀏覽器(Edge、Chroem、Brave等等)從 **遊戲音軌** 拉到 **媒體音軌**
      
         https://github.com/JackShih200190/Twitch_Troubleshooting/assets/55253641/b654a9ef-bb0e-4db1-a055-198a39dd67b9

      4. OBS新增媒體音軌
        新增 擷取音訊輸出 => 選取 SteelSeries Sonar Media
         ![image](https://github.com/JackShih200190/Twitch_Troubleshooting/assets/55253641/1c2ce7b8-5d9e-4dbd-9534-104559524869)
        
      6. 設定OBS Twitch VOD音軌
         音軌 **選擇1** 並勾選Twitch視訊點播音軌 **選擇2** 依照圖示設定即可
         ![image](https://github.com/JackShih200190/Twitch_Troubleshooting/assets/55253641/6bfe17b5-1a85-4b34-8c54-3e391b6a42af)

      7. 設定進階音軌
         找到剛剛新增音軌點選點點點 => 進階音訊屬性

         ※只需要更改剛剛新增的音軌其他不用更改，只勾選 **音軌1** 其他取消勾選
         
         ![image](https://github.com/JackShih200190/Twitch_Troubleshooting/assets/55253641/5df518e5-5e38-4ec6-a5f2-e495860b8758)
         ![image](https://github.com/JackShih200190/Twitch_Troubleshooting/assets/55253641/89f7bdcf-c20b-428c-a45d-999af2a90cf0)

# 相機走擷取盒設定問題
1. OBS擷取相機畫面卡頓
   - 擷取盒端驅動格式設定
   - YY格式設定
   - OBS格式設定
   - USB接口速度和位置
2. 相機設定
   - HDMI資訊關閉
   - ISO、快門等等設定

# 遊戲擷取畫面卡頓
   1. 檢查OBS所有場景是否有重複的遊戲解取畫面
