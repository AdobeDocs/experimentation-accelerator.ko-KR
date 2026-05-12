---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer Experimentation Accelerator
description: Journey Optimizer Experimentation Accelerator을 사용한 AI의 데이터 사용
topic: Content Management
role: User
level: Beginner
keywords: 콘텐츠, 실험, 다중, 대상자, 처리
TQID: https://experienceleague.adobe.com/FaQ5-cPzhnIplEoL1HwVh390jot-EA8G5u6JP8CVneI
product_v2:
  - id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2:
  - id: b3538224-471e-4c63-a444-9b19d89ae29c
  - id: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04
  - id: dc22c819-3f29-4e91-8b7d-5c6719831141
subfeature_v2:
  - id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2:
  - id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
  - id: bcc5edb5-84c3-4940-9f84-ed88b6c16274
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
  - id: eb30f47f-d87a-400f-8f78-63ce7979ff56
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 441
ht-degree: 2%

---

# Journey Optimizer Experimentation Accelerator을 사용한 AI의 데이터 사용{#experiment-accelerator-security}

**Adobe Journey Optimizer Journey Optimizer Experimentation Accelerator**&#x200B;을(를) 사용하면 인사이트를 자동으로 검색하고 실험 및 실험 프로그램을 개선할 수 있는 기회를 추천할 수 있습니다. 이 솔루션은 AI와 머신 러닝을 활용하여 이러한 권장 사항을 제공합니다. 이 문은 고객의 데이터가 **Journey Optimizer Experimentation Accelerator**&#x200B;에서 사용되는 방식을 명확히 설명합니다.

## Journey Optimizer Experimentation Accelerator은 어떤 데이터를 사용합니까?

현재 **Journey Optimizer Experimentation Accelerator**&#x200B;에서 사용하는 데이터 유형은 다음 세 가지입니다.

* **실험 메타데이터**: 실험 이름, 실험에 사용되는 대상자의 정의 및 실험의 처리(예: 이름, 분할 비율, 위치 또는 실험이 제공되는 표면).

* **치료의 성능**: 사람 수, 성공 지표의 평균 및 각 치료의 표준 편차.

* **치료의 내용**: 렌더링된 HTML 및 웹 사이트의 사용자에게 표시되는 치료의 스크린샷입니다.

## Journey Optimizer Experimentation Accelerator은 이 데이터로 무엇을 합니까?

**Journey Optimizer Experimentation Accelerator**&#x200B;은(는) 각 처리에 대한 콘텐츠를 가져와서 포함, 즉 콘텐츠의 수학적 표현을 만든 다음 이러한 포함 및 처리의 성능을 상호 연관시킵니다. 이 프로세스를 통해 나중에 사용하기 위해 가장 잘 수행된 콘텐츠 속성을 추출할 수 있습니다. 그런 다음 이러한 속성은 Adobe 호스팅 대용량 언어 모델에 제공되며, 이를 인사이트를 생성하고 기회를 제안하는 데 사용되는 사람이 읽을 수 있는 구문으로 변환됩니다.

## 사용된 데이터에 대한 Journey Optimizer Experimentation Accelerator의 제한 사항은 무엇입니까?

각 고객은 특정 조직 및 샌드박스에 할당됩니다. 전용 모델은 모든 샌드박스에 대해 교육됩니다. 샌드박스가 삭제되면 모든 관련 데이터, 신호 및 모델이 영구적으로 제거됩니다.

* 당사는 고객 데이터를 사용하여 해당 고객으로부터 모델을 교육하거나 세부 조정할 뿐입니다.

* 우리는 고객을 혼용하여 모델을 교육하거나 세밀하게 조정하는 일은 절대 하지 않는다.

## Adobe 모델 또는 AI가 브랜드의 사용자 경험을 자동으로 변경합니까?

아니요. **Journey Optimizer Experimentation Accelerator**&#x200B;에서는 변경할 수 있는 내용과 변경 방법에 대한 권장 사항만 제공합니다. Journey Optimizer 또는 Target을 사용하여 경험을 변경할 수 있는 권한이 있는 사용자만 이러한 권장 사항에 따라 작업을 수행할 수 있습니다. 모든 권장 사항은 푸시하기 전에 검토 및 편집할 수 있습니다.

## 데이터 또는 시스템 안정성에 위험이 있습니까?

**Journey Optimizer Experimentation Accelerator**&#x200B;은(는) 데이터만 수집 및 분석하여 향후 테스트를 위한 통찰력과 권장 사항을 제공합니다. 테스트 설정을 수정할 수 있는 액세스 권한이 없습니다. 도구 내에서 생성된 모든 제안은 구현을 위해 Target 및 Journey Optimizer으로 전송되므로 고객의 현재 활동에 영향을 주지 않습니다.
