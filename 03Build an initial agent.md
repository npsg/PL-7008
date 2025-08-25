# Build an initial agent

## Exercise 1 - Create agent

### Task 1.1 – Microsoft Copilot Studio portal
- 環境を必ずチェックします。

### Task 1.2 – Create an agent
1. 「新しいエージェント」を選択してから、画面左部の「構成」を選択します。すると、「名前」「説明」「指示」が入力できます。
2. 不動産予約サービス
3. 不動産物件の予約を作成する
4. 不動産物件の予約作成に関するトピックのエージェントを作成する
5. 「作成」ボタンの右側にある「･･･」を選択し、「エージェントの言語（ja-JP）を更新する」を選択した後、「en-US」に切り替えます。
<ol start="7">
<li>ここで、Bookingsが表示されない場合は環境が選択されていないか、前のトピック「Import Dataverse solution」が失敗しています。</li>
</ol>

## Exercise 2 - Add Generative AI answers

### Task 2.1 - Disable generative orchestration
- そのままオフにします。

### Task 2.2 – Add a knowledge source
1. 「サポート情報」タブ
<ol start="6">
<li>「エージェントに追加する」ボタン</li>
</ol>
<ol start="8">
<li>**エージェントをテストするパネル**の「トピック間の追跡」をオンにします。通常、テストパネルでは 1つのトピックごとに会話を開始・終了する挙動になります。これをオンにすると、会話の履歴を保持したまま別のトピックに移行できるようになります。</li>
</ol>
<ol start="11">
<li>Webが参照されて回答が生成されれば成功です。</li>
</ol>
