# Auto Clicker

**Version 3.2 · Windows · English / 简体中文 / 日本語**

[English](#english) · [简体中文](#简体中文) · [日本語](#日本語)

---

## English

Auto Clicker places numbered click markers anywhere on your Windows desktop, including across multiple monitors. Arrange the markers, set a delay for each point, and run a chosen number of cycles or repeat until stopped.

### Download and launch

1. Download `AutoClicker_v3.2.exe` from the project’s GitHub Releases page.
2. Double-click the EXE to launch it. Python does not need to be installed.
3. Use the language menu in the upper-right corner to choose **English**, **简体中文**, or **日本語**. The default language is English.

### Quick start

1. Select **Add Point**. A numbered marker appears near the mouse pointer.
2. Hold the **middle mouse button** on the marker and drag it to the target. The crosshair at its center marks the click position. Markers can be placed on any connected display.
3. In the point list, set the delay after each point. New points start at **0.5 seconds**. The delay is the pause before the next click.
4. Use **Move Up** and **Move Down** to change the order. Select **Delete** in a row, or right-click a marker, to remove a point.
5. Set the number of cycles, or select **Repeat indefinitely**.
6. Select **Start** and review the confirmation dialog. Confirmation before each cycle is enabled by default.

Press **F6** at any time while the task is running to stop it. Markers are hidden during clicking and shown again when the run finishes.

### Notes

- The app sends left-clicks at the marker coordinates. It cannot tell which control or file is underneath a point, so check every marker’s crosshair before starting.
- The per-cycle confirmation is useful for tasks that remove or change data. You can turn it off in the app if you do not need it.
- Points and settings are kept for the current session; closing the app clears them.
- The standalone EXE includes its runtime and does not require a separate Python installation.

---

## 简体中文

Auto Clicker 是一款 Windows 桌面连点工具。你可以在桌面上添加带编号的点击点，拖动点位、调整顺序和间隔时间，并设置运行轮数或无限循环。点位可以放在扩展桌面的任意显示器上。

### 下载和启动

1. 从项目的 GitHub Releases 页面下载 `AutoClicker_v3.2.exe`。
2. 双击 EXE 启动，不需要另外安装 Python。
3. 使用窗口右上角的语言菜单选择 **English**、**简体中文** 或 **日本語**。默认语言为 English。

### 快速开始

1. 点击 **添加点位**。屏幕上会在鼠标附近出现一个编号圆球。
2. 在圆球上按住**鼠标中键**并拖到目标位置。圆心十字就是实际点击位置；可以拖到任意已连接的显示器。
3. 在点位列表中设置每个点之后的等待时间。新建点位默认是 **0.5 秒**，表示点击该点后、继续下一个点击前的停顿时间。
4. 用 **上移**、**下移**调整顺序。点击该行的 **删除**，或在屏幕圆球上单击鼠标右键，可以移除点位。
5. 设置运行轮数，或选择 **无限循环**。
6. 点击 **开始运行**并查看确认框。默认会在每轮开始前询问一次。

运行过程中按 **F6** 可以立即停止。自动点击时圆球会暂时隐藏，运行结束后重新显示。

### 注意事项

- 软件会在点位坐标发送鼠标左键点击，但无法判断该位置下方是什么控件或文件。开始前请逐一核对圆心十字。
- 对删除或修改数据的任务，建议保留“每轮开始前都询问我”。不需要逐轮确认时，可以在软件中取消勾选。
- 点位和设置只在当前打开的软件会话中保留；关闭软件后需要重新添加。
- 独立 EXE 已包含运行所需组件，不需要单独安装 Python。

---

## 日本語

Auto Clicker は Windows デスクトップ用の自動クリックツールです。番号付きのクリックポイントを追加してドラッグで配置し、順番や待ち時間を設定できます。指定した回数だけ実行するか、停止するまで繰り返せます。拡張デスクトップ上の複数モニターにもポイントを配置できます。

### ダウンロードと起動

1. プロジェクトの GitHub Releases ページから `AutoClicker_v3.2.exe` をダウンロードします。
2. EXE をダブルクリックして起動します。Python のインストールは不要です。
3. 右上の言語メニューから **English**、**简体中文**、**日本語**を選択します。初期設定は English です。

### クイックスタート

1. **点を追加**を選択します。マウスポインターの近くに番号付きのマーカーが表示されます。
2. マーカー上で**マウスの中ボタン**を押したままドラッグし、クリックしたい位置に置きます。中央の十字がクリック位置です。接続された別のモニターにも配置できます。
3. ポイント一覧で各ポイントの後の待ち時間を設定します。新しいポイントの初期値は **0.5 秒**です。次のクリックまでの待ち時間を表します。
4. **上へ**、**下へ**で順番を変更します。一覧の**削除**を選ぶか、画面上のマーカーを右クリックしてポイントを削除します。
5. 実行回数を設定するか、**無限に繰り返す**を選択します。
6. **開始**を選択し、確認ダイアログを確認します。初期設定では各サイクルの前に確認を求めます。

実行中に **F6** キーを押すとすぐに停止します。クリック実行中はマーカーが一時的に非表示になり、終了後に再表示されます。

### 注意事項

- 指定した座標でマウスの左クリックを送信します。ポイントの下に何があるかは判別できないため、開始前に十字の位置を確認してください。
- データを削除・変更する作業では、各サイクルの確認を有効にしておくことをおすすめします。不要な場合はアプリ内で無効にできます。
- ポイントと設定は現在の起動中のみ保持されます。アプリを閉じると消去されます。
- 単体 EXE に実行環境が含まれているため、別途 Python をインストールする必要はありません。
