# ボウルのプログラムの作り方(How to develop a bowl program)

## 1. プログラムを作る前の準備(Preparation before develop the program)

- Scratch 3.0を起動し、スプライト1を削除する。(スプライト1を選択→×をクリック)

    Start Scratch 3.0 and delete sprite 1.(Select sprite 1　→　Click ×)

![Common](figure/common/startup_screen.png)

- ![Common](figure/common/sprite+button.png)ボタンをクリックする。

    Click on the ![Common](figure/common/sprite+button.png) button.

- ボウル(Bowl)を選択、クリックする。

    Select a bowl and click on it.

![Bowl](figure/bowl/select_bowl.png)

- スプライトが設定されていることを確認する。

    Confirm that the selected sprite is set.

![Bowl](figure/bowl/set_bowl.png)

## 2. プログラムの作り方(How to develop a program)

### 2-1. 完成イメージ(Completed image)

![Bowl](figure/bowl/bowl's_program_completed.png)

### 3-2. 作り方(How to develop)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/move_burron.png) ![Bowl](figure/bowl/x_y_coordinates.png) ![Bowl](figure/bowl/x_coordinates_change.png)×2 ![Bowl](figure/bowl/y_coordinates_change.png)×2

![Common](figure/common/event_button.png) ![Common](figure/common/flag.png)

![Common](figure/common/control_button.png) ![Common](figure/common/loop.png) ![Common](figure/common/if.png)×4

![Common](figure/common/examine_button.png) ![Bowl](figure/bowl/↑↓←→key.png)×4

![Bowl](figure/bowl/bowl_program_blocks.png)

- ![Common](figure/common/if.png)の![Common](figure/common/if_blank.png)に![Bowl](figure/bowl/↑↓←→key.png)をドラッグ＆ドロップします。(これを4回(ブロック数分)実行します。)

    Drag and drop ![Bowl](figure/bowl/↑↓←→key.png) to ![Common](figure/common/if_blank.png) for ![Common](figure/common/if.png).(Do this four times (for a few blocks).)

![Bowl](figure/bowl/bowl_if.png)

- ![Bowl](figure/bowl/↑↓←→key.png)の▼を押して、表示されるメニューで **『上向き矢印』を選択** します。 **残りのブロックに『下向き矢印』、『右向き矢印』、『左向き矢印』を設定** してください。

    Press ▼ on ![Bowl](figure/bowl/↑↓←→key.png) and select "up arrow" in the menu that appears.
Set the "down arrow", "right arrow", and "left arrow" for the remaining blocks.

![Bowl](figure/bowl/bowl_if_↑.png)

- **『上向き矢印』と『下向き矢印』を設定したブロック** に![Bowl](figure/bowl/y_coordinates_change.png)をくっつけます。

    Connect ![Bowl](figure/bowl/y_coordinates_change.png) to the blocks with the "up arrow" and "down arrow".

![Bowl](figure/bowl/bowl_if_↑_y.png)

- **『下向き矢印』を設定したブロック** の数字を **-10に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number of the block with the "downeft arrow" to -10.(Double-clicking on a number, you will be able to edit the number.)

![Bowl](figure/bowl/bowl_if_↓_y.png)

- **『右向き矢印』、『左向き矢印』を設定したブロック** に![Bowl](figure/bowl/x_coordinates_change.png)をくっつけます。

    Connect ![Bowl](figure/bowl/x_coordinates_change.png) to the blocks with the "right arrow" and "left arrow".

![Bowl](figure/bowl/bowl_if_→_x.png)

- **『左向き矢印』を設定したブロック** の数字を **-10に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number of the block with the "left arrow" to -10.(Double-clicking on a number, you will be able to edit the number.)

![Bowl](figure/bowl/bowl_if_←_x.png)

- ![Bowl](figure/bowl/x_y_coordinates.png)の **x座標とy座標の数字を以下の画像の内容に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the numbers in the x and y coordinates of ![Bowl](figure/bowl/x_y_coordinates.png) to the contents of the following image.(Double-clicking on a number, you will be able to edit the number.)

![Bowl](figure/bowl/x_y_coordinates_0_140.png)

- ブロックをくっつけてください。これでプログラムは完成です。

    Connect the blocks.The program is complete.

![Bowl](figure/bowl/bowl's_program_completed.png)
