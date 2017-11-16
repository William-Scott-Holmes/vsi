---



copyright:
  years: 2017
lastupdated: "2017-10-24"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}


# 디바이스 액세스 관리
{: #managing-device-access}

특정 디바이스의 세부사항에 액세스하고 이를 관리하려면 사용자 계정에 적절한 권한이 부여되어 있어야 합니다. 계정 관리자가 디바이스에 대한 사용자 계정 액세스 권한을 부여하고 나면 {{site.data.keyword.slportal_full}} 또는 API를 사용하여 디바이스 세부사항을 보할 수 있습니다. 표시되는 정보 또는 조치는 디바이스 유형과 사용자 계정이 부여된 권한에 따라 달라집니다.
{:shortdesc}

**참고:** 계정에 액세스 권한이 부여되지 않은 디바이스가 있는 경우에는 이러한 디바이스에 액세스하려 시도하면 "알 수 없는 디바이스" 이름이 표시됩니다.

디바이스 액세스 권한은 계정에 있는 임의의 사용자에게 지정할 수 있지만 자기 자신에게는 지정할 수 없습니다. 계정의 관리자만 자신의 고객 계정에 있는 모든 디바이스에 대해 액세스 권한을 가지며 계정에 있는 모든 다른 사용자의 액세스 권한을 설정할 수 있습니다.  

공용 가상 서버 또는 전용 가상 서버의 디바이스 세부사항에 액세스하려면 다음 권한이 있어야 합니다. 

**가상 서버 세부사항 보기**

지정된 가상 서버의 IP 주소, 운영 체제 유형, 비밀번호 등을 볼 수 있게 해 줍니다. 포털의 가상 서버 비밀번호를 업데이트할 수도 있습니다. 공용 인스턴스, 전용 인스턴스 및 전용 호스트 인스턴스를 보려면 사용자에게 이 액세스 권한이 있어야 합니다. 

**가상 전용 호스트 세부사항 보기**

지정된 전용 호스트의 IP 주소, 운영 체제 유형, 비밀번호 등을 볼 수 있게 해 줍니다. 전용 인스턴스를 다른 전용 호스트에 마이그레이션할 수도 있습니다. 전용 호스트를 보려면 사용자에게 이 액세스 권한이 있어야 합니다. 

## 가상 서버 인스턴스를 볼 수 있는 권한 추가
하위 사용자에게 *가상 서버 세부사항 보기* 권한을 추가하려면 다음 단계를 사용하십시오. 계정의 관리자만 계정의 다른 사용자에게 권한을 부여할 수 있습니다.   

1. 고유 신임 정보를 사용하여 [{{site.data.keyword.slportal}} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")](https://control.softlayer.com/){: new_window}에 액세스하십시오.
2. 탐색줄에서 **계정 > 사용자**를 선택하여 사용자 화면에 액세스하십시오. 
3. 관련 사용자 이름을 클릭하여 사용자 프로파일에 액세스하십시오. 
4. **포털 권한** 아이콘을 클릭하여 포털 권한 화면에 액세스하십시오. 
5. *디바이스* 탭에서 **가상 서버 세부사항 보기**를 선택하여 이 권한을 사용자의 프로파일에 추가하십시오. 

특정 디바이스 레벨에서 액세스 권한을 제공하려면 다음 단계로 진행하십시오. 

1. **디바이스 액세스 권한** 아이콘을 클릭하여 디바이스 액세스 권한 화면에 액세스하십시오. 
2. **빠른 액세스** 탭을 클릭하십시오.
   참고: 또 다른 옵션은 개별 디바이스를 선택하는 것입니다. 
3. *디바이스 유형* 드롭 다운 목록에서 **모든 가상 서버**를 선택하십시오. 
4. 연관된 사용자가 이 디바이스 유형에 대한 액세스 권한을 항상 가져야 하는 경우에는 **새 디바이스가 추가되면 자동으로 액세스 권한 부여** 선택란을 선택하십시오. 
5. 올바른 디바이스가 선택되었는지 확인하십시오. 
6. **디바이스 액세스 권한 업데이트**를 클릭하십시오. 

## 전용 호스트를 볼 수 있는 권한 추가
하위 사용자에게 *가상 전용 호스트 세부사항 보기* 권한을 추가하려면 다음 단계를 사용하십시오. 계정의 관리자만 계정의 다른 사용자에게 권한을 부여할 수 있습니다. 

1. 고유 신임 정보를 사용하여 [{{site.data.keyword.slportal}} ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")](https://control.softlayer.com/){: new_window}에 액세스하십시오.
2. 탐색줄에서 **계정 > 사용자**를 선택하여 사용자 화면에 액세스하십시오. 
3. 관련 사용자 이름을 클릭하여 사용자 프로파일에 액세스하십시오. 
4. **포털 권한** 아이콘을 클릭하여 포털 권한 화면에 액세스하십시오. 
5. *디바이스* 탭에서 **가상 전용 호스트 세부사항 보기**를 선택하여 이 권한을 사용자의 프로파일에 추가하십시오. 

특정 디바이스 레벨에서 액세스 권한을 제공하려면 다음 단계로 진행하십시오. 

1. **디바이스 액세스 권한** 아이콘을 클릭하여 디바이스 액세스 권한 화면에 액세스하십시오. 
2. **빠른 액세스** 탭을 클릭하십시오.
   참고: 또 다른 옵션은 개별 디바이스를 선택하는 것입니다. 
3. *디바이스 유형* 드롭 다운 목록에서 **모든 전용 호스트**를 선택하십시오. 
4. 연관된 사용자가 이 디바이스 유형에 대한 액세스 권한을 항상 가져야 하는 경우에는 **새 디바이스가 추가되면 자동으로 액세스 권한 부여** 선택란을 선택하십시오. 
5. 올바른 디바이스가 선택되었는지 확인하십시오. 
6. **디바이스 액세스 권한 업데이트**를 클릭하십시오. 

**참고:** SoftLayer_User_Customer::addBulkDedicatedHostAccess API 서비스를 사용하여 하나 이상의 전용 호스트에 대한 사용자 액세스 권한을 부여할 수도 있습니다. 자세한 정보는 [대량 전용 호스트 액세스 권한 추가 ![외부 링크 아이콘](../icons/launch-glyph.svg "외부 링크 아이콘")](http://sldn.softlayer.com/reference/services/softlayer_user_customer/addbulkdedicatedhostaccess){: new_window}를 참조하십시오.   

## 다음 단계
사용자 권한은 변경사항이 제출된 후 즉시 업데이트됩니다. 권한이 부여된 경우 사용자는 선택한 기능을 보거나 이와 상호작용할 수 있습니다. 권한이 제거된 경우 사용자는 더 이상 선택한 기능을 보거나 이와 상호작용할 수 없습니다. 권한은 언제든지 다시 업데이트할 수 있습니다. 