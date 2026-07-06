# SHC-KPatch

본 패치는 비영리 목적으로 제작되었습니다  

본 패치의 상업적 이용은 금지합니다


본패치를  변조,개조,재배포 하지 마십시오  

본 패치를 공유하거나 롬에 입혀 공유하지 마십시오

저작권으로 인한 법적인 책임은 패치를 사용한 사용자에게 있음을 알려드립니다

문제 발생시 배포가 중단될 수 있고 추후 작업 또한 중단될 수 있습니다

<img width="1043" height="621" alt="image" src="https://github.com/user-attachments/assets/de366417-0400-47f4-bff5-91eccf45b69c" />

PS3 초 히로인 전기 한국어 패치

기종 : PS3  

게임명 :  초 히로인 전기  

          超ヒロイン戦記  
       
게임ID : BLJS10244  

게임버전 : 1.01


[한글패치 압축비번]  

2014년02월16일_v260702

[준비물]  

1. 한글패치
 
2. 원본 실행가능한 폴더 구조 (원본이 실행가능한 폴더 구조여야 합니다)
 
3. 1.01 업데이트(PKG)
 

[패치할 원본 MD5해시값]

1. design.cpk
 
원본 MD5해시값  

dbc220e0b59904559a10198da5c61910

2. ShcPack.cpk

원본 MD5해시값  

a448aaf260097f3c9098b610fa0c01c4

3. EBOOT.BIN

원본 MD5해시값  

bf33376d18b003ee0ea797dfb946f80a

[패치방법]  

 * 모든 파일은 한 곳에 같이 있어야 합니다 *

0. 패치할 작업폴더를 하나 만듭니다
 
   예> c:\SHCP


1. 한글패치를 "여기에 풀기"로 압축을 해제합니다.
 
   반드시 반디집이나 7-zip을 사용해주세요(알집은 사용금지)


2. EBOOT.BIN 1.01 복사
 
    A. rpcs3로 원본 롬폴더를 지정하여 실행합니다.
   
       hdd에 install 할꺼냐고 물어면 YES해서 타이틀 화면까지 가고 창을 닫습니다.
   
    B. rpcs3 에뮬 메뉴에서 install pakages/raps... 눌러 준비해둔 1.01로 업데이트 합니다.
   
    C. 1.01 업데이트가 된 것을 확인하고 rpcs3에뮬을 종료합니다.
   
       - 간혹 프로세스에 떠 있을 때가 있으니 '작업관리자'를 띄워서

         프로세스가 살아 있으면 강제종료 해주세요

    *아래 폴더를 반드시 삭제해주세요
   
      rpcs3-v0.0.41설치폴더\dev_hdd0\game\BLJS10244-INSTALL

    D.  패치할 파일들을 복사:  rpcs3설치폴더에서 EBOOT.BIN을 복사해옵니다.
   
          rpcs3-v0.0.41설치폴더\dev_hdd0\game\BLJS10244\USRDIR\EBOOT.BIN

3.  패치할 파일들을 복사:  ShcPack.cpk 복사, Design.cpk
  
   위치 : ShcPack.cpk   rpcs3-v0.0.41설치폴더\dev_hdd0\game\BLJS10244\USRDIR\
   위치 : Design.cpk  원본 롬폴더\PS3_GAME\USRDIR\

4. 패치시작
 
    "이거_눌러서_패치해.bat"를 눌러주고 잠시 기다립니다.
   
    완료 메세지가 나올 때까지 기다립니다

6. 패치된 파일 해당 위치에 복사 붙여넣기
 
   정상적으로 패치가 되면 패치할 작업폴더\patched 에 파일들이 생성됩니다.
   
7. 패치된 파일들과 hash.csv를 복사해서 붙여 넣습니다.  

-> 패치할 작업폴더\patched\ShcPack.cpk 파일을 아래 두군데에 복사 덮어쓰기  

A.위치1:  rpcs3-v0.0.41설치폴더\dev_hdd0\game\BLJS10244\USRDIR\  

B.위치2:  원본 롬폴더\PS3_GAME\USRDIR\  

--------------------------  

-> 패치할 작업폴더\patched\design.cpk  

 위치:  원본 롬폴더\PS3_GAME\USRDIR\

-> 패치할 작업폴더\patched\hash.csv 
   위치: 원본 롬폴더\PS3_GAME\USRDIR\
