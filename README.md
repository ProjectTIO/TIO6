# Tio

골렘 공격 애니메이션 수정 - 24.1.8 update1 - OJS

벽 프렉쳐 효과 추가. - 24.1.8 update2 - OJS

물 웅덩이 추가 잡못 아이템 드롭 추가. - 24.1.9 update1 - OJS

아이템 효과 추가. - 24.1.10 update1 - OJS

맵 수정 - 24.1.11 update1 - OJS

프로토 완료. -.24.1.12

게임 사이클 종료. , 공격 수정 -24.1.15

폭

안녕
------------------------------------------------------------------------------------------------------

1.14

기본 플레이 캐릭터 - BP_ThirdPerson

텍스쳐 - 메가스캔 3D Assets - Quixel Bridge 

랜드스케이프- 폴라지 사용


골렘 (PawnSensing-시각)
ㄴbeginPlay - > Roam - > 브랜치 분기 (죽지 않았고 로밍[순찰] 이 연속적으로 false 일 경우 공격)
                                    ㄴ 공격 false 일 시 다시 roaming으로 
                                    ㄴ get Actor Location - > getRandomReachablePointinRadius -> AI Move to -> dealy -?set(roam)

ㄴEventTick -> updatePawnChase - > updateHeath Bar - > Check Health

ㄴupdatePawnChase - getActorLocation -> Play anim MOntage

updateHeatbar

player?

---
알파&베타
ㄴ 게임종료(사이클만들기)
ㄴ 아이템 상자
ㄴ 적 공격 위치 바꾸기
ㄴ 리스폰
ㄴ 레벨 맵 수정
ㄴ 보스 AI?