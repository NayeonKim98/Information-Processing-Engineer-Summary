# 2과목 소프트웨어 개발

### EAI(Enterprise Application Integration)

- 주요 통합 방식

| 방식 | 설명 | 장점 | 단점 |
| --- | --- | --- | --- |
| Point-to-Point | 1:1 | 간단 | 시스템 증가 복잡도 |
| Hub & Spoke | 중앙 허브, 개별 스포크 | 중앙 집중 | 허브 병목 |
| Message Bus | 공통 메시지 버스 | 확장성, 병목 낮음 | 구현 복잡도 |
| Hybrid | Hub & Spoke + Message Bus | 병목 낮고 구조 유연 | 설계 복잡, 비용 높음 |

### 소스 코드 품질 분석 도구

| 구분 | 종류 |
| --- | --- |
| 정적 | pmd, cppcheck, SonarQube, checkstyle ccm, cobertura Findbugs |
| 동적 | Avalanche, Valgrind |

- 동적을 외우자 ..

### 인터페이스 구현 검증 도구

| 구성 | 설명 |
| --- | --- |
| Warir | Ruby기반, 호환성 |
| xUnit | java 등, 테스트 |
| FitNesse | 웹 기반 |
| STAF | 서비스 호출 |
| NTAF Nawer | 자동화 |
| Selenium | 웹 애플리케이션 |

### 빌드 자동화 도구

| 도구 | 설명 | 특징 |
| --- | --- | --- |
| Ant | Apache 기반 | 순차, 유연, 복잡 |
| Maven | Apache 기반, 의존 | 라이프사이클 |
| Gradle | Groovy, 태스크 | 유연, 안드로이드 |
| Jenkins | CI/CD 자동화 | 파이프라인, 플러그인 |

### 저작권 관리 구성 요소

- 콘텐츠 제공자
- 패키저 : 배포 단위로 묶음
- 클리어링 하우스 : 키 관리 및 라이센스
- DRM 컨트롤러 : 배포된 콘텐츠 이용 권한

### 해싱 함수

| 해싱 방식 | 예시 |
| --- | --- |
| 제산법 | h(k) = k % m |
| 중간 제곱법 | k = 123 이면 k^2 = 15129 중간 세 자리 |
| 폴더법 | k = 123456 -> 123 + 456 |
| 숫자 분석법 | 010-1234-5678 에서 1234 |
| 기수 변환법 | k = 123 8진수로 변환 후 |
| XOR법 | k앞부분 ^ 뒷부분 = 해시값 |