## Download **Udemy** course by **udemy-dl** with cookies authentication method

1. Download **udemy-dl**
   	https://github.com/r0oth3x49/udemy-dl

2. Download python and install
   	https://www.python.org/downloads/

3. Install module requirement and check udemy-dl tool

   ```
   pip install -r requirements.txt
   ```

   ```
   Download ffmpeg and install to environment variable.
   ```

   ```
   python udemy-dl.py
   ```

   ![image-20200927121837196](C:\Users\ThuKha\AppData\Roaming\Typora\typora-user-images\image-20200927121837196.png)   

4. Open Udemy website on browser and get access token at cookies storage
   	https://github.com/r0oth3x49/udemy-dl/issues/389#issuecomment-491903900
   ![image-20200927122719466](C:\Users\ThuKha\AppData\Roaming\Typora\typora-user-images\image-20200927122719466.png)

5. Create cookies.txt file and put your token with following format
   ![image-20200927123114954](C:\Users\ThuKha\AppData\Roaming\Typora\typora-user-images\image-20200927123114954.png)

6. Open **CMD** at udemy-dl path

7. Check course info with udemmy-dl tool
   *python udemy-dl.py **[COURSE-URL]** -k **[ACCESS-TOKEN-FILE]** --info*

   ```
   python udemy-dl.py https://www.udemy.com/course/how-to-write-asterisk-dialplan-auto-attendant-menu-queue-configuration/ -k cookies.txt --info
   ```

    ![image-20200927123435310](C:\Users\ThuKha\AppData\Roaming\Typora\typora-user-images\image-20200927123435310.png)
   

8. Choose video resolution and subtitle language support

9. Start download
   *python udemy-dl.py **[COURSE-URL]** -k **[ACCESS-TOKEN-FILE]** -q [VIDEO-Quality]  -s **[SUBTITLE]** -o **[OUTPUT PATH]***

   ```
   python udemy-dl.py https://www.udemy.com/course/how-to-write-asterisk-dialplan-auto-attendant-menu-queue-configuration/ -k cookies.txt -q 720 -s en -o "F:\Downloaders\udemy-dl\output"
   ```


   ![image-20200927132533711](C:\Users\ThuKha\AppData\Roaming\Typora\typora-user-images\image-20200927132533711.png)

10. Done! It is download all course files and also all resource files.
    ![image-20200927132913540](C:\Users\ThuKha\AppData\Roaming\Typora\typora-user-images\image-20200927132913540.png)









