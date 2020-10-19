# abex' 1st crackme  
### HD를 CD-ROM으로 인식하게 만들기  
00401024 CMP EAX,ESI //EAX,ESI값이 같은지 비교  
00401026 JE SHORT 0040103D// 비교한 값이 같으면 점프 (문제에서는 같지 않아서 점프X)  
  
JE를 JNE로 변경해서 비교한 값이 같지 않을 경우 점프하도록 변경  
(EAX!=ESI -> 0040103D로 점프)
