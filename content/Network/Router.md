---
title: Router
draft: false
tags:
  - Network
---
 > [[Packet]]을 중계하는 장치의 일종

라우터는 어떤 장치가 어떤 선에 연결되어 있는지를 기록하고 패킷을 정확히 배달해줍니다.
Router가 목적지를 확인하여 다음 Router를 나타낸다. ->  IP가 목적지를 확인하여 다음 IP 중계 장치를 나타낸다.

## 경로표
- Network Destination — 패킷의 최종 목적지를 나타냄
- Netmask — 패킷의 최종 목적지를 나타냄
- Gateway — 중계 대상 라우터 주소
- Interface — LAN 어댑터 등의 네트워크용 인터페이스에서 패킷을 송신하면 상대에 패킷을 전해줄 수 있다는 의미
- Metric (메트릭) — 패킷 운반 비용
Network Destination, Netmask가 0.0.0.0 이면 기본 게이트웨이를 나타냄
Gateway 와 Interface가 같으면 라우터 중계 없이 직접 패킷을 전달할 수 있음
## Reference
Tsutomu Tone(2003), *[성공과 실패를 결정하는 1%의 네트워크 원리](http://www.yes24.com/Product/Goods/90640081)* ISBN [9788931556742](https://www.nl.go.kr/seoji/contents/S80100000000.do?schType=simple&schStr=9788931556742)