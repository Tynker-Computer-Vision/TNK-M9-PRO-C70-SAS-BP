Perform a Right Click
======================


In this activity, you will learn to perform a right click if the distance between the middle finger and index finger is greater than 100.


<img src= "https://s3.amazonaws.com/media-p.slid.es/uploads/1525749/images/10511807/aa1.gif" width = "480" height = "320">




Follow the given steps to complete this activity:


1. Perform the right click


* Open the main.py file.


* Check if the length between the `index finger` and `middle finger` is greater than `100`.


    `if length > 100:`


* Use `cv2.circle` to draw a green color circle if the above condition is true.


    `cv2.circle(cameraFeedImg, (cx, cy),15, (0, 255, 0), cv2.FILLED)`


* Use  `pyautogui.click()` and pass `button= right` in it as a parameter to perform the right click.


    `pyautogui.click(button='right')`


* Save and run the code to check the output.


