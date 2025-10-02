# FIRMWARE-2025.10.01_02-D_9_-10
FIRMWARE-2025.10.01_02-D_9_ 10
#### etc. Buzzer


- TIM1 출력 이용 PWM 으로 부저의 주파수르 제어 할 것이므로 아래와 같이 설정한다. Counter Period(ARR) 값 변경에 따라 주파수가 제어됨으로 초기값은 큰 의미는 없으나 초기값 0일 경우 최초 전원인가시 동작을 안 해버릴 수 있으므로 사용할 음계 주파수 중간값으로 설정을 해준다.
- 
<p align="center">
<img width="1464" height="795" alt="image" src="https://github.com/user-attachments/assets/327a8482-2eb0-401d-8c69-c3cfa8368d9f" />
</p>
