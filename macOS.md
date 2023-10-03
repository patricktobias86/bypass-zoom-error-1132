# SOLUTION FOR ERROR 1132 ON MACOS
### Follow these instructions to bypass Error 1132 from your computer, this works for both Mac using M and Intel chips and with all versions of Zoom (October 2023).

1. Download Zoom from zoom.us and install it as you normally would.
2. Open the Zoom app after you installed it.
3. At the top macOS menu, on the left of your screen click on the “Go” tab and select the “Go To Folder” option.
4. Navigate to `User/[USER]/Library/Application Support/zoom.us/data/`.
5. Locate the file called  `zoomus.enc.db` and right click on the file, choose "Open with" as choose `Text Edit`.
6. Once the text edit window opens, select all the text in the file (using CMD + A) and then press Delete. The file should now be empty.
7. Save the file using CMD + S and close the window.
8. Repeat step 5-7 with files `zoommeeting.enc.db` & `zoomus.tmp.enc.db`
9. After all three are done you can continue using Zoom without any Error 1132.
10. You can close the app as usual if you want and open it again.
