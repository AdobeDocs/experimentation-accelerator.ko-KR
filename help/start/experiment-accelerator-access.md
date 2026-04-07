---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator
description: 실험을 효과적으로 수행하고 인사이트를 생성할 수 있도록 역량을 향상하십시오.
topic: Content Management
role: User
level: Beginner
keywords: 콘텐츠, 실험, 다중, 대상자, 처리
source-git-commit: 020ed6c652c66ed78789a5a90dfc8c8dece624a9
workflow-type: tm+mt
source-wordcount: '507'
ht-degree: 18%

---

# Journey Optimizer Experimentation Accelerator 액세스

[실험을 만들고 구성](https://experienceleague.adobe.com/ko/docs/journey-optimizer/using/content-management/content-experiment/content-experiment)한 후 캠페인이나 여정을 프로필에 전송하면 **[!UICONTROL Journey Optimizer Experimentation Accelerator]**&#x200B;에 액세스하여 실험의 성과를 자세히 살펴볼 수 있습니다.

[!UICONTROL 실험] 드롭다운의 왼쪽 메뉴에서 또는 앱 전환기를 통해 **[!UICONTROL Journey Optimizer Experimentation Accelerator]**&#x200B;에 액세스할 수 있습니다. Target 라이선스만 있는 사용자는 앱 전환기를 통해서만 액세스할 수 있습니다.

![](assets/access.png)

사용 가능한 실험은 설정에 따라 다릅니다.

* **Adobe Journey Optimizer 사용자의 경우**: 활성화된 조직의 샌드박스에서 설정된 실험이 자동으로 포함됩니다.

* **Journey Optimizer을 사용하는 Adobe Target 사용자의 경우**: Target의 모든 A/B 활동이 Journey Optimizer의 프로덕션 샌드박스의 **[!UICONTROL Journey Optimizer Experimentation Accelerator]**&#x200B;에 표시됩니다.

* **Adobe Target 전용 사용자의 경우**: Target 조직의 모든 A/B 활동이 Journey Optimizer의 프로덕션 샌드박스에 포함됩니다.

**[!UICONTROL Journey Optimizer Experimentation Accelerator]**&#x200B;을(를) 사용하려면 샌드박스 및 다음 관련 권한에 액세스해야 합니다.

* **[!UICONTROL 실험 보기]**
* **[!UICONTROL 실험 메타데이터 관리]**

+++ Adobe Experience Platform 또는 Adobe 여정 최적화 프로그램 라이선스를 사용하여 실험과 관련된 권한을 할당하는 방법을 알아봅니다

1. **[!DNL Permissions]** 제품에서 **[!UICONTROL 역할]** 탭으로 이동하여 원하는 **[!UICONTROL 역할]**&#x200B;을(를) 선택하십시오.

1. 권한을 수정하려면 **[!UICONTROL 편집]**&#x200B;을 클릭하십시오.

1. **[!UICONTROL 실험 가속기]** 리소스를 추가한 다음 드롭다운 메뉴에서 **[!UICONTROL 실험 보기]** 및/또는 **[!UICONTROL 실험 메타데이터 관리]**&#x200B;를 선택합니다.

   ![](assets/permissions-experiment.png)

1. 변경 내용을 적용하려면 **[!UICONTROL 저장]**&#x200B;을 클릭하십시오.

이 역할에 이미 할당된 모든 사용자의 권한은 자동으로 업데이트됩니다.

새 사용자에게 이 역할을 할당하려면 다음 작업을 수행하십시오.

1. 역할 대시보드 내의 **[!UICONTROL 사용자]** 탭으로 이동한 다음 **[!UICONTROL 사용자 추가]**&#x200B;를 클릭합니다.

1. 사용자 이름, 이메일 주소를 입력하거나 목록에서 선택한 다음 **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   사용자를 이전에 만들지 않은 경우 [이 설명서](https://experienceleague.adobe.com/ko/docs/experience-platform/access-control/abac/permissions-ui/users)를 참조하세요.

사용자는 인스턴스에 액세스하기 위한 지침이 포함된 이메일을 받게 됩니다.

+++

</br>

+++ Adobe Target 라이선스를 사용하여 실험 관련 권한을 할당하는 방법을 알아봅니다

1. **[Admin Console](http://adminconsole.adobe.com/)**&#x200B;을(를) 엽니다.

1. **[!UICONTROL 제품]**&#x200B;에서 **[!UICONTROL Adobe Experience Platform]**&#x200B;을 선택하세요.

1. **[!UICONTROL 새 프로필]**&#x200B;을 클릭합니다.

   ![](assets/permission-target.png)

1. 프로필의 **[!UICONTROL 이름]** 및 **[!UICONTROL 설명]**&#x200B;을 입력한 다음 **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

1. 새로 만든 **[!UICONTROL 프로필]**&#x200B;을 열고 **[!UICONTROL 권한]** 탭으로 이동합니다.

1. **[!UICONTROL experimation-accelerator]** 권한 옆의 ![](assets/do-not-localize/Smock_Edit_18_N.svg)을(를) 클릭합니다.

   ![](assets/permission-target-1.png)

1. **[!UICONTROL 실험 보기]** 및 **[!UICONTROL 실험 메타데이터 관리]**&#x200B;와 같이 이 프로필에 필요한 권한을 추가한 다음 **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   >[!TIP]
   >
   > 사용자가 서로 다른 액세스 수준이 필요한 경우 별도의 프로필을 만듭니다. 예를 들어 **[!UICONTROL 실험 보기]**&#x200B;만 사용하는 **[!UICONTROL Experimentation Accelerator 뷰어]** 프로필과 **[!UICONTROL 실험 보기]** 및 **[!UICONTROL 실험 메타데이터 관리]**&#x200B;를 모두 사용하는 **[!UICONTROL Experimentation Accelerator 편집기]** 프로필을 만듭니다.

   ![](assets/permission-target-2.png)

1. **[!UICONTROL 권한]** 탭에서 **[!UICONTROL 샌드박스]**&#x200B;를 선택합니다.

1. 사용자가 Journey Optimizer Experimentation Accelerator을 사용할 수 있는 샌드박스를 추가한 다음 **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

1. **[!UICONTROL 사용자]** 탭을 연 다음 **[!UICONTROL 사용자 추가]**&#x200B;를 클릭합니다.

   ![](assets/permission-target-3.png)

1. 이 액세스 권한을 받을 사용자를 추가한 다음 **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

이 프로필에 추가된 사용자는 이제 앱 전환기에서 Journey Optimizer Experimentation Accelerator에 액세스할 수 있습니다.

+++


<!--
table style="table-layout:fixed"><tr style="border: 0;">
<td><img alt="Overview" href="experiment-accelerator-overview.md" src="assets/do-not-localize/experiments-2.jpeg">
<div align="center"><p><strong><a href="experiment-accelerator-overview.md">Overview</a></strong></p></div></td>
<td><img alt="Experiments" href="experiment-accelerator-monitor.md" src="assets/do-not-localize/experiment-overview.jpeg">
<div align="center"><p><strong><a href="experiment-accelerator-monitor.md">Experiments</a></strong></p></div></td>
<td><img alt="Metrics" href="experiment-accelerator-metrics.md" src="assets/do-not-localize/experiment-metrics.png">
<div align="center"><p><strong><a href="experiment-accelerator-metrics.md">Metrics</a></strong></p></div></td>
</tr></table
-->
