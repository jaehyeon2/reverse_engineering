# abex' 2nd crackme  
### Name을 입력했을 때 Serial 값 알아내기  
00403332 줄에 Congratuation! 으로 점프를 시키는 구간이 있음.  
그 줄의 위쪽에 브레이크 포인트를 건 후에 스택을 확인하면 Serial과 입력한 Serial을 비교하는 스택이 있음.  
요구하는 Serial 값을 얻어 낼 수가 있음.  
  
*Serial 값 = 앞 4자리 수 아스키 코드에 16진수 64를 더함
