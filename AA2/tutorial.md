Move the Cursor using Hand Signs
=================================

In this activity, you will learn to move the mouse pointer left, right, up and down using different hand signs.

<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10511888/aa2.gif" width = "480" height = "320">

Follow the given steps to complete this activity:

1. Move the mouse pointer

* Open the main.py file.

* Add a condition to check if `index and middle` fingers are up and then move the cursor down.

    `if fingers[0] == 1 and fingers[1] == 1 and fingers[2] == 1 and fingers[3] == 0 and fingers[4] == 0:`

        `pyautogui.move(0, 10)`

* Add a condition to check if first three fingers are up and move the cursor up.
                
    `if fingers[0] == 1 and fingers[1] == 1 and fingers[2] == 1 and fingers[3] == 1 and fingers[4] == 0:`

        `pyautogui.move(0, -10)`

* Add a condition to check if last two fingers are up and move the cursor left.

    `if fingers[0] == 1 and fingers[1] == 0 and fingers[2] == 0 and fingers[3] == 1 and fingers[4] == 1:`

        `pyautogui.move(-10, 0)`

* Add a condition to check if last finger is up and move the cursor right.

    `if fingers[0] == 1 and fingers[1] == 0 and fingers[2] == 0 and fingers[3] == 0 and fingers[4] == 1:`

        `pyautogui.move(10, 0)`

* Save and run the code to check the output.
