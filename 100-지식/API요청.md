# API요청

#100-지식

비즈니스 모델: 너드랩은 태그 스크립트 설치 및 CRM 최적화까지 성장 해킹의 전체 프로세스를 자동화하는 '엔드 투 엔드' 플랫폼을 구축하고자 합니다. 태그 스크립트(리마케팅, 전환 등)를 설치함으로써 Google 디스플레이 광고, Meta 광고, TikTok 광고, 당근, 네이버 GFA를 운영하고자 하는 쇼핑몰들에게 동적 리마케팅 광고의 진입 장벽을 없애고자 합니다. 카페24,아임웹 API를 통해 데이터를 자동으로 관리하며, 문자 및 이메일 푸시에 필요한 타겟과 발송을 자동화하여 리텐션 매출을 통해 신규 유입 비용을 낮춰 실제 매출을 상승시키는 솔루션입니다.
이를 통해 Meta 및 Google 동적 리마케팅의 성과와 CRM 푸시의 자동화로 이커머스의 프로모션 임팩트를 높여줄 수 있습니다. 또한, 상업 광고주들에게 필요한 정확한 데이터만을 시각화하여 대시보드와 보고서를 구성하여 인사이트를 제공하고, 컨텐츠는 너드랩이 여태껏 가지고 있는 크리에이티브의 노하우로 인사이트를 제공해 줍니다. 
또한 구글 클라우드의 gemini AI와 빅쿼리의 학습으로 내부데이터를 AI가 학습 후 변화가 있는 포인트에 자동으로 디스코드에 푸시해 주는 인사이트 기능도 사람이 하지 않는 방향으로 진화할 것입니다. 

도구 접근/사용: 우리는 Meta, Google AdWords, TikTok의 동적 리마케팅 광고를 쉽게 생성할 수 있는 솔루션을 만들고자 합니다. 이 솔루션은 다음과 같은 기능을 제공할 예정입니다:
1. Meta, GDN, TikTok,당근 등  동적 리마케팅 광고를 운영하고자 하는 쇼핑몰을 대상으로 리마케팅 및 전환 태그 설치를 기술적으로 지원하여 광고 설정을 용이하게 합니다.
2. 데이터웨어하우스(GCP 클라우드 및 AWS)를 통해 자사몰 DB와 스마트스토어 DB를 연계하여 정확한 데이터를 구축하고 광고매치의 맞춤타겟,이메일 타겟, 문자 푸시등 정확한 CRM으로 매출의 임팩트를 높입니다.
3. 3대장 애널리틱스 (앰플리튜드,GA4,믹스패널)을 이벤트 텍소노미 기반으로 행동데이터를 수집하여, 광고주들이 어려움을 겪은 개발적인 페인포인트를 해결해줍니다. 
4. 상업 광고주에게 필요한 내부 정확한 데이터 웨어하우스를 통해  인하우스에서 경험한 유용한 데이터만을 시각화하는 대시보드와 보고서를 구축했습니다. ( 창업자는 쇼핑몰 인하우스의 경험이 많습니다.) 
5. 클라우드 서버와 Gemini AI를 통해 벡단의 데이터를 학습해서 데이터분석가 없이도 퀄리티 높은 인사이트를 발견해 줍니다. 
6. 너드랩의 디스코드 커뮤니티를 통해 AI가 인스타 보고 및 대시보드의 알람이 자동화되며, 가치를 공유하는 생명력 있는 광고주들의 교육도 무료로 제공합니다. 

도구 설계: 우리는 상업 광고주에게 필요한 데이터만을 시각화하는 대시보드와 보고서를 구축했습니다. 이 데이터는 자사몰,스마트스토어 API를 통해 도출하며, 각 광고 매체의 데이터들도 API 혹은 크롤링으로 수집하여 광고주의 이익률을 정확하게 측정할 수 있도록 도움을 줍니다. 
API 서비스 호출: 광고주의 스토어에서 데이터를 크롤링 및 API를 연동되며 CDP(고객 데이터 플랫폼)의 역할과 CRM 솔루션으로 Push 자동화 API와 연결됩니다. 

TEST STEP 
Test step
1. [rebeltech.info](http://rebeltech.info) log in (id: sonplancos / pw: project123)
2. meta ad report click
3. click facebook connect


**Business Model**:
NerdLab aims to build an end-to-end growth hacking platform that fully automates processes—from installing tag scripts to optimizing CRM. By implementing various tag scripts (for remarketing, conversions, etc.), we lower the entry barrier for shopping sites that want to run Google Display Network, Meta, TikTok, Danggeun, and Naver GFA dynamic remarketing ads. Through integrations with Café24 and I’m Web APIs, we automate data management, enabling automated targeting and sending of SMS and email push notifications. This not only helps drive retention-based revenue but also reduces new customer acquisition costs, ultimately boosting actual sales.
By leveraging Meta and Google dynamic remarketing capabilities and automating CRM pushes, our solution amplifies the impact of promotional campaigns for e-commerce businesses. Additionally, we provide advertisers with only the most relevant and accurate data visualizations, dashboards, and reports, delivering actionable insights. With NerdLab’s accumulated creative expertise, we can further enhance content strategy.
We are also evolving toward a system where Google Cloud’s Gemini AI and BigQuery can learn from internal data, automatically flagging points of change and pushing these insights to a Discord channel—eliminating the need for manual oversight.
**Tool Access/Usage**:
Our solution simplifies the creation and management of dynamic remarketing ads on Meta, Google AdWords, TikTok, and Danggeun. By providing technical support for installing remarketing and conversion tags, we streamline ad setup for shopping sites.
Through a data warehouse (built on GCP Cloud or AWS), we integrate data from proprietary stores and Naver Smart Stores, ensuring data accuracy. We then create highly customized audiences, email targets, and SMS push segments to maximize sales impact via precise CRM strategies.
We leverage leading analytics tools (Amplitude, GA4, Mixpanel) based on event taxonomies to collect behavioral data and resolve the technical challenges that advertisers often face.
For commercial advertisers, we utilize a highly accurate internal data warehouse to build dashboards and reports that visualize only the most valuable data. (Our founder has extensive in-house experience in managing shopping malls.)
With our cloud servers and Gemini AI, we train back-end data to uncover high-quality insights—without the need for a dedicated data analyst.
Through NerdLab’s Discord community, AI-generated reports and dashboard alerts are automated. We also freely share knowledge and educational resources, fostering a vibrant community of advertisers who recognize the value we bring.
**Tool Design**:
We have built dashboards and reports that visualize only the essential data commercial advertisers need. By connecting via the APIs of proprietary and Naver Smart Stores, as well as integrating data from each advertising medium (via API or web scraping), we enable advertisers to measure profitability with precision.
**API Service Calls**:
Data is collected from the advertiser’s store through API integration and/or web crawling. Our solution also acts as a CDP (Customer Data Platform) and connects with CRM solutions to automate push notifications via APIs.

---
**TEST STEP**
**Test procedure**:

TEST STEP 
Test step
login ID: [sonplancos@naver.com](mailto:sonplancos@naver.com) / PW: project123 -> Click "data table" in the MainPage 
1. Click Business Review Create button -> select a campaign and click the next button -> ad image not available
 
1. Click on the list inside "data table report" -> Some images are unavailable or have poor image quality.

## 🔗 연결된 카드
- [너드랩](../%EB%B3%B4%EB%93%9C/%EB%84%88%EB%93%9C%EB%9E%A9.md)
