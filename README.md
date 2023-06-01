# OpenAI_Whisper_speech_recognition_colab
[![colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/f901107/OpenAI-Whisper-speech-recognition/blob/main/OpenAI_Whisper_speech_recognition_colab.ipynb)

OpenAI 的 Whisper 語音辨識
* 上傳檔案到 Google Drive ，檔案按右鍵"共用"->選一般存取權->選"知道連結的任何人"->點下方複製連結，將連結貼到程式的「url」欄位中執行程式即可辨識語音檔按轉成文字或字幕檔。
* 支援檔案格式: 影片(mp4)、音檔(mp3、m4a、wav) 的連結、讀取.txt檔(多個檔案連結)、YouTube 影片分享連結、YouTube撥放列表連結。
* 可自訂字幕檔要儲存的資料夾。
* 可自訂是否要跳過已辨識過的。
* yt-dlp 下載影音檔案。

<br> OpenaAI 的 Whisper 是一個自動語音辨識系統，而且有開源，可以在底下的網址中找到:https://github.com/openai/whisper 結合 Whisper 和 yt-dlp 的工具，就可以將 Youtube 上的影片或播放清單擷取聲音、儲存語音檔後，進行語音辨識，並生成字幕檔。</br>
<br> 目前在後面程式設定區塊中，語音來源路徑的「url」欄位中，可以填入 Youtube 的影片或影片清單網址。接著將其它選項都設定好後，就可以在[程式區塊]中按「執行」的按鈕，開始進行語音辨識了。</br>
<br> Whisper 可辨識中英夾雜、臺語，語言代碼「lang」的欄位要選「Chinese」，如果用「自動判斷」，有時會被當成非中文，而無法辨識出文字。程式第一次執行時，因為要安裝及下載自動語音辨識所需要的資料，可能要稍等一下下。</br>
