# タグ

!!! Info "タグとは"
    OBSへ転送する先の名前や計算式の一部としてこの名前をつかう事ができます。
 
## タグ一覧

|タグ|意味|
|-------------------|--------------------------|
|  〔配信〕.last.userName| 最後にコメントした人の名前|
|  〔配信〕.last.displayName| 最後にコメントした人の表示名|
|  〔配信〕.last.comment| 最後にコメントした人のコメント|
|  〔配信〕.last.reward.cost| 最後に提供されたChポイント |
|  〔配信〕.last.reward.title| 最後に提供されたChポイントの種類 |
|  〔配信〕.gift.last.userName| 最後にギフトした人の名前|
|  〔配信〕.gift.last.displayName| 最後にギフトした人の表示名|
|  〔配信〕.gift.last.comment| 最後にギフトした人のコメント|
|  〔配信〕.gift.last.paid| 最後にギフトした人の贈答表示|
|  〔配信〕.member.last.userName| 最後にコメントしたメンバーの名前|
|  〔配信〕.member.last.displayName| 最後にコメントしたメンバーの表示名|
|  〔配信〕.member.last.comment| 最後にコメントしたメンバーのコメント|
|  〔配信〕.moderator.last.userName|最後にコメントしたモデレーターの名前|
|  〔配信〕.moderator.last.displayName|最後にコメントしたモデレータの表示名|
|  〔配信〕.moderator.last.comment|最後にコメントしたモデレータのコメント|
|  〔配信〕.firstTime.last.userName| 最後にコメントした初見メンバーの名前|
|  〔配信〕.firstTime.last.displayName| 最後にコメントした初見メンバーの表示名|
|  〔配信〕.firstTime.last.comment| 最後にコメントした初見メンバーのコメント|
|  〔配信〕.viewer| 〔配信〕の視聴者数|
|  〔配信〕.upVote| 〔配信〕のこの配信における、高評価の数|
|  〔配信〕.totalLikeCount| 〔配信〕における、全いいねの数|
|  〔配信〕.total| 〔配信〕における、全視聴数|
|  〔配信〕.follower| 〔配信〕における、フォロワ数|
|  〔配信〕.points.ad| 〔配信〕における公告ポイント数|
|  〔配信〕.points.gift| 〔配信〕におけるギフトポイント数|
|  〔配信〕.title| 〔配信〕における配信タイトル|
|  〔配信〕.isLive| 〔配信〕が配信中かどうか(配信中ならソースを表示)|
|  〔配信〕.time.elapsed| 〔配信〕の配信経過時間|
|  word.〔キーワード〕.count| キーワード(タグ：〔キーワード〕)の数|
|  word.〔キーワード〕.uniqueCount| キーワード（タグ：〔キーワード〕)の数(ユニークユーザ数)|
|  live.time.countDown| カウントダウン時間|
|  live.time.countUp| カウントアップ時間|
|  live.time.local| 配信者現在時刻|
|  live.time.utc| 現在の世界標準時刻|
|  live.date.local| 配信者現在日付|
|  live.date.utc| 現在の世界標準日付|
|  action.〔設定〕.user.name| カスタムアクション(〔設定〕)成立時のユーザ名|
|  action.〔設定〕.user.comment| カスタムアクション(〔設定〕)成立時のコメント|
|  comment.count| コメント総数|
|  comment.firstTime.uniqueNames| 初見さんリスト|
|  comment.firssTime.uniqueCount| 初見さん数|
|  comment.uniqueUser.uniqueNames| 全コメントユーザ名|
|  comment.uniqueUser.uniqueCount| コメントしたユニークユーザ数|
|  comment.gift.uniqueNames| 全ギフトユーザ名|
|  comment.gift.uniqueCount| ギフトしたユニークユーザ数|
|  comment.member.uniqueNames| コメントした全メンバーユーザ名|
|  comment.member.uniqueCount| コメントした全メンバーユーザ数|
|  survey.isEnabled| アンケート中かどうか(配信中ならソースを表示)|
|  waitingList.joinWord| 参加キーワード|
|  waitingList.declineWord| 辞退キーワード|
|  question.title| クイズタイトル|
|  question.choice.〔n〕.tag| クイズの投票キー 〔n〕個め|
|  question.choice.〔n〕.label| クイズの選択肢 〔n〕個めが有効か？（有効ならソースを表示)|
|  question.choice.〔n〕.isEnabled| クイズの選択肢 〔n〕個めが有効か？（有効ならソースを表示)|
|  question.choice.〔n〕.count| クイズの投票数 〔n〕個め|
|  question.answer.count| クイズの全投票数|
|  setlist.title| セットリストのタイトル|
|  setlist.now.name| セットリストの曲名(現在)|
|  setlist.now.url| セットリスト曲ＵＲＬ(メディアソースならロードします)|
|  setlist.now.isEnabled| セットリストが有効か（有効ならソースを表示）|
|  setlist.wait.〔n〕.name| セットリスト〔n〕曲目の曲名(現在)|
|  setlist.wait.〔n〕.url| セットリスト〔n〕曲目ＵＲＬ(メディアソースならロードします)|
|  setlist.wait.〔n〕.isEnabled| セットリスト〔n〕曲目有効か（有効ならソースを表示）|
|  setlist.completed.〔n〕.name| セットリスト終了〔n〕曲目の曲名(現在)|
|  setlist.completed.〔n〕.url| セットリスト終了〔n〕曲目ＵＲＬ(メディアソースならロードします)|
|  setlist.completed.〔n〕.isEnabled| セットリスト終了〔n〕曲目有効か（有効ならソースを表示）|
|  setlist.wait.list| セットリスト　待ち（全部）|
|  setlist.wait.isEnabled| セットリスト　待ち（全部）有効か（有効ならソースを表示）|
|  setlist.completed.list| セットリスト　終了（全部）|
|  setlist.completed.isEnabled| セットリスト　終了（全部）有効か（有効ならソースを表示）|
|  waitingList.count| 参加待ち者数|
|  waitingList.now.requestCount|現在の参加待ち者の参加リクエスト回数|
|  waitingList.now.date|現在の参加待ち者が参加した日付|
|  waitingList.now.name| 現在の参加待ち者名|
|  waitingList.now.isEnabled| 参加待ちが有効か（有効ならソースを表示）|
|  waitingList.〔n〕.requestCount|現在の参加待ち者の参加リクエスト回数(〔n〕人目)|
|  waitingList.〔n〕.name| 現在の参加待ち者名 〔n〕人目|
|  waitingList.〔n〕.date|現在の参加待ち者〔n〕人目が参加した日付|
|  waitingList.〔n〕.isEnabled| 参加待ち〔n〕人目が有効か（有効ならソースを表示）|
|  waitingList.all| 参加待ちリスト|
|  waitingList.all.nr| 参加待ちリスト(改行無し)|
|  waitingList.isEnabled| 参加待ちが有効か（有効ならソースを表示）|
|  pinned.service| ピン止めしたチャットの配信サイト|
|  pinned.isEnabled| ピン止めしたチャットが有効か（有効ならソースを表示）|
|  pinned.tag| ピン止めしたチャットの枠名|
|  pinned.screenName| ピン止めしたチャットを書いた人の表示名|
|  pinned.userName| ピン止めしたチャットを書いた人の名|
|  pinned.userId| ピン止めしたチャットを書いた人のＩＤ|
|  pinned.message| ピン止めしたチャットメッセージ|
|  obs.scene.〔シーン名〕.showCount| シーンを表示した回数|
|  obs.transition.〔トランシジョン名〕.showCount| トランジションを表示した回数|
|  obs.〔シーン名〕.〔ソース名〕.showCount| アイテムを表示した回数|
|  obs.source.〔ソース名〕.isEnabled| OBSソースが表示されているかどうか|
|  obs.stream.state| OBSのストリーミング状態|
|  obs.stream.scene| OBSの現在のシーン|
|  obs.stream.isEnabled| 配信が有効か？|
|  obs.stream.isReConnect| 配信を再接続したか？|
|  obs.stream.timeCode| 配信秒数(OBSのレポートを基にしている)|
|  obs.stream.duration| 配信の遅延|
|  obs.stream.congestion| 配信の混雑状況|
|  obs.stream.bytes| 配信バイト数|
|  obs.stream.skipframe| 配信スキップフレーム|
|  obs.stream.totalframe| 配信トータルフレーム|
|  obs.screenShot.isEnabled| スクリーンショットのファイルが有効か？|
|  obs.screenShot.fileName| スクリーンショットのファイル名|
|  ync.last.talkerName| 最後に話した人の名前|
|  ync.last.〔n〕.text| 最後に話した人の文章 （n番目の言語)|
|  ync.last.〔n〕.inHiragana| 話者文にひらがなを含むか （n番目の言語)|
|  ync.last.〔n〕.inKatakana| 話者文にカタカナを含むか （n番目の言語)|
|  ync.last.〔n〕.language| 最後に話した人の言語名 （n番目の言語)|
|  ync.〔話者名〕.〔n〕.text| 話者別文章 （n番目の言語)|
|  ync.〔話者名〕.〔n〕.inHiragana| 話者文にひらがなを含むか （n番目の言語)|
|  ync.〔話者名〕.〔n〕.inKatakana| 話者文にカタカナを含むか （n番目の言語)|
|  ync.〔話者名〕.〔n〕.language| 話者別文章の言語名 （n番目の言語)|
|  customTransfer.〔Tag〕.text| カスタム転送文|
