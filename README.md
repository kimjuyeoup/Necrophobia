★Necrophobia
- 팀 프로젝트 "Necrophobia"에서 제가 직접 구현한 코드들을 정리해놨습니다.
- 언리얼 엔진에서 "C++"과 "Behavior Tree"를 활용하여 좀비 오브젝트의 AI 로직을 구현했습니다.

★Tech Stack
- Unreal Engine 5 (C++)
- Behavior Tree (BTTask, BTService, BTDecorator)
- Animation BluePrint

★My Contribution
- 이동 : 'Pro4Zombie','Pro4ZombieAI' -> AI 컨트롤러
- 공격 : 'Zombie_BTTask_Attack','BTDecorator_ZombieAttachRange' -> 공격 범위 판정 및 애니메이션
- 피격/사망 : 'Zombie_BTService_DeadOrAlive','BTDecorator_ZombiesSleepOrWake' -> 좀비 상태 관리

★시연 영상
- ![Zombie Demo](https://youtu.be/xR0lxL5kb2I)
