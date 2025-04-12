<details>
<summary>

# 作業連結

</summary>
<img src="qrcode_1.png" width="200" Height="200" />
</details>

<details>
<summary>

# 個人介紹

</summary>

| 項次 | 項目     | 內容                         |
|------|----------|------------------------------|
| 1    | 姓名     | 楊全全                       |
| 2    | 性別     | 男                           |
| 3    | 職稱     | 董事長                   |
| 4    | 圖片     | <img src="cat2.jpg" width="500" height="500" />                       |
| 5    | 公司     | 楊承翰的家         |
| 6    | 聯絡信箱 | j113252122@nkust.edu.tw    |
</details>


<details>
<summary>
  
# 課程line群組

</summary>

<img src="a1.jpg" width="200" Height="200" />

</details>


<details>
<summary>
  
# 喜歡的影片

</summary>

<a href="[http://www.youtube.com/watch?feature=player_embedded&v=FL1TaXa0hIU]([https://www.youtube.com/watch?v=wjfuB8Xjhc4](https://www.youtube.com/watch?v=wjfuB8Xjhc4))" target="_blank"><img src="http://img.youtube.com/vi/wjfuB8Xjhc4/0.jpg" 
alt="貓島" width="400" height="250" border="10" /></a>
<br>影片取自 youtube


<a href="http://www.youtube.com/watch?feature=player_embedded&v=wjfuB8Xjhc4" target="_blank"><img src="http://img.youtube.com/vi/wjfuB8Xjhc4/0.jpg" 
alt="貓島" width="400" height="250" border="10" /></a>
</details>

<details>
<summary>

# 程式碼的貓咪

</summary>

     ／＞　 フ  
    | 　_　_|   
  ／` ミ＿xノ   
 /　　　　 |   
/　 ヽ　　 ﾉ   
│　　|　|　|  
／￣|　　 |　|   
(￣ヽ＿_ヽ_)__)  
＼二)   |

</details>

<details>
<summary>

# 作業連結

</summary>
<img src="cat4.jpg" width="800" Height="800" />
</details>

<details>
<summary>

# 程式碼

</summary>

import cv2
from matplotlib import pyplot as plt

img = cv2.imread('cat3.jpg')
im2 = img[:,:,::-1]              # Convert image as rgb
plt.imshow(im2)
plt.show()

im3 = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)  # 轉成灰階
im3 = cv2.medianBlur(im3, 7)                 # 模糊化，去除雜訊
output = cv2.Canny(im3, 36, 36)              # 偵測邊緣

plt.imshow(output)
plt.show()

</details>






