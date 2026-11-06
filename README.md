# 틈타 (Teumta-Android)

퇴근길 수도권 전철 1호선, 역과 장소마다 오늘 들를 수 있는 시간을 알려 주는 Android 앱이에요.

- 서버: [Teumta-Server](https://github.com/dkk011/Teumta-Server)
- 개인정보처리방침: https://dkk011.github.io/Teumta-Server/privacy.html

## 기능
- 여유 시간 띠: 회사역부터 집역까지 역마다 오늘 머물 수 있는 시간
- 장소 경유: 들를 곳을 검색하면 몇 시까지 나오면 되는지와 탈 열차
- 1호선 102개 역, 급행·갈아타기·자정 넘은 막차까지 시간표로 계산 (실시간 지연은 반영하지 않음)

## 기술
Kotlin, Jetpack Compose (Material 3), MVVM, Coroutines/Flow, Hilt, Navigation Compose, Ktor Client, Room, DataStore + Tink, Credential Manager, 카카오맵 SDK

- 패키지명: `com.teumta.app`
- 최소 SDK와 빌드 방법은 프로젝트를 만든 뒤 채워요.
