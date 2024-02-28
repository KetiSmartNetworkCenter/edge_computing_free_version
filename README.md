# Edge Computing Framework

엣지 컴퓨팅은 아래 그림과 같이 특정 프로토콜을 사용하여 통신하는 Device Service Layer와 디바이스 데이터  수집 및 저장을 하는 Core Service Layer, 디바이스 정보를 관리 및 명령 가능한 Device Management Service Layer로 구성됨

<img width="863" alt="image" src="https://github.com/KetiSmartNetworkCenter/edge_computing_free_version/assets/120157640/60eb8873-bf12-4799-a8b4-1e070ed1bb31">

## Get Started
### Free Version Service

Device Service Layer  
* OPC-UA
* UART
* Modbus-TCP
* Modbus-RTU
* MQTT
* REST

Device Management Service Layer
* Device Management
* Device Management Database (redislabs/rejson)

### Download
```
git clone https://github.com/KetiSmartNetworkCenter/edge_computing_free_version.git  
```

### Start
```
docker-compose up -d
```
