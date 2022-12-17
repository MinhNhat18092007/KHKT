# KHKT



# Gesture Controlled Virtual Mouse &nbsp;[![](https://img.shields.io/badge/python-3.8.5-blue.svg)](https://www.python.org/downloads/) [![platform](https://img.shields.io/badge/platform-windows-green.svg)](https://github.com/xenon-19/Gesture_Controller) 

Gesture Controlled Virtual Mouse makes human computer interaction simple by making use of Hand Gestures and Voice Commands. The computer requires almost no direct contact. All i/o operations can be virtually controlled by using static and dynamic hand gestures along with a voice assistant. This project makes use of the state-of-art Machine Learning and Computer Vision algorithms to recognize hand gestures and voice commands, which works smoothly without any additional hardware requirements. It leverages models such as CNN implemented by [MediaPipe](https://github.com/google/mediapipe) running on top of pybind11. It consists of two modules: One which works direct on hands by making use of MediaPipe Hand detection, and other which makes use of Gloves of any uniform color. Currently it works on Windows platform.

 )_<br>
Note: Use Python version: 3.10.8

# Features
 _click on dropdown to know more_ <br>

### Gesture Recognition:
<details>
<summary>Hướng dẫn</summary>
 <figure>
 <pre>
  Để sử dụng chuột ảo bạn chỉ cần đưa ngón tay trỏ lên và di chuyển, để thực hiện lệnh nhấn chuột trái thì bạn chỉ cần đưa hai ngón tay trỏ và ngón giữa lên cùng một lúc sau đó bạn gập ngón tay trỏ xuống là được, còn nếu bạn muốn thực hiện nhấn chuột hai lần thì bạn chỉ cần kẹp hai ngón tay đó lại là được
2.	Zoom ảnh:
Để sử dụng zoom ảnh thì bạn chỉ đưa 2 ngón tay đầu tiên (của cả 2 bàn tay) lên sao cho xuất hiện 1 đường thẳng nối hai bản tay lại với nhau, sau đó bạn chỉ cần zoom ảnh bằng cách kéo hai bàn tay xa nhau 
3.	Vẽ trong không gian:
Bạn đưa 2 ngón tay giữa lên và chọn vào màu mực muốn vẽ, sau đó dùng ngón tay trỏ để có thể vẽ, nếu muốn xóa thì bạn có thể dùng icon tẩy
4.	Điều khiển thuyết trình:
Để thực hiện chuyển slide tiếp theo thì bạn chỉ cần giơ ngón út lên (tất cả các ngón còn lại nắm lại), còn nếu muốn quay lại thì bạn đưa ngón tay cái lên (tất cả các ngón còn lại nắm lại). Bạn có thể vẽ trực tiếp lên slide bằng ngón trỏ, xóa những phần đã vẽ bằng cánh giơ 3 ngón chính giữa lên
5.	Tăng chỉnh âm lượng:
Bạn thực hiện tăng chính âm lượng bằng cách tăng khoảng cách giữa 2 ngón cái và ngón trỏ, muốn set âm lượng thì bạn chỉ cần kẹp ngón út xuống
6.	Bàn phím ảo:
Bàn đưa 2 ngón giữa đến vị trí chữ cái muốn nhấn, để thực hiện nhấn phím thì bạn cần kẹp 2 ngón đó lại với nhau
7.	Trợ lý ảo:
Bạn thực hiện dùng trợ lý ảo bằng từ hãy. Trợ lý ảo có các chức năng như:
            1. Chào hỏi
            2. Hiển thị giờ
            3. Mở website, application
            4. Tìm kiếm trên Google
            5. Gửi email
            6. Dự báo thời tiết
            7. Mở video nhạc
            8. Thay đổi hình nền máy tính
            9. Đọc báo hôm nay
            10. Kể bạn biết về thế giới
            11…..
8.	Chuột ảo nâng cao:
Để xem cách sử dụng vui lòng truy cập đường link sau “”
</pre>

</figure> 
</details>


<details>
<summary>Neutral Gesture</summary>
 <figure>
  <img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/palm.gif" alt="Palm" width="711" height="400"><br>
  <figcaption>Neutral Gesture. Used to halt/stop execution of current gesture.</figcaption>
</figure>
</details>
 

<details>
<summary>Move Cursor</summary>
  <img src="https://github.com/xenon-19/Gesture_Controller/blob/e20edfb1f368ffa600d96bd91031942ec97cb2ab/demo_media/move%20mouse.gif" alt="Move Cursor" width="711" height="400"><br>
  <figcaption>Cursor is assigned to the midpoint of index and middle fingertips. This gesture moves the cursor to the desired location. Speed of the cursor movement is proportional to the speed of hand.</figcaption>
</details>

<details>
<summary>Left Click</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/left%20click.gif" alt="Left Click" width="711" height="400"><br>
 <figcaption>Gesture for single left click</figcaption>
</details>

<details>
<summary>Right Click</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/right%20click.gif" alt="Right Click" width="711" height="400"><br>
 <figcaption>Gesture for single right click</figcaption>
</details>

<details>
<summary>Double Click</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/double%20click.gif" alt="Double Click" width="711" height="400"><br>
 <figcaption>Gesture for double click</figcaption>
</details>

<details>
<summary>Scrolling</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/Scrolling.gif" alt="Scrolling" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for horizontal and vertical scroll. The speed of scroll is proportional to the distance moved by pinch gesture from start point. Vertical and Horizontal scrolls are controlled by vertical and horizontal pinch movements respectively.</figcaption>
</details>

<details>
<summary>Drag and Drop</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/drag%20and%20drop.gif" alt="Drag and Drop" width="711" height="400"><br>
 <figcaption>Gesture for drag and drop functionality. Can be used to move/tranfer files from one directory to other.</figcaption>
</details>

<details>
<summary>Multiple Item Selection</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/multiple%20item%20selection.gif" alt="Multiple Item Selection" width="711" height="400"><br>
 <figcaption>Gesture to select multiple items</figcaption>
</details>

<details>
<summary>Volume Control</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/Volume%20control.gif" alt="Volume Control" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for Volume control. The rate of increase/decrease of volume is proportional to the distance moved by pinch gesture from start point. </figcaption>
</details>

<details>
<summary>Brightness Control</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/Brigntness%20Control.gif" alt="Brightness Control" width="711" height="400"><br>
 <figcaption>Dynamic Gestures for Brightness control. The rate of increase/decrease of brightness is proportional to the distance moved by pinch gesture from start point. </figcaption>
</details>

