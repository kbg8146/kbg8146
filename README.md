# Kim Bugeon

**Embedded Software Engineer in Progress**

· 경북대학교 전자공학부

· LIG넥스원 THE SSEN 임베디드 SW 스쿨 3기

. SSAFY(삼성청년SW·AI아카데미) 16기

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/kbg8146)
[![Velog](https://img.shields.io/badge/Velog-20C997?style=flat&logo=velog&logoColor=white)](https://velog.io/@kbg8146)
[![Email](https://img.shields.io/badge/kbg8146@naver.com-03C75A?style=flat&logo=naver&logoColor=white)](mailto:kbg8146@naver.com)

---

## Projects

### GPS-Denied INS — STM32
> GPS 없이 IMU만으로 실내 항법을 수행하는 임베디드 시스템  

`STM32F429` `FreeRTOS` `I2C` `BNO055`

- 5개 FreeRTOS 태스크 설계 — Sensor, ADCS, Mission, Command, Telemetry
- Mutex 기반 IMU 데이터 보호, Fault Recovery FSM 구현
- I2C Clock Stretching 디버깅 → SDA Bus Lock-up 9-clock recovery 적용
- **오차율 52% → 30m 경로 기준 2m 이내로 개선**

→ [Repository](https://github.com/kbg8146/GPS-Denied-INS-STM32)

### Smart Nametag — IoT  
> ESP32 기반 스마트 명찰 시스템 (캡스톤)  

`ESP32` `MQTT` `BLE` `HTTP`

- ICD 문서 주도 작성 — JSON 필드 불일치 해결
- 에러 로그 레벨 시스템 설계 (INFO/WARN/ERROR/FATAL)
- **한국정보기술학회 동상 → 금상 수상**

→ [Repository](https://github.com/kbg8146/smart-nametag)

### 유도조종장치 모의환경 프로젝트
>

`Zynq` `FreeRTOS`

- 다이어그램
- ICD
- GCU
- 

### BMS 시스템

---

## Tech Stack

```
Languages        C · C++
MCU/SoC          STM32F4 · ESP32 · Zynq-7000
RTOS             FreeRTOS (Task, Queue, Mutex, Semaphore)
Embedded Linux   PetaLinux · Device Driver · TFTP/NFS Boot · Cross-Compilation
Protocols        I2C · SPI · UART · MQTT · BLE
Tools            Vivado · Vitis · STM32CubeIDE · VS Code · Git
Build            CMake · Makefile · ARM GCC Toolchain
```

---

## Algorithm

<div align="center">

<img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=kbg8146" alt="Solved.ac Profile"/>
<img src="http://mazandi.herokuapp.com/api?handle=kbg8146&theme=warm" alt="mazandi profile"/>

</div>


C++ 기반 BOJ 문제 풀이 — BFS/DFS, DP, 분할정복, 그리디, 이분탐색, 백트래킹

→ [Algorithm Repository](https://github.com/kbg8146/algorithm)

---
## Github Stats
<div align="center">
  
<img src="https://streak-stats.demolab.com?user=kbg8146&theme=dark"/>
<img src="https://github-readme-stats.vercel.app/api?username=kbg8146&show_icons=true&theme=dark" alt="GitHub Stats"/>

</div>
