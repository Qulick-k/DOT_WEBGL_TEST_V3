DOT放到WebGL無法顯示實體
看起來DOT沒支援網頁版著色器，需要再自己做著色器。

資料>https://forum.unity.com/threads/dots-urp-webgl-problem.1253661/


WebGL在預設條件果然還是有些限制，無法使用Microphone或是沒支援到DOT，之後觀察有沒有能著手的解決方案


另外在上傳到WebGL的時候需要注意壓縮的形式Format，改成Grip或是禁用
debug參考>https://stackoverflow.com/questions/72453065/unable-to-parse-build-build-framework-js-br
