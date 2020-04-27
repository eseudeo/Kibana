# kibana_korean

kibana에서는 기본적으로 영어를 지원하고, 공식적으로 일본어/중국어를 지원하고 있습니다.

Kibana version 6.7.1을 위한 한글 언어팩

##세팅 환경
* CentOS 7
* Kibana version 6.7.1

## 세팅방법
1) 한글팩 저장하기
* 한글팩 이름: ko-KR.json
* 한글팩 저장 위치: /usr/share/kibana/node_modules/x-pack/plugins/translations/translations

2) kibana.yml에 locale 셋팅 추가
Kibana.yml 위치: /etc/kibana
추가할 내용: i18n.locale: "ko-KR"

3) kibana restart
systemctl restart kibana.service
