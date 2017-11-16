---



copyright:
  years: 2017
lastupdated: "2017-11-06"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}

# 가상 서버 정보

{{site.data.keyword.BluVirtServers}}는 전용 코어 및 메모리 할당과 함께 구매되는 스케일링 가능한 가상 서버입니다. 이는 이미지 템플리트와 같은 기능을 사용할 수 있으며 수 분 내에 추가할 수 있는 계산 자원을 찾고 있는 경우 굉장히 유용합니다. 하이퍼바이저는 {{site.data.keyword.BluSoftlayer_full}}에서 완전히 관리하며 사용자는 {{site.data.keyword.slportal_full}} 및 {{site.data.keyword.slapi_short}}를 사용하여 구성 및 관리 태스크를 수행할 수 있습니다. 가상 서버는 실제 서버와 동일한 VLAN에 배치되어, 사용자가 상호 운용성을 유지하면서 가상 서버와 베어메탈 서버에 워크로드를 분산할 수 있게 해 줍니다. 가상 서버는 주문 시에 모든 항목을 사용자 정의할 수 있으며, 필요한 계산 능력이 증가함에 따라 스케일링할 수 있습니다.
{:shortdesc}

사용자는 시간별 또는 월별 비용 청구, 공용(멀티 테넌시) 환경 또는 전용(싱글 테넌시) 환경, 고성능 로컬 디스크 또는 엔터프라이즈 SAN 스토리지 간에 선택할 수 있습니다. 

## 주요 기능

다음 정보에는 가상 서버에 포함된 주요 기능이 나열되어 있습니다. 
### 매끄러운 통합

{{site.data.keyword.BluVirtServers_short}}는 베어메탈 서버 및 네트워크 어플라이언스와 동일한 포드에 배치됩니다. 이는 각 워크로드에 대해 최상의 기술을 사용할 수 있게 해 주는 유연성을 제공합니다. 일반적으로는 여러 가상 서버와 하나의 로드 밸런서가 배치되어 웹 트래픽을 서비스합니다. 이러한 서버는 베어메탈 데이터베이스 서버 및 기타 대량 워크로드에 대한 직접 계층 2 사설 네트워크 액세스 권한을 갖습니다. 
### 전체 사용자 정의 가능

몇 가지 옵션을 사용하여 어떤 조건에도 적합한 가상 서버를 빌드할 수 있습니다. 사전 정의된 패키지 요구사항이 없으므로 사용자는 각 서버가 지원하는 워크로드에 대해 서버를 조정할 수 있습니다. 

### 빠른 프로비저닝

가상 서버는 5분 내에 프로비저닝될 수 있어, 주문과 프로비저닝 간의 대기 시간이 매우 짧습니다. 
### 원격 관리

IBM의 모든 서비스 및 솔루션과 마찬가지로, 사용자는 가상 서버를 원격으로 관리할 수 있습니다. {{site.data.keyword.slportal}} 또는 {{site.data.keyword.slapi_short}}를 사용하여 모든 디바이스 세부사항을 보고 관리하십시오. 제공된 KVM 기능을 통해 서버와 상호작용하거나, 공용 또는 개인용 인터페이스를 통해 전체 관리 제어 권한을 갖고 서버에 로그인할 수도 있습니다. 
### 쉬운 스케일링

가상 서버가 프로비저닝된 후에는 인스턴스를 쉽고 빠르게 확장하거나 축소하고 필요에 따라 인스턴스를 추가하거나 제거할 수 있습니다. 서버가 구성되고 조정된 후에는 이에 대한 이미지 템플리트를 작성한 후, 원래 이미지를 기반으로 추가 가상 서버를 작성할 수 있습니다. 