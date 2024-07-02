# 안드로이드 Camera2 API와 OpenCV 체커보드를 이용한 캘리브레이션 내부행렬, 왜곡계수 구하기

## 프리뷰

![](https://github.com/wndudwkd003/Android_Camera2_OpenCV_Calibration/blob/master/demo/20240414_035508.png)

![](https://github.com/wndudwkd003/Android_Camera2_OpenCV_Calibration/blob/master/demo/ezgif-7-7defd44b8c.gif)

## 사용법
1. 안드로이드 스튜디오와 스마트폰을 연결한다.
2. 애플리케이션을 실행한다.
3. 오른쪽 상단 카메라 선택 버튼으로 원하는 카메라를 선택한다.
4. 메인 액티비티 내부에서 체커보드 가로 세로 개수가 맞는지 확인한다.
5. 오른쪽 하단 버튼을 눌러서 체커보드를 촬영하며 인식이 잘 되는지 확인한다.
6. 최대 촬영 개수를 넘어가면 자동으로 캘리브레이션 된다.
7. 로그캣창을 열어서 내부행렬과 왜곡계수를 확인한다.


## Reference
- https://developer.android.com/media/camera/camera2
- https://github.com/Kurun-pan/android-multi-camera
- https://foss4g.tistory.com/1665
- https://github.com/QuickBirdEng/opencv-android
