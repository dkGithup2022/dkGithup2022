

자바와 검색 시스템을 좋아하는 개발자입니다.  
개발자 정보공유를 위한 커뮤니티를 제작하고 있습니다. 

검색에서 유저의 의도와 성향에 맞는 정보를 제공함과 동시에, 서비스 관리에 대한 리소스를 줄이는데에 집중하고 있습니다.  
운영중인 커뮤니티 사이트는 주 한시간 정도의 투자로 온전히 운영중입니다.  

----

## 🛠 Skills

- **Backend**: Java, Spring Boot, MySQL, Elasticsearch
- **DevOps**: Kubernetes, Linux, Docker, GitHub Actions

---

## 🚀 Projects

### [Dev-Wiki](https://dev-wiki.dev/) – *공식 문서 검색/번역 서비스*
- LLM 기반 키워드 추출 + 벡터 검색 + 리랭크 조합으로 시맨틱 검색 제공
- MySQL, Spring 공식 문서 약 4,000건 번역 및 검색 서비스화
- [시스템 아키텍쳐](https://dev-wiki.dev/reading/tech/6)
- [데이터 프로세싱](https://dev-wiki.dev/reading/tech/5)
- [채용정보 검색 & 추천](https://dev-wiki.dev/hirings)


### [JavaFactory](https://github.com/JavaFactoryPluginDev/javafactory-plugin) – *LLM 기반 코드 자동 생성 도구*
- 자연어 패턴 정의 + 어노테이션 기반 참조 → 구현체, 테스트, 픽스처 자동 생성
- [서비스 레포지토리](https://github.com/JavaFactoryPluginDev/javafactory-plugin)
- [JetBrains Marketplace 등록](https://plugins.jetbrains.com/plugin/27246-javafactory--pattern-based-llm-code-generator)
- 데모 비디오 : [400 lines of code in 20s with all test passed](https://www.youtube.com/watch?v=ReBCXKOpW3M)


---

## 💼 Work Experience

### 🔍 검색 서비스 구축 및 운영
- Elasticsearch 기반 검색 시스템 초기 설계 및 성능 최적화  
  (1억 건 상품 데이터 / 캐시 없이 2000 QPS 처리)
- Full-text Query 튜닝 및 클러스터 병목 개선 (Single Shard Test 기반)

### 🧱 레거시 시스템의 차세대 전환
- 대규모 기성 서비스의 아키텍처 개편 및 차세대 시스템 이관 주도
- 슬로우 쿼리 분석 및 튜닝을 통한 응답 속도 안정화

___

## 연간 관심사 로그

수술과 치료 이후의 작업내용입니다.

#### 25. 6 : 테스트, 구현체 코드 생성 자동화 , llm  
intellij 플러그인으로 테스트, 인테페이스에 따른 구현체를 자동생성하는 도구를 만들어 배포했습니다.  
다운로드 400+ , 해커뉴스 인기글에 오르긴 했지만 mcp 와 claude code 혹은 cursor 조합에 비해 큰 이득이 없다고 생각. 접었습니다.  
만약에 이쪽으로 기여를 하거나 제품을 만든다면, [serena mcp](https://github.com/oraios/serena) 처럼 프롬프트 제작에 올바른 래퍼런스를 첨부하는 방향의 기여를 할 것 같습니다.   

지금은 claude code script 로 이떄의 작업을 대체하고 있습니다. 작업링크 : [스크립트모음 & 결과 프로젝트예시](https://github.com/dkGithup2022/claude_code_multimodule_script)

#### 25.8 건강문제로 잠깐 휴식 

#### 25.9 : 유저 관심사 반영한 검색 개발
기존 채용 검색에서 "카카오 뱅크" 를 검색 시, "카카오" 혹은 "토스" 의 리소스가 상단에 위치하는 경우를 포착.   
해당 문제를 해결하기 위해 검색 메커니즘을 개선합니다.

채용 검색 시, 두번의 검색을 수행합니다  
1. 사용자 의도 분석 - percolate query 를 통해 강조할 키워드, 가중치 추출  
2. 기존 쿼리에 (1) 의 결과 임베드   

디테일한 설명은 [문서](https://dev-wiki.dev/reading/tech/17) 로 남겼습니다.   


#### 25.10 : 기존 서비스 홍보 
지금은 홍보중입니다. 서치콘솔에 문제있어서 서비스 노출안되던거 수정하고 쓰레드, 단톡방 통해서 사이트를 홍보중입니다. 


