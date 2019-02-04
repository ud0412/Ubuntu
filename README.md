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

