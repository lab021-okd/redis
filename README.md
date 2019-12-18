Redis
=====
OKD 클라우드 플랫폼 구축 시 각 세부를 지원하기 위해 Redis에 대한 Docker 이미지와 OKD Cateogry Templdate를 구축하였다.

## Redis

레디스(Redis)는 고성능 key-value 저장소로서 리스트, 해시, 셋 정렬된 셋 등 여러 형식의 자료구조를 지원하는 NoSQL입니다. 메모리에 상주하면서 RDBMS의 캐시 솔루션으로서 주로 사용되며 라인, 삼성전자, 네이버, Stackoverflow, 인스타그램 등 여러 IT 대기업에서도 사용하는 검증된 오픈소스 솔루션입니다. 

## Docker

이 리포지토리에는 공개 Docker Hub 레지스트리에 게시 된 Docker의 자동 빌드 용 Redis의 Dockerfile이 포함되어 있다.

## Template

OKD에서 실행 가능한 template 파일로서 기본적인 구성을 통해 사용자가 컴스텀하게 변경 가능하도록 구성을 했다