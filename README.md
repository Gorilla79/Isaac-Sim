# Isaac-Sim

NVIDIA Omniverse Isaac sim 사용

## Unitree-Go2
- Go2 로봇을 시뮬레이션 한 과정을 정리

1. 로봇 임포트
   - 파일 위치 : omniverse://localhost/NVIDIA/Assets/Isaac/4.2/Isaac/Robots/Unitree/Go2/
   - Creat - Physics - Ground Plane 설정 필수!(안하면 로봇이 무한 떨어짐)
![Screenshot from 2024-11-23 14-24-27](https://github.com/user-attachments/assets/acf98b7c-c317-42d9-9d2e-40ee80022e37)

2. 파이썬 파일로 Go1 로봇 시뮬레이션 실행
   - 실행 위치 : /home/ds415/.local/share/ov/pkg/isaac-sim-2023.1.1
   - 실행 내용 : ./python.sh standalone_examples/api/omni.isaac.quadruped/a1_standalone.py --waypoint standalone_examples/api/omni.isaac.quadruped/waypoints.json
![Screenshot from 2024-11-23 21-34-19](https://github.com/user-attachments/assets/7cc9eaad-d2f3-4e44-9bb2-4c5710bb641c)
