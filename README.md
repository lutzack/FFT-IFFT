# FFT-IFFT
・処理  
画像をフーリエ変換しパワースペクトルを出力した  
マウスイベントを取得する関数を用いて指定した周波数成分を逆フーリエ変換し出力した  
指定した周波数成分を周辺の周波数成分とともに逆フーリエ変換し合成して元画像の再構築を行った

・使い方  
プログラムを起動したらウィンドウが表示されるので「pick frequency」というウィンドウ上で  
好きなところを左クリックすると選択した周波数の空間領域での画像とその付近の周波数を用いて  
再構築を行った元画像が表示される  
終わるときは「pick frequency」で右クリックをする
 
ライブラリ　          バージョン  
matplotlib           3.0.3     
numpy                1.16.2         
opencv-python        4.1.0.25  

・参考にしたサイト  
https://codeday.me/jp/qa/20190515/831937.html  

https://www.hello-python.com/2018/02/16/numpy%E3%81%A8opencv%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%9F%E7%94%BB%E5%83%8F%E3%81%AE%E3%83%95%E3%83%BC%E3%83%AA%E3%82%A8%E5%A4%89%E6%8F%9B%E3%81%A8%E9%80%86%E5%A4%89%E6%8F%9B/  

https://algorithm.joho.info/programming/python/opencv-fft-spectrum/  
(コピーした部分：サンプルプログラムのソースコード)  

http://whitecat-student.hatenablog.com/entry/2016/11/09/225631  
(コピーした部分：サンプルプログラム)  

実行した結果  
https://github.com/lutzack/FFT-IFFT/blob/master/FFT-IFFT.gif
