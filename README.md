# cv2 라이브러리를 이용해서 이미지의 테두리만 추출하는 코드 작성
cv2.Sobel() 함수 사용
1. 입력 이미지
2. 출력 이미지 정밀도
3. x방향 미분차수
4. y방향 미분차수
5. 커널크기
6. ex) sobel = cv2.Sobel(img_test, cv2.CV_8U, 1, 0, 3)
