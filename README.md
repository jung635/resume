# 정선주



#### E-mail
sunju635@naver.com

---
## 🎓 학력

### 부경대학교
**컴퓨터공학과**
*2011/03 – 2016/08*

### 예문여자고등학교
*2008/03 – 2011/02*

---

## 🏢 경력

### 현대오토에버
**데이터플랫폼개발팀**
*2020/08/10 – 현재*

- 하둡 기반 데이터 플랫폼 개발
- 차량 데이터 수집체계 대응 자동차 트윈 시스템 개발
- 차량보안정보관리 서비스 개발 및 운영
- 차량 보안키 통합 관리 KMS 사양 개발

### 한국정보인증
**서비스운영팀**
*2017/09 – 2020/07*
- 공인 인증서 관리 서비스 개발 및 운영
- SSL 인증서 관리 서비스 개발 및 운영

### RealtyTech/GoMarketing
**개발팀**
*2016/02 – 2016/06*
- 부동산 웹사이트 개발

---

## 💻 프로젝트

### 하둡 기반 데이터 플랫폼 개발
*2020/08/10 – 현재*

**하둡 기반 오픈소스 빌드 및 패키징**

- 데이터 플랫폼 상품화를 위해, 하둡 에코 컴포넌트들의 빌드 및 패키징 수행
- 플랫폼 설치 및 사용 시 트러블 슈팅
- 컴포넌트간 호환성 문제 해결
- 대상 컴포넌트: 컴포넌트: Ambari, Zookeeper, Infra Solr, HDFS, Ambari Metrix, Yarn, Mapreduce2, Tez, Spark, Hive, Oozie, Sqoop, Hue, Ranger, Zeppelin, Hbase, Pig, Storm, Atlas, Kafka, Druid, Superset, Airflow, Nifi, Trino, Opensearch

**보안 강화**
- 주요 컴포넌트의 보안 로그 기록을 위한 Audit 플러그인 개발
  - 컴포넌트들의 동작 방식 및 코드를 분석하여, 오픈소스를 수정하지 않고 플러그인을 추가하여 Audit 로그를 기록 할 수 있도록 함.
    - 🛠️ 활용 기술
      - Ambari: Spring security Proxy Authentication Class 추가하여 로그인 로그 기록
      - Ranger: AoP, Spring Filter 사용하여 접근, 로그인, 유저 권한 관리, 보안 정책 관리 로그 기록  
      - Hue: Middleware 추가하여 로그인, 유저 권한 관리, 다운로드 로그 기록
      - Hdfs:  ranger plugin을 활용하여 접근 로그 기록
      - Hive: AoP를 활용하여, 쿼리 수행 기록
      - Trino: EventListener Plugin을 추가하여, 쿼리 수행 기록
      - Hbase: Coprocessor을 추가하여 쿼리 수행 기록
      - Spark: SparkListenerEvent을 추가 및 Spark Plan, Accumulator를 활용하여 통해 쿼리 수행 기록
      - Zeppelin: AoP를 활용하여 로그인 로그 기록
- 취약점 대응
  - 데이터 플랫폼에서 사용하는 오픈소스 디팬던시 취약점 점검 및 조치
    - 오픈소스 업그레이드 및 호환 관리
    - EoS 오픈소스 마이그레이션 수행
  - Zeppelin, Airflow, Hue와 같은 웹 기반 컴포넌트 취약점 대응
- LDAP 인증 적용
  - 컴포넌트별 LDAP 인증 적용

**Infra Solr 제거 및 Opensearch 대체**
- Ranger, Atlas의 Infra Solr 연동 제거 및 Opensearch로 대체
- Opensearch 미지원 API에 대한 호환 개발

**데이터 플랫폼 상품 공식 웹사이트 개발**
- Next.js 기반 데이터플랫폼 상품 공식 웹사이트 개발
- Confluence 매뉴얼 싱크 기능 개발

### vehicle twin 프로젝트
*2020/08/10 – 2021/08/31, 2022/04/01  - 2022/12/31*

**차량 데이터 파이프라인 구축**
- 자동차 트윈을 위한 차량 데이터 수집 파이프라인 개발
- 활용 기술: NiFi, Kafka, Kafka Connect, S3, Swift 등

**자동차 트윈 서비스 개발**
- k8s 기반 차량 데이터 활용 서비스 CI/CD 구축
- 테스트 자동화 스크립트 개발
- ELK 로그 적재 구축
- 🛠️ 활용 기술: k8s, spinnaker, ELK, Postman test scripts

**데이터 사용자들을 위한 Faas 시스템 개발**
- 데이터 기반의 서비스를 쉽게 관리 가능한 Faas 시스템 개발
- 🛠️ 활용 기술: k8s, Knative

**Devworks workspace 개발**
- 데이터를 활용한 소스 코드를 작성하고, 빌드 및 실행 할 수 있는 workspace 개발
- 🛠️ 활용 기술: React, Spring Framework


### 차량보안정보관리 서비스 개발
*2020/08/10 – 2022/02/28*

**차량보안정보관리 서비스 개발 및 운영**
- FoD 인증서 발급 및 검증 라이브러리 개발
- 펌웨어 전자서명 검증 개발
- 보안키/인증서 발급 개발
- FIDO 인증 로그인 적용
- DRM 모듈 적용
- 결제 관리, 계정관리, CRL, 보안라이브러리, 감사 및 모니터링, 게시판 메뉴 개발

### 차량 보안키 통합 관리 KMS 사양개발
*2021/09/01 – 2021/11/30*
- 현 보안키 관리 분석 및 키관리 시스템 요구사항 개발
- 키 라이프 사이클 사양 설계 및 검증 개발

### 공인 및 SSL 인증서 발급 및 관리 서비스 개발 및 운영
*2017/09 – 2020/07*
- 공인 인증서 관리 서비스 개발 및 운영
- SSL 인증서 관리 서비스 개발 및 운영
- SSL 인증서 관리 서비스 다국어화 수행
- CI/CD 구축 및 사내 파이프라인 표준화



