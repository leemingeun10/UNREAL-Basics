# Unreal Engine 5 부트캠프 실습

게임 개발 부트캠프에서 Unreal Engine 5를 처음 배우며 만든 실습 프로젝트 모음입니다. (2025.03 ~ 2025.04)

## 프로젝트 목록

| 폴더 | 내용 |
| --- | --- |
| `Hello_Unreal` | 언리얼 에디터와 블루프린트 기초 |
| `EX2`, `Ex3` | 3인칭 캐릭터 조작, 블루프린트 실습 |
| `Ex4_GameState` | GameMode·GameState로 게임 규칙과 점수 관리 |
| `animProject` | 애니메이션 블루프린트와 상태 머신 |
| `vehicle` | 차량 물리 실습 |
| `HackAndSlashTemp` | 핵앤슬래시 전투 프로토타입 (몬스터, 화살·대포 발사체, 코인 획득과 인벤토리) |
| `migration` | 에셋 마이그레이션 실습 |

## 다룬 내용

- 블루프린트 클래스 상속과 컴포넌트
- 델리게이트(이벤트 디스패처)로 오브젝트 간 통신 (`BP_CountBox_Deligate`)
- 발사체(`BP_Arrow`, `BP_Bullet`, `BP_Cannon`)와 충돌 처리
- 코인 획득과 인벤토리(`BP_CoinGet`, `BP_CoinInven`)
- 몬스터 애니메이션 블루프린트

이 실습을 바탕으로 이후 [핵앤슬래시 프로토타입](https://github.com/leemingeun10/20250425Test)과 [멀티플레이 슈팅](https://github.com/leemingeun10/ShootingGame)을 만들었습니다.
