# リンゴのプログラムの作り方(How to develop an apple program)

## 1. 前提(Premise)

**[ボウル](bowl.md)のプログラムが完成** していること。

Bowl's program is complete.

## 2. プログラムを作る前の準備(Preparation before develop the program)

- ![Common](figure/common/sprite+button.png)ボタンをダブルクリックする。

    Double-click on the ![Common](figure/common/sprite+button.png) button.

- 表示される画面でリンゴ(Apple)をクリックする。

    Select an apple and click on it.

![Apple](figure/apple/select_apple.png)

- スプライトが設定されていることを確認する。

    Confirm that the selected sprite is set.

![Apple](figure/apple/set_apple.png)

## 3. プログラムの作り方(How to develop a program)

### 3-1. 完成イメージ(Completed image)

![Apple](figure/apple/apple's_program_completed.png)

### 3-2. 作り方(How to develop)

- ![Common](figure/common/make_block_button.png)を押してください。

    Press ![Common](figure/common/make_block_button.png).

- ![Common](figure/common/building_block_button.png)を押してください。

    Press ![Common](figure/common/building_block_button.png).

- 以下の画面が表示されるので、 **『ブロック名』を『初期設定』に変更** してから、OKボタンを押してください。

    When the following screen is displayed, change the "Block Name" to "Initial Settings" and press the OK button.

![Common](figure/common/init_screen.png)

- 以下の画面が表示されることを確認してください。

    Confirm that the following screen is displayed.

![Common](figure/common/init_block.png)

- ![Common](figure/common/variable_button.png)を押してください。

    Press ![Common](figure/common/variable_button.png).

- ![Common](figure/common/make_variable_button.png)を押してください。

    Press ![Common](figure/common/make_variable_button.png).

- 以下の画面が表示されるので、 **『新しい変数名：』に『スコア』と入力** してから、OKボタンを押してください。

    Enter "score" in "New variable name:" and press the OK button.

![Common](figure/common/add_variable_screen.png)

- **変数『スコア』が追加されていることを確認** してください。

    Confirm that the variable "Score" is added.

![Common](figure/common/score_variable.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/move_burron.png)　![Apple](figure/apple/someplace.png) ![Apple](figure/apple/y_coordinate.png)

![Common](figure/common/variable_button.png) ![Apple](figure/apple/score.png)

![Apple](figure/apple/apple_init_blocks.png)

- ![Apple](figure/apple/y_coordinate.png)の数字を **180に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number ![Apple](figure/apple/y_coordinate.png) to 180. (Double-clicking on a number, you will be able to edit the number.)

- 変更後、ブロックをくっつけてください。

    After the change, connect the blocks.

![Apple](figure/apple/apple_init_screen.png)

- 以下のブロックを画面中央にドラック＆ドロップします。

    Drag and drop the following blocks to the center of the screen.

![Common](figure/common/move_burron.png)　![Apple](figure/apple/someplace.png)×2 ![Apple](figure/apple/y_coordinate.png)×2 ![Apple](figure/apple/y_coordinate_change.png) ![Apple](figure/apple/y_coordinate_element.png)

![Common](figure/common/sound_button.png) ![Apple](figure/apple/make_a_sound.png)

![Common](figure/common/event_button.png) ![Common](figure/common/flag.png)

![Common](figure/common/control_button.png) ![Common](figure/common/loop.png) ![Common](figure/common/if.png)×2

![Common](figure/common/examine_button.png) ![Apple](figure/apple/mouse.png)

![Common](figure/common/operation_button.png) ![Apple](figure/apple/<.png)

![Common](figure/common/variable_button.png) ![Apple](figure/apple/score_change.png)

![Common](figure/common/make_block_button.png) ![Apple](figure/apple/init_setting.png)

![Apple](figure/apple/apple_program_blocks.png)

- ![Common](figure/common/if.png)の![Common](figure/common/if_blank.png)に![Apple](figure/apple/mouse.png)をドラッグ＆ドロップします。

    Drag and drop ![Apple](figure/apple/mouse.png) to ![Common](figure/common/if_blank.png) for ![Common](figure/common/if.png).

![Apple](figure/apple/if_mouse.png)

- ![Apple](figure/apple/mouse.png)の▼を押し、 **『マウスのポインター』から『Bowl』に変更** します。

    Press ▼ on A to change the "Mouse Pointer" to "Bowl".

![Apple](figure/apple/mouse_to_bowl.png)

- ![Apple](figure/apple/<.png)の![Apple](figure/apple/<_blank.png)に![Apple](figure/apple/y_coordinate_element.png)をドラッグ＆ドロップします。

    Drag and drop ![Apple](figure/apple/y_coordinate_element.png) to ![Apple](figure/apple/<_blank.png) for ![Apple](figure/apple/<.png).

![Apple](figure/apple/<_conv_y.png)

- ![Common](figure/common/if.png)の![Common](figure/common/if_blank.png)に![Apple](figure/apple/<_conv_y_small.png)をドラッグ＆ドロップします。

    Drag and drop ![Apple](figure/apple/<_conv_y_small.png) to ![Common](figure/common/if_blank.png) for ![Common](figure/common/if.png).

![Apple](figure/apple/if_<_conv_y.png)

- ![Apple](figure/apple/<_conv_y_small.png)の数字を **-170に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number ![Apple](figure/apple/<_conv_y_small.png) to -170. (Double-clicking on a number, you will be able to edit the number.)

- ![Apple](figure/apple/y_coordinate.png)の数字を **180に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)(これを2回(ブロック数分)実行します。)

    Change the number ![Apple](figure/apple/y_coordinate.png) to 180. (Double-clicking on a number, you will be able to edit the number.)(Do this two times (for a few blocks).)

- ![Apple](figure/apple/y_coordinate_change.png)の数字を **-5に変更** します。(数字をダブルクリックすることで、数字を編集できる状態になります。)

    Change the number ![Apple](figure/apple/y_coordinate_change.png) to -5. (Double-clicking on a number, you will be able to edit the number.)

- ブロックをくっつけてください。これでプログラムは完成です。

    Connect the blocks.The program is complete.

![Apple](figure/apple/apple_program.png)

- 最後に、プログラムを保存してください。

    Finally, save the program.

![Common](figure/common/save.png)
