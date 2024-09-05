# PhotosToOneDrive
<h3>This colab project helps you to copy your Google Photos data to Microsoft OneDrive using RClone &amp; Colab</h3>
<h4>Follow the below instructions to get access token for Onedrive & Google Photos</h4> <br>
1.download rclone to your PC download link= https://rclone.org/downloads/
<br><br>
2.Open Rclone download Folder

![1  rclone folder](https://github.com/user-attachments/assets/54431c60-0328-4d31-8341-9e196390bb2e)

3. Click on the folder path/address bar

![2  Click on Address](https://github.com/user-attachments/assets/6c0d951c-c3de-41ee-87c3-1f91fd88f496)

4. Change the address to CMD & hit Enter

![3  change to cmd](https://github.com/user-attachments/assets/4dc97221-fe2d-457e-b01b-be8d433851d5)

5. Once cmd is open, type: rclone authorize "onedrive"

![4  cmd prompt](https://github.com/user-attachments/assets/af704ccb-fd4e-4d08-ae79-75bee0652459)

6. Your browser will redirect to onedrive signin, Login to your Microsoft Account

![5  onedrive login](https://github.com/user-attachments/assets/6f3a6b0b-369c-4f1b-9088-201617716bbe)

7. Once successfully authenticated, the landing page would show success.

![6  Success Page](https://github.com/user-attachments/assets/3b2400af-771c-4e6a-bca8-7373e96e2b47)

8. Go to CMD. Copy the access code & paste it somewhere for future reference.

![7  Access Code OneDrive](https://github.com/user-attachments/assets/f3def93e-6b82-43d7-9d10-7d6d2bd4e4b2)

9. Now to get access token for Google photos, enter the following in the CMD. TYpe rclone authorize "google photos"

![8  google photos](https://github.com/user-attachments/assets/c56de866-5b06-4229-9701-bb43c22f0231)

10. Login to your google account.

![9  google login](https://github.com/user-attachments/assets/af596c5a-1fec-47f1-999a-8a057a9e54d4)

11. Allow the permission to see & organize google photos data.

![10  permission](https://github.com/user-attachments/assets/024f1b37-844b-4200-8861-411928eb70cc)

12. If authorization is successful, the landing page would show success.

![11  success](https://github.com/user-attachments/assets/7932f40c-5228-4a40-a09d-a245d8e98c93)

13. Copy the access token & save it for future reference.

![12  access code google photos](https://github.com/user-attachments/assets/ea858164-c89c-4c6b-9512-72451cf664fd)







