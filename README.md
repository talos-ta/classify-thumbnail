# classify-thumbnail

## Description
これはYouTuberのメインチャンネルとサブチャンネルのサムネイルを分類するためのプログラム群です。  
YouTube Data APIのキーが必要です。  
「main」、「sub」にはそれぞれメインチャンネルとサブチャンネルのサムネイルが、「predict_main」「predict_sub」にはCNNで分類されたサムネイルが入ります。  
get_url.ipynbはサムネイルのURLを取得するプログラム、  
get_thumbnail.ipynbはURLからサムネイルを保存するプログラム、  
cnn.ipynbは画像データを学習し、分類するプログラムです。  
