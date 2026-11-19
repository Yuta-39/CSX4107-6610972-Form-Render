# CSX4107-6610972-Form-Render

MEMO
action は 入力データの送信先 (URLやファイル名)
method は データの送り方(通信方法)
    postだとデータがURLに表示されず、裏側(Request Body)に隠れて送れる
    get 入力した内容がURLの後ろ(?name=yuta)のようにくっついて送られる。

    お問い合わせ・登録系ならpost
    検索フォームならget

    
