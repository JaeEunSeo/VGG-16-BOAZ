# VGG_BOAZ  

D & E 멘토멘티 스터디  

두 가지 Task가 있습니다.  


첫 시간에 가상환경 설정 방법에 대해 배웠죠?  

이를 이용해서 BOAZ16 이라는 가상환경을 만드세요  
<a href='https://www.notion.so/OT-d0144e9702d44bfbaa2a1749a4ff73ea'>(가상환경 만드는 방법 노션)</a>  
제가 드린 git link를 가지고 본인의 환경에 clone 하세요  

필요한 라이브러리를 설치하기 위해 파일 내에 있는 requirements.txt를 설치하세요

Task 1: 필수 과제(쉬워요..)  

폴더 내에 vgg.py 라는 파일이 있습니다.

여기 주석처리된 부분에 코드를 채워주세요.  

Task 2: 선택 과제(GPU가 필요할 거에요.. 아마?)  

폴더 내에 main.py 라는 파일이 있습니다.
터미널에 "python main.py -a vgg16 --dummy"를 실행해서 잘 돌아가는지 확인해 보세요!  
(구현 모습)
![image](https://github.com/Jeong-Eul/VGG-16-BOAZ/assets/122766824/2da63760-364f-445e-8890-3ca9d19ada01)

여기서 dummy 란 가상 데이터를 의미해요. 이미지넷 데이터세트는 너무 크기 때문에 잘 돌아가는지 확인하기 위한 용도로 만들어졌습니다.  
mian.py 파일에 이 dummy가 어떻게 만들어졌는지 알 수 있습니다. 궁금하시면 코드를 살펴보세요  

Task 1을 못하더라도 Task 2를 실행하는데 전혀 지장 없습니다.  
가상 환경 세팅부터 VGG Net 구성까지 모두 이해하는 것이 과제의 목표입니다.
