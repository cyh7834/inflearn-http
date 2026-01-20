## 섹션 2. URI와 웹 브라우저 요청 흐름
### 1. URI (Uniform Resource Identifier)
* **의미**: 리소스를 식별하는 가장 포괄적인 개념.
* **URL (Locator)**: 리소스가 있는 위치. (가장 흔히 사용)
* **URN (Name)**: 리소스에 부여된 이름. (실제 리소스를 찾기 어려워 잘 사용 안 함)

### 2. URL 구조 분석
* `https://www.google.com:443/search?q=hello&hl=ko`
    * **Scheme**: 프로토콜 (http, https).
    * **Host**: 도메인명 혹은 IP 주소.
    * **PORT**: 일반적으로 생략 (http는 80, https는 443).
    * **Path**: 리소스 경로 (계층적 구조).
    * **Query**: `key=value` 형태. 서버에 전달하는 파라미터.