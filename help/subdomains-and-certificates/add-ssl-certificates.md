---
title: SSL 인증서 추가
description: 하위 도메인 보안을 위해 SSL 인증서를 추가하는 방법을 알아봅니다.
feature: Control Panel
jira: KT-4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
source-git-commit: 81c5210502e719d6dfe0a000c511e3da4b17275a
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 100%

---

# SSL 인증서 추가

Adobe Campaign [!UICONTROL 컨트롤 패널]을 사용하면 하위 도메인 보안을 위해 SSL 인증서를 추가할 수 있습니다.

## 컨트롤 패널 하위 도메인 관리 액세스

컨트롤 패널의 하위 도메인 관리에 액세스하려면 다음 위치로 이동하십시오.

* [Experience Cloud 홈](https://experience.adobe.com/#/home) > 솔루션 선택기: **[!DNL Campaign]** > **[!UICONTROL > 컨트롤 패널]** 카드 > **[!UICONTROL 하위 도메인 및 인증서]** 카드

  또는
* 다음 URL에서 직접 액세스: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## SSL 인증서 추가 단계

SSL 인증서를 추가하려면 다음 3단계를 수행하십시오.

### 1. 인증서 서명 요청 생성

SSL 인증서를 구매하려면 CSR(인증서 서명 요청)이 필요합니다. 인스턴스와 보안을 설정할 하위 도메인에 대해 CSR을 생성해야 합니다.

아래 비디오에서는 컨트롤 패널에서 인증서 서명 요청을 생성하는 방법을 설명합니다.

>[!VIDEO](https://video.tv.adobe.com/v/31317?learn=on){transcript=true}

*인증서 서명 요청 생성(02:36)*

>[!NOTE]
>
>CSR 생성 프로세스에 몇 가지 개선 사항이 있습니다.
>
>* 이제 CSR을 생성할 때 포함된 하위 도메인 중 하나를 공통 이름으로 선택할 수 있습니다.
>* 이제 CSR을 생성하기 전에 CSR 요약을 복사할 수 있습니다.
>* CSR이 생성되면 작업 로그에서 다시 다운로드할 수 있습니다. 이 기능은 이 릴리스 전에 생성된 인증서에는 적용되지 않습니다.
>
>![CSR 다운로드](/help/assets/download-csr.gif)
>
>자세한 내용은 [제품 설명서](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=ko)를 참조하십시오.
>

### 2. SSL 인증서 구매

CSR을 획득한 후에는 조직에서 승인한 인증 기관에서 SSL 인증서를 구매해야 합니다.

### 3. SSL 인증서 설치

SSL 인증서를 획득한 다음에는 보안을 설정할 하위 도메인에 대해 해당 인증서를 설치해야 합니다.

아래 비디오에서는 [!UICONTROL 컨트롤 패널]에서 SSL 인증서를 설치하는 방법을 설명합니다.

>[!VIDEO](https://video.tv.adobe.com/v/31166?learn=on){transcript=true}

*SSL 인증서 설치(01:25)*


