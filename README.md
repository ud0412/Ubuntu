# Ubuntu

* Ubuntu 한글 입력기 설정
  - 16.04
    + 시스템 설정 > 언어 지원 > 키보드 입력기 : fcitx
    + 시스템 설정 > 텍스트 입력창 : 한국어(101/104키 호환)
  - 18.4
    + 키보드 입력기 : ibus
    + 입력기 : 한국어(hangul)
    + 노트북 기종에 따라 한국어(hangul) 설정에 단축키 추가

* Lenovo 에서 Wi-Fi 잡히지 않는 문제
  - ubuntu 설치 후 첫 부팅후 terminal 에 아래 명령어 입력 후 reboot
  <pre><code> sudo tee /etc/modprobe.d/blacklist-ideapad.conf <<< "blacklist ideapad_laptop" </code></pre>

* 가상 화면 전환
  - 16.4
    + 시스템 설정 > 모양 > 동작방식 > 작업공간 바꾸기 사용 : check
    + ctrl + alt + 방향키로 전환
  - 18.4
    + super key(window key) + page up/down 
    + 특정 notebook 의 방향키에 page up/down 이 동시에 있는 경우 super + fn + 방향키 up/down
    
* 한글 설정에서 홈 아래 디렉토리 이름을 영어로 변경하기
  - 시스템 설정 > 언어 지원 > 메뉴와 창에 사용할 언어 를 영어로 변경
  - logout 후 다시 login 하면 폴더 이름 변경 창이 뜸. 이때 변경을 선택
  - 다시 메뉴와 창에 사용할 언어를 한국어로 변경하고 logout 후 login
  - 폴더 이름 변경 창이 뜨면 변경하지 않음을 선택

