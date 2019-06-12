---
title: Office 참가자에 대한 릴리스 정보
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
//: ''
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 초기 참가자 대상 그룹에게 주요 새 기능, 수정 사항 또는 알려진 문제의 최신 목록을 제공합니다.
ms.openlocfilehash: 8cc5c8c9b11dabce030095a2d56404856850377a
ms.sourcegitcommit: d8ac84be012031d41fc29caf7e5b0bc32425a523
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/11/2019
ms.locfileid: "34857758"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="eb38b-103">Office 참가자에 대한 릴리스 정보</span><span class="sxs-lookup"><span data-stu-id="eb38b-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="eb38b-104">이 문서에는 Windows 데스크톱용 Word, Excel, PowerPoint, Outlook, Access 및 Project 의 참가자 빌드에 대한 릴리스 정보가 포함되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="eb38b-105">매주 Microsoft는 흥미로운 새 기능, 중요한 수정 사항, 알리고자 하는 중요한 문제를 강조합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="eb38b-106">Microsoft는 일정 기간 동안 자주 참가자들에게 기능을 배포하며 때로는 수정 사항도 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="eb38b-107">이로서 더욱 광범위한 사용자들에게 기능을 릴리스하기 전에 원활하게 작동하는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="eb38b-108">따라서 아래에 설명된 기능이 보이지 않더라도 곧 제공되게 되므로 걱정할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="eb38b-109">릴리스 정보는 매주 게시되며 여러 빌드의 컴파일일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="eb38b-110">릴리스 정보 게시 날짜는 실제 빌드 릴리스 날짜와 일치하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-110">The release notes publication date may not match the actual build release date</span></span>

 > [!NOTE]
> - <span data-ttu-id="eb38b-111">Office 365 ProPlus의 기존 설치에 대한 Microsoft Teams - 6월 말부터 Microsoft Teams가 Office 365 ProPlus(및 Office 365 Business)의 기존 설치에 업데이트 설치 시 포함됩니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="eb38b-112">Teams가 추가되는 날짜는 사용 중인 업데이트 채널에 따라 다릅니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="eb38b-113">추가 정보는 [Office 365 ProPlus와 함께 Microsoft Teams 배포](https://docs.microsoft.com/ko-KR/deployoffice/teams-install)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="eb38b-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/en-us/deployoffice/teams-install) for additional information.</span></span>

## <a name="june-7-2019"></a><span data-ttu-id="eb38b-114">2019년 6월 7일</span><span class="sxs-lookup"><span data-stu-id="eb38b-114">June 7, 2019</span></span>
<span data-ttu-id="eb38b-115">버전 1907 (빌드 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="eb38b-115">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eb38b-116">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-116">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-117">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-117">Word</span></span> 
- <span data-ttu-id="eb38b-118">문장의 첫 글자를 대문자로 자동 고침을 설정했을 때 Word에서 종종 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-118">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="eb38b-119">SharePoint에서 문서를 편집할 때의 성능이 개선되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-119">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="eb38b-120">Adobe Illustrator에서 만든 벡터 기반 이미지가 올바르게 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-120">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-121">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-121">Excel</span></span>
- <span data-ttu-id="eb38b-122">매크로가 기록될 때 정렬 필드가 제대로 설정 되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-122">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="eb38b-123">배열 수식을 다시 계산하는 동안 멈춤 또는 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-123">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-124">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-124">PowerPoint</span></span>
- <span data-ttu-id="eb38b-125">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-125">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-126">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-126">Outlook</span></span>
- <span data-ttu-id="eb38b-127">인라인 첨부 파일의 크기가 잘못 조정되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-127">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-128">액세스</span><span class="sxs-lookup"><span data-stu-id="eb38b-128">Access</span></span>
- <span data-ttu-id="eb38b-129">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-129">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-130">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-130">Project</span></span>
- <span data-ttu-id="eb38b-131">일정 기간의 작업표에서 과제 완료 날짜가 간혹 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-131">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="eb38b-132">이전 버전에서 프로젝트를 열 때 완료율 값이 잘못될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-132">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="eb38b-133">2019년 5월 31일</span><span class="sxs-lookup"><span data-stu-id="eb38b-133">May 31, 2019</span></span>
<span data-ttu-id="eb38b-134">버전 1906 (빌드 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="eb38b-134">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eb38b-135">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="eb38b-135">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-136">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-136">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="eb38b-137">현재 고객 지원팀에 문의하기 위한 대화 상자는 도킹할 수 있으며 오른쪽에 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-137">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="eb38b-138">고객 지원팀에 문의하는데 사용되는 대화 상자가 이제 오른쪽 창에 표시되고 도킹된 창으로 시작 됩니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-138">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="eb38b-139">이메일에서 잉크로 표시하세요!</span><span class="sxs-lookup"><span data-stu-id="eb38b-139">Ink in Your Email!</span></span>

<span data-ttu-id="eb38b-140">이제 Outlook 전자 메일에 그림을 그리고 주석을 달 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-140">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-141">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-141">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="eb38b-142">Word로 문서 링크 열기</span><span class="sxs-lookup"><span data-stu-id="eb38b-142">Open document links in Word</span></span>

<span data-ttu-id="eb38b-143">Office에서 문서 링크를 클릭 시 기본 설정을 업데이트하여 Word 앱에서 기본적으로 열리도록 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-143">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="eb38b-144">기본 설정을 업데이트하려면 파일 ->옵션->고급->링크 처리로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-144">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="eb38b-145">자세한 정보: https://support.office.com/ko-KR/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="eb38b-145">Learn morehttps://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eb38b-146">시작하기:</span><span class="sxs-lookup"><span data-stu-id="eb38b-146">Getting Started:</span></span>

<span data-ttu-id="eb38b-147">기능은 기본적으로 해제됩니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-147">Feature will default to off.</span></span> <span data-ttu-id="eb38b-148">사용자는 옵션->고급->링크 처리 설정으로 이동하거나 Win32 WXP 앱이 옵트인 경험을 가능하게할 시 옵트인하여 기능을 켤 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-148">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="eb38b-149">사용자가 Outlook/Word/PowerPoint/Excel에서 비즈니스/Sharepoint용 OneDrive/OneDrive에저장된 Word/PowerPoint/Excel 파일로의 링크를 클릭하는 경우 기본적으로 브라우저가 아닌 해당 Office 응용 프로그램에서 링크가 열립니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-149">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="eb38b-150">이 기본 설정을 변경하려면 사용자는 Outlook/Word/Excel/PowerPoint에서 다음의 설정을 업데이트하면 됩니다:</span><span class="sxs-lookup"><span data-stu-id="eb38b-150">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="eb38b-151">파일->옵션->고급->링크 처리</span><span class="sxs-lookup"><span data-stu-id="eb38b-151">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="eb38b-152">이 설정은 Outlook/Word/PowerPoint/Excel에서 공유되며 이들 앱에서 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-152">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-153">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-153">Scenarios to Try:</span></span>

<span data-ttu-id="eb38b-154">옵트인 (opt in) 경험을 사용하려면 - Outlook/Word/PowerPoint/Excel에서 OneDrive/SharePoint에 저장된 Word 문서로의 링크를 엽니다 - 30일 창에서 이 과정을 두 번 시행합니다..</span><span class="sxs-lookup"><span data-stu-id="eb38b-154">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="eb38b-155">옵트인(opt-in) 한 후에는 기본적으로 Win32 앱에서 링크를 시작합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-155">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-156">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-156">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="eb38b-157">PowerPoint에서 프레젠테이션을 링크를 엽니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-157">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="eb38b-158">Office에서 프레젠테이션 링크를 클릭 시 기본 설정을 업데이트하여 PowerPoint 앱에서 기본적으로 열리도록 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-158">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="eb38b-159">기본 설정을 업데이트하려면 파일 ->옵션->고급->링크 처리로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-159">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="eb38b-160">자세한 정보: https://support.office.com/ko-KR/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="eb38b-160">Learn morehttps://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eb38b-161">시작하기:</span><span class="sxs-lookup"><span data-stu-id="eb38b-161">Getting Started:</span></span>

<span data-ttu-id="eb38b-162">기능은 기본적으로 해제됩니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-162">Feature will default to off.</span></span> <span data-ttu-id="eb38b-163">사용자는 옵션->고급->링크 처리 설정으로 이동하거나 Win32 WXP 앱이 옵트인 경험을 가능하게할 시 옵트인하여 기능을 켤 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-163">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="eb38b-164">사용자가 Outlook/Word/PowerPoint/Excel에서 비즈니스/Sharepoint용 OneDrive/OneDrive에저장된 Word/PowerPoint/Excel 파일로의 링크를 클릭하는 경우 기본적으로 브라우저가 아닌 해당 Office 응용 프로그램에서 링크가 열립니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-164">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="eb38b-165">이 기본 설정을 변경하려면 사용자는 Outlook/Word/Excel/PowerPoint에서 다음의 설정을 업데이트하면 됩니다:</span><span class="sxs-lookup"><span data-stu-id="eb38b-165">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="eb38b-166">파일->옵션->고급->링크 처리</span><span class="sxs-lookup"><span data-stu-id="eb38b-166">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="eb38b-167">이 설정은 Outlook/Word/PowerPoint/Excel에서 공유되며 이들 앱에서 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-167">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-168">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-168">Scenarios to Try:</span></span>

<span data-ttu-id="eb38b-169">옵트인 (opt in) 경험을 사용하려면 - Outlook/Word/PowerPoint/Excel에서 OneDrive/SharePoint에 저장된 PowerPoint 프레젠테이션으로의 링크를 엽니다 - 30일 창에서 이 과정을 두 번 시행합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-169">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="eb38b-170">옵트인(opt-in) 한 후에는 기본적으로 Win32 앱에서 링크를 시작합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-170">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-171">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-171">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="eb38b-172">Excel에서 워크북 링크 열기</span><span class="sxs-lookup"><span data-stu-id="eb38b-172">Open workbook links in Excel</span></span>

<span data-ttu-id="eb38b-173">Office에서 워크북 링크를 클릭 시 기본 설정을 업데이트하여 Excel 앱에서 기본적으로 열리도록 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-173">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="eb38b-174">기본 설정을 업데이트하려면 파일->옵션->고급->링크 처리로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-174">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="eb38b-175">자세한 정보: https://support.office.com/ko-KR/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="eb38b-175">Learn morehttps://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eb38b-176">시작하기:</span><span class="sxs-lookup"><span data-stu-id="eb38b-176">Getting Started:</span></span>

<span data-ttu-id="eb38b-177">기능은 기본적으로 해제됩니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-177">Feature will default to off.</span></span> <span data-ttu-id="eb38b-178">사용자는 옵션->고급->링크 처리 설정으로 이동하거나 Win32 WXP 앱이 옵트인 경험을 가능하게할 시 옵트인하여 기능을 켤 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-178">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="eb38b-179">사용자가 Outlook/Word/PowerPoint/Excel에서 비즈니스/Sharepoint용 OneDrive/OneDrive에저장된 Word/PowerPoint/Excel 파일로의 링크를 클릭하는 경우 기본적으로 브라우저가 아닌 해당 Office 응용 프로그램에서 링크가 열립니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-179">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="eb38b-180">이 기본 설정을 변경하려면 사용자는 Outlook/Word/Excel/PowerPoint에서 다음의 설정을 업데이트하면 됩니다:</span><span class="sxs-lookup"><span data-stu-id="eb38b-180">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="eb38b-181">파일->옵션->고급->링크 처리</span><span class="sxs-lookup"><span data-stu-id="eb38b-181">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="eb38b-182">이 설정은 Outlook/Word/PowerPoint/Excel에서 공유되며 이들 앱에서 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-182">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-183">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-183">Scenarios to Try:</span></span>

<span data-ttu-id="eb38b-184">옵트인 (opt in) 경험을 사용하려면 - Outlook/Word/PowerPoint/Excel에서 OneDrive/SharePoint에 저장된 Excel 워크북으로의 링크를 엽니다 - 30일 창에서 이 과정을 두 번 시행합니다..</span><span class="sxs-lookup"><span data-stu-id="eb38b-184">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="eb38b-185">옵트인(opt-in) 한 후에는 기본적으로 Win32 앱에서 링크를 시작합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-185">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eb38b-186">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-186">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="eb38b-187">모두</span><span class="sxs-lookup"><span data-stu-id="eb38b-187">All</span></span>
- <span data-ttu-id="eb38b-188">자동 저장이 비활성화된 상태에서도 파일이 간혹 자동으로 저장되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-188">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-189">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-189">Word</span></span> 
- <span data-ttu-id="eb38b-190">일부 사용자가 SharePoint에 저장하지 못하게 하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-190">We fixed an issue which prevented some users from saving files to cloud locations</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-191">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-191">Excel</span></span>
- <span data-ttu-id="eb38b-192">비활성 필터에 대해 올바르지 않은 아이콘이 표시될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-192">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-193">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-193">PowerPoint</span></span>
- <span data-ttu-id="eb38b-194">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-194">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-195">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-195">Outlook</span></span>
- <span data-ttu-id="eb38b-196">일부 사용자가 그룹 일정 보기에서 오프라인으로 잘못 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-196">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="eb38b-197">SafeLink가 후행 공백이 있는 URL을 분석하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-197">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="eb38b-198">방이 비 작업시간 외에 사용가능 하도록 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-198">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-199">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-199">Access</span></span>
- <span data-ttu-id="eb38b-200">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-200">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-201">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-201">Project</span></span>
- <span data-ttu-id="eb38b-202">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-202">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="eb38b-203">2019년 5월 24일</span><span class="sxs-lookup"><span data-stu-id="eb38b-203">May 24, 2019</span></span>
<span data-ttu-id="eb38b-204">버전 1906(빌드 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="eb38b-204">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eb38b-205">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="eb38b-205">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="eb38b-206">사용자 환경 업데이트</span><span class="sxs-lookup"><span data-stu-id="eb38b-206">User Experience Updates</span></span>

<span data-ttu-id="eb38b-207">출시 예정이었던 업데이트가 이제 시행되었으며, 이는 간소화된 리본과 폴더 창, 메시지 목록 및 읽기 창의 시각적 새로 고침 기능을 특징으로 합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-207">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eb38b-208">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-208">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="eb38b-209">모두</span><span class="sxs-lookup"><span data-stu-id="eb38b-209">All</span></span>

- <span data-ttu-id="eb38b-210">채팅 창이 표시되지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-210">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-211">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-211">Word</span></span> 
- <span data-ttu-id="eb38b-212">경우에 따라 Word에서 문법적 오류로 인해 텍스트가 잘못 강조될 수있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-212">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-213">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-213">Excel</span></span>
- <span data-ttu-id="eb38b-214">차트 요소에 올바르지 않은 아이콘이 사용되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-214">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="eb38b-215">동일한 통합 문서가 이미 열려 있는 경우 VBA 스크립트에서 잘못 된 통합 문서를 활성화할 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-215">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-216">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-216">PowerPoint</span></span>
- <span data-ttu-id="eb38b-217">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-217">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-218">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-218">Outlook</span></span>
- <span data-ttu-id="eb38b-219">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-219">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-220">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-220">Access</span></span>
- <span data-ttu-id="eb38b-221">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-221">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-222">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-222">Project</span></span>
- <span data-ttu-id="eb38b-223">작업 표시줄로 전환한 후 프로젝트가 중단될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-223">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="eb38b-224">2019년 5월 17일</span><span class="sxs-lookup"><span data-stu-id="eb38b-224">May 17, 2019</span></span>
<span data-ttu-id="eb38b-225">버전 1906(빌드 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="eb38b-225">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eb38b-226">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="eb38b-226">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-227">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-227">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="eb38b-228">사용자 환경 업데이트</span><span class="sxs-lookup"><span data-stu-id="eb38b-228">User Experience Updates</span></span>

<span data-ttu-id="eb38b-229">출시 예정이었던 업데이트가 이제 시행되었으며, 이는 간소화된 리본과 폴더 창, 메시지 목록 및 읽기 창의 시각적 새로 고침 기능을 특징으로 합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-229">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eb38b-230">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-230">Getting Started:</span></span>

<span data-ttu-id="eb38b-231">이러한 변경 사항은 새로운 기본 UI의 일부가됩니다. 12월 중순 이래로 출시 예정 스위치 뒤에 숨겨진 상태였지만 100% prod가 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-231">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="eb38b-232">사용자 지정이 가능한 간소화된 리본</span><span class="sxs-lookup"><span data-stu-id="eb38b-232">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="eb38b-233">클래식 및 요약 보기 간의 간편한 전환 및 명령 고정/고정 해제가 쉽도록 사용자 지정 가능</span><span class="sxs-lookup"><span data-stu-id="eb38b-233">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eb38b-234">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-234">Getting Started:</span></span>

<span data-ttu-id="eb38b-235">사용자는 출시 예정(초기 설정)을 켜고 리본의 갈매기 모양을 클릭해 클래식 멀티 라인 리본과 새로운 단순 싱글 라인 리본 사이를 전환하여 간소화된 리본을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-235">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-236">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-236">Scenarios to Try:</span></span>

<span data-ttu-id="eb38b-237">클래식 리본에서 간단한 리본으로 전환</span><span class="sxs-lookup"><span data-stu-id="eb38b-237">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="eb38b-238">즐겨찾기 선택 작업</span><span class="sxs-lookup"><span data-stu-id="eb38b-238">Pick your favorite action</span></span>

<span data-ttu-id="eb38b-239">플래그를 사용하지 않고 삭제?</span><span class="sxs-lookup"><span data-stu-id="eb38b-239">Don't use Flag and Delete?</span></span> <span data-ttu-id="eb38b-240">[보관] 또는 [읽은 상태로 표시]는 어떤가요?</span><span class="sxs-lookup"><span data-stu-id="eb38b-240">How about Archive or Mark as Read?</span></span> <span data-ttu-id="eb38b-241">가장 많이 사용하는 명령으로 빠른 작업 메뉴를 사용자 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-241">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eb38b-242">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-242">Getting Started:</span></span>

<span data-ttu-id="eb38b-243">빠른 작업을 선택하려면 메시지 목록의 이메일을 마우스 오른쪽 버튼으로 클릭하여 상황에 맞는 메뉴를 불러 오십시오.</span><span class="sxs-lookup"><span data-stu-id="eb38b-243">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="eb38b-244">그런 다음 "빠른 작업 설정..."을 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-244">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-245">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-245">Scenarios to Try:</span></span>

<span data-ttu-id="eb38b-246">기본값을 플래그에서 변경하고 보관으로 삭제, 이동, 읽은 상태로 표시하거나 메시지 목록을 더 깔끔하게 하기 위해 모두 없앱니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-246">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="eb38b-247">넓은 레이아웃 아니면 더 좁은 레이아웃?</span><span class="sxs-lookup"><span data-stu-id="eb38b-247">Relaxed or tighter layout?</span></span> <span data-ttu-id="eb38b-248">선택</span><span class="sxs-lookup"><span data-stu-id="eb38b-248">You choose</span></span>

<span data-ttu-id="eb38b-249">더 좁은 간격을 사용하면 항목 간에 더 넓은 공백을 할지 또는 더 좁은 레이아웃을 사용하여 더 많은 항목을 표시할지를 결정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-249">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eb38b-250">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-250">Getting Started:</span></span>

<span data-ttu-id="eb38b-251">보기 탭, 촘촘한 간격 사용 확인란 - 기본 리본의 메시지 그룹, 단순 리본의 현재보기 설정</span><span class="sxs-lookup"><span data-stu-id="eb38b-251">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-252">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-252">Scenarios to Try:</span></span>

<span data-ttu-id="eb38b-253">Outlook을 사용하여 설정을 사용하거나 사용하지 않고 전자 메일을 분류하고 작성합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-253">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="eb38b-254">간격을 좁게 사용하면 페이지당 메시지가 더 많이 표시되고 작성 양식의 컨트롤이 보다 간소화됩니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-254">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="eb38b-255">Onedrive 동기화 클라이언트를 사용할 때 MRU 항목 중복 제거</span><span class="sxs-lookup"><span data-stu-id="eb38b-255">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="eb38b-256">mru 항목을 제거하고 동기화된 데이터에 대한 복사 동작으로 보다 신속하게 연결할 수 있도록 하여 클라우드 첨부가 포함된 onedrive 동기화 클라이언트와보다 잘 통합됩니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-256">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eb38b-257">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-257">Getting Started:</span></span>

<span data-ttu-id="eb38b-258">OneDrive 동기화 클라이언트를 사용하면 첨부 파일 MRU에서 중복 된 파일이 더 이상 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-258">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-259">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-259">Scenarios to Try:</span></span>

<span data-ttu-id="eb38b-260">OneDrive 동기화 클라이언트 사용 및 Outlook 데스크톱의 파일 첨부 메뉴 사용</span><span class="sxs-lookup"><span data-stu-id="eb38b-260">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="eb38b-261">여러 폴더가 있는 사서함에 대한 공유 폴더 동기화 기능 향상</span><span class="sxs-lookup"><span data-stu-id="eb38b-261">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="eb38b-262">수년 동안 Outlook은 공유 사서함을 동기화할 때 폴더 수를 최대 500개로 제한해 왔습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-262">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="eb38b-263">이 변경을 통해 Outlook은 이 500개 폴더 제한이 더 이상 적용되지 않도록 동기화 방식을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-263">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eb38b-264">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-264">Getting Started:</span></span>

<span data-ttu-id="eb38b-265">사서함에 1000 폴더를 만들고, 다른 사용자에 게 사서함에 대 한 액세스 권한을 부여 하 고, "다른 사용자"를 위한 Outlook 프로필을 만들고, 동기화가 작동 하는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-265">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-266">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-266">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="eb38b-267">조금만 지우기</span><span class="sxs-lookup"><span data-stu-id="eb38b-267">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eb38b-268">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-268">Getting Started:</span></span>

<span data-ttu-id="eb38b-269">그리기 탭으로 이동하십시오. 지우개 드롭 다운을 선택하십시오.</span><span class="sxs-lookup"><span data-stu-id="eb38b-269">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="eb38b-270">작은 지우개 또는 중간 지우개를 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-270">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-271">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-271">Scenarios to Try:</span></span>

<span data-ttu-id="eb38b-272">그리기 탭으로 이동하 고 펜을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-272">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="eb38b-273">잉크 스트로크를 그립니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-273">Draw an ink stroke.</span></span> <span data-ttu-id="eb38b-274">지우개 드롭다운을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-274">Select the Eraser dropdown.</span></span> <span data-ttu-id="eb38b-275">작은 지우개 또는 중간 지우개를 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-275">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="eb38b-276">잉크 스트로크를 조금만 지웁니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-276">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eb38b-277">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-277">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="eb38b-278">모두</span><span class="sxs-lookup"><span data-stu-id="eb38b-278">All</span></span> 
- <span data-ttu-id="eb38b-279">일부 사용자가 PDF를 저장하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-279">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="eb38b-280">사용자가 32 비트 시스템에서 대용량 파일을 저장하는 데 영향을 줄 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-280">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-281">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-281">Word</span></span> 
- <span data-ttu-id="eb38b-282">받아쓰기 기능의 응답성을 크게 향상 시켰습니다</span><span class="sxs-lookup"><span data-stu-id="eb38b-282">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-283">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-283">Excel</span></span>
- <span data-ttu-id="eb38b-284">터치 스크린 장치에서 두 번 클릭 이벤트가 실패 할 수 있는 문제가 수정되었습니다</span><span class="sxs-lookup"><span data-stu-id="eb38b-284">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="eb38b-285">일부 사용자가 VBA 매크로를 편집하지 못할 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-285">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="eb38b-286">슬라이스를 사용할 때 성능에 영향을 줄 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-286">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-287">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-287">PowerPoint</span></span>
- <span data-ttu-id="eb38b-288">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-288">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-289">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-289">Outlook</span></span>
- <span data-ttu-id="eb38b-290">선택한 항목에서 잘못된 서식 파일을 표시할 수 있는 문제가 수정되었습니다</span><span class="sxs-lookup"><span data-stu-id="eb38b-290">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-291">액세스</span><span class="sxs-lookup"><span data-stu-id="eb38b-291">Access</span></span>
- <span data-ttu-id="eb38b-292">확대/축소 빌더를 사용하여 긴 서식 있는 텍스트를 표시하면 읽기가 어려워지는 문제를 해결했습니다</span><span class="sxs-lookup"><span data-stu-id="eb38b-292">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-293">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-293">Project</span></span>
- <span data-ttu-id="eb38b-294">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-294">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="eb38b-295">2019년 5월 10일</span><span class="sxs-lookup"><span data-stu-id="eb38b-295">May 10, 2019</span></span>
<span data-ttu-id="eb38b-296">버전 1906(빌드 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="eb38b-296">Version 1906 (build 11702.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eb38b-297">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-297">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="eb38b-298">모두</span><span class="sxs-lookup"><span data-stu-id="eb38b-298">All</span></span>
- <span data-ttu-id="eb38b-299">다른 이름으로 저장 대화 상자에서 잘못된 경로를 표시할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-299">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-300">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-300">Word</span></span> 
- <span data-ttu-id="eb38b-301">텍스트를 입력하세요의 일부 선택 항목이 삽입되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-301">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-302">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-302">Excel</span></span>
- <span data-ttu-id="eb38b-303">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-303">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-304">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-304">PowerPoint</span></span>
- <span data-ttu-id="eb38b-305">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-305">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-306">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-306">Outlook</span></span>
- <span data-ttu-id="eb38b-307">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-307">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-308">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-308">Access</span></span>
- <span data-ttu-id="eb38b-309">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-309">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-310">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-310">Project</span></span>
- <span data-ttu-id="eb38b-311">작업 ID에서 강조 표시가 필요할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-311">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="eb38b-312">2019년 5월 3일</span><span class="sxs-lookup"><span data-stu-id="eb38b-312">May 3, 2019</span></span>
<span data-ttu-id="eb38b-313">버전 1906(빌드 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="eb38b-313">Version 1906 (build 11629.20008)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eb38b-314">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-314">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="eb38b-315">모두</span><span class="sxs-lookup"><span data-stu-id="eb38b-315">All</span></span>
- <span data-ttu-id="eb38b-316">일부 사용자를 대상으로 비즈니스용 OneDrive 동기화 중에 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-316">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-317">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-317">Word</span></span> 
- <span data-ttu-id="eb38b-318">특정한 경우 Word를 시작하는 데 오랜 시간이 걸리는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-318">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-319">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-319">Excel</span></span>
- <span data-ttu-id="eb38b-320">최신 버전 Excel로 업그레이드한 후 통합 문서에서 가끔 외부 링크가 제거되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-320">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="eb38b-321">일부 사용자를 대상으로 새 통합 문서에서 셀을 선택할 때 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-321">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-322">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-322">PowerPoint</span></span>
- <span data-ttu-id="eb38b-323">드로잉을 텍스트로 변환할 때 글꼴 크기가 일정하지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-323">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-324">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-324">Outlook</span></span>
- <span data-ttu-id="eb38b-325">.VCF 파일에서 연락처를 저장하면 빈 필드가 생길 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-325">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="eb38b-326">전송되었음에도 불구하고 메시지가 보낼 편지함 폴더에 쌓일 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-326">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="eb38b-327">DRM 메시지를 볼 때 Outlook이 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-327">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-328">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-328">Access</span></span>
- <span data-ttu-id="eb38b-329">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-329">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-330">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-330">Project</span></span>
- <span data-ttu-id="eb38b-331">편집기가 중국어에서 영어로 전환되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-331">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="eb38b-332">게시되지 않은 작업이 게시된 마스터 프로젝트 사본에 표시될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-332">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="eb38b-333">2019년 4월 26일</span><span class="sxs-lookup"><span data-stu-id="eb38b-333">April 26, 2019</span></span>
<span data-ttu-id="eb38b-334">버전 1905(빌드 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="eb38b-334">Version 1905 (build 11617.20002)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eb38b-335">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-335">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-336">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-336">Word</span></span> 
- <span data-ttu-id="eb38b-337">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-337">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-338">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-338">Excel</span></span>
- <span data-ttu-id="eb38b-339">해 찾기 매크로가 실행에 실패하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-339">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="eb38b-340">Excel 파일를 SharePoint로 가져오지 못하게 하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-340">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-341">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-341">PowerPoint</span></span>
- <span data-ttu-id="eb38b-342">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-342">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-343">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-343">Outlook</span></span>
- <span data-ttu-id="eb38b-344">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-344">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-345">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-345">Access</span></span>
- <span data-ttu-id="eb38b-346">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-346">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-347">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-347">Project</span></span>
- <span data-ttu-id="eb38b-348">다양한 성능 및 안정성 수정 사항</span><span class="sxs-lookup"><span data-stu-id="eb38b-348">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="eb38b-349">2019년 4월 19일</span><span class="sxs-lookup"><span data-stu-id="eb38b-349">April 19, 2019</span></span>
<span data-ttu-id="eb38b-350">버전 1905 (빌드 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="eb38b-350">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eb38b-351">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="eb38b-351">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-352">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-352">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="eb38b-353">데이터 형식을 사용하여 등치 지역도 개선</span><span class="sxs-lookup"><span data-stu-id="eb38b-353">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="eb38b-354">이 기능은 Excel의 지리 데이터 형식을 사용하여 등치 지역도 차트를 그리는 사용자에게 유용한 개선 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-354">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="eb38b-355">기능과 최종 사용자가 매핑하고자 하는 지역의 정확성의 통합성을 향상하는 이점을 최종 사용자에게 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-355">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="eb38b-356">추가적인 이점은 도시 폴리곤을 매핑할 수 있다는 점입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-356">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eb38b-357">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-357">Getting Started:</span></span>

- <span data-ttu-id="eb38b-358">이 기능은 Excel의 기존 기능을 개선한 것입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-358">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="eb38b-359">개선 사항을 사용하려면 위치를 서식이 있는 엔티티로 변환하고 등치 지역도를 사용해 그립니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-359">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-360">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-360">Scenarios to Try:</span></span>

- <span data-ttu-id="eb38b-361">사용자는 국가, 시/도, 시/군/구 및 우편 번호를 매핑할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-361">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="eb38b-362">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-362">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="eb38b-363">모든 응용 프로그램</span><span class="sxs-lookup"><span data-stu-id="eb38b-363">All Applications</span></span>
- <span data-ttu-id="eb38b-364">응용 프로그램을 시작할 때마다 첫 번째 실행 대화 상자가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-364">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="eb38b-365">"다른 이름으로 저장" 대화 상자에서 SharePoint 링크가 누락되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-365">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="eb38b-366">사용자에게 "지금 복구" 대화 상자가 올바르게 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-366">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-367">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-367">Word</span></span> 
- <span data-ttu-id="eb38b-368">일부 사용자가 글꼴을 요청할 때 메모리 또는 디스크 공간 부족에 대한 오류가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-368">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="eb38b-369">메모 창에서 전환할 때 창 포커스를 잃는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-369">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-370">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-370">Excel</span></span>
- <span data-ttu-id="eb38b-371">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-371">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-372">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-372">PowerPoint</span></span>
- <span data-ttu-id="eb38b-373">브랜드 셰이프 크기를 조정할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-373">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="eb38b-374">제한된 보기 모드에서 파일을 열 때 PowerPoint에서 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-374">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-375">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-375">Outlook</span></span>
- <span data-ttu-id="eb38b-376">일부 사용자가 중국어 단어를 선택하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-376">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="eb38b-377">만료 날짜가 올바르게 계산되지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-377">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-378">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-378">Access</span></span>
- <span data-ttu-id="eb38b-379">일부 사용자가 매크로 작성기를 사용하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-379">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="eb38b-380">보고서를 인쇄할 때 첫 페이지만 인쇄하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-380">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="eb38b-381">하이퍼 링크를 마우스로 가리킬 때 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-381">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="eb38b-382">관계 보기를 사용하는 경우 일부 항목이 화면에 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-382">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-383">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-383">Project</span></span>
- <span data-ttu-id="eb38b-384">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-384">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="eb38b-385">2019년 4월 12일</span><span class="sxs-lookup"><span data-stu-id="eb38b-385">April 12, 2019</span></span>
<span data-ttu-id="eb38b-386">버전 1905 (빌드 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="eb38b-386">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eb38b-387">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="eb38b-387">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-388">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-388">Access</span></span>

#### <a name="new-in-access---data-connector-to-microsoft-graph"></a><span data-ttu-id="eb38b-389">Access의 새로운 기능 - Microsoft Graph에 대한 데이터 커넥터</span><span class="sxs-lookup"><span data-stu-id="eb38b-389">New in Access - Data Connector to Microsoft Graph</span></span>

<span data-ttu-id="eb38b-390">그래프에 저장된 스마트 컨텍스트 데이터를 활용할 수있는 응용 프로그램을 만들기 위해 양식 Microsoft Graph 서비스에 링크하거나 가져옵니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-390">Link to or import form Microsoft Graph services to build applications that can leverage the smart contextual data stored in the Graph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eb38b-391">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-391">Getting Started:</span></span>

<span data-ttu-id="eb38b-392">리본의 외부 데이터 탭에서 새 데이터 소스를 클릭하고 온라인 서비스 메뉴에서 새 그래프 커넥터를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-392">External Data tab in the ribbon, click on New Data Sources and find the new Graph connector in the Online Services menu</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-393">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-393">Scenarios to Try:</span></span>

<span data-ttu-id="eb38b-394">사람, 그룹 및 OneDrive 항목을 비롯한 다양한 그래프 서비스에서 가져오거나 링크할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-394">Import from or link to various Graph services including People, Groups and OneDrive Items.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eb38b-395">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-395">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="eb38b-396">모든 응용 프로그램</span><span class="sxs-lookup"><span data-stu-id="eb38b-396">All Applications</span></span>
 - <span data-ttu-id="eb38b-397">일부 사용자가 클라우드 위치에 파일을 저장하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-397">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="eb38b-398">잘못된 창이 리본에서 열릴 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-398">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-399">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-399">Word</span></span> 
- <span data-ttu-id="eb38b-400">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-400">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-401">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-401">Excel</span></span>
- <span data-ttu-id="eb38b-402">통합 문서에 연결된 데이터 유형이 없을 때 연결된 데이터 유형에 대한 오류 메시지가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-402">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="eb38b-403">로컬에서 또는 온라인에서 볼 때 Word 문서 내 URL 링크가 변경될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-403">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-404">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-404">PowerPoint</span></span>
- <span data-ttu-id="eb38b-405">애니메이션 탭에서 변경 사항을 취소한 후 응용 프로그램이 중단될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-405">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-406">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-406">Outlook</span></span>
- <span data-ttu-id="eb38b-407">일부 사용자가 공용 폴더에서 연락처에 대한 메모 필드를 수정할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-407">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="eb38b-408">만료 날짜와 삭제 날짜 간에 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-408">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-409">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-409">Access</span></span>
- <span data-ttu-id="eb38b-410">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-410">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-411">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-411">Project</span></span>
- <span data-ttu-id="eb38b-412">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-412">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="eb38b-413">2019년 4월 5일</span><span class="sxs-lookup"><span data-stu-id="eb38b-413">April 5, 2019</span></span>
<span data-ttu-id="eb38b-414">버전 1904(빌드 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="eb38b-414">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eb38b-415">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="eb38b-415">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-416">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-416">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="eb38b-417">Windows 용 Outlook: 중요 받은 편지함 설정 지정 및 공유</span><span class="sxs-lookup"><span data-stu-id="eb38b-417">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="eb38b-418">중요 받은 편지함 기본 설정은 클라우드에 저장되므로, 임의 컴퓨터에서 Windows용 Outlook 및 웹용 Outlook을 사용할 때 일관된 경험을 즐길 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-418">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eb38b-419">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-419">Getting Started:</span></span>

<span data-ttu-id="eb38b-420">파일 > 옵션 > 일반 탭에 새로운 ‘클라우드에 내 Outlook 설정 저장’ 기본 설정이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-420">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="eb38b-421">다른 Desktop Outlook 설치 및 OWA로 로밍하려면 사용자가 중요 받은 편지함 설정을 사용으로 지정하는 상자를 선택해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-421">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-422">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-422">Scenarios to Try:</span></span>

<span data-ttu-id="eb38b-423">클라우드 설정 기본 설정이 켜져 있는 컴퓨터에서 중요 받은 편지함을 변경하십시오.</span><span class="sxs-lookup"><span data-stu-id="eb38b-423">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="eb38b-424">OWA로 이동하여 거기에 적용된 환경 설정을 확인하십시오.</span><span class="sxs-lookup"><span data-stu-id="eb38b-424">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="eb38b-425">OWA에서 중요 받은 편지함을 변경하고 데스크톱 Outlook을 시작하여 환경 설정이 반영되었는지 확인하십시오.</span><span class="sxs-lookup"><span data-stu-id="eb38b-425">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-426">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-426">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="eb38b-427">학습 도구 모드는 더 많은 페이지 색상을 지원합니다</span><span class="sxs-lookup"><span data-stu-id="eb38b-427">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="eb38b-428">Word 학습 도구는 페이지 테마 색을 추가로 지원하므로 페이지의 배경색을 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-428">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="eb38b-429">많은 사람들이 흑백 또는 검정색 배경으로 읽는 것에 어려움을 느끼고 있으므로 PC 및 Mac의 Word에서 색상 선택을 확장했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-429">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eb38b-430">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-430">Getting Started:</span></span>

<span data-ttu-id="eb38b-431">이 기능을 사용하려면보기 탭으로 이동하여 학습 도구와 페이지 색상을 차례로 선택하십시오.</span><span class="sxs-lookup"><span data-stu-id="eb38b-431">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-432">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-432">Scenarios to Try:</span></span>

<span data-ttu-id="eb38b-433">이 기능을 사용하려면보기 탭으로 이동하여 학습 도구와 페이지 색상을 차례로 선택하십시오.</span><span class="sxs-lookup"><span data-stu-id="eb38b-433">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-434">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-434">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="eb38b-435">애니메이션 3D 모델로 독창성 높이기</span><span class="sxs-lookup"><span data-stu-id="eb38b-435">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="eb38b-436">이제 Office에서 애니메이션 모델을 지원하므로 편집기에서 재생되므로 시트를 실제로 사용할 수 있습니다!</span><span class="sxs-lookup"><span data-stu-id="eb38b-436">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eb38b-437">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-437">Getting Started:</span></span>

1. <span data-ttu-id="eb38b-438">Excel을 엽니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-438">Open Excel 2007.</span></span>
2. <span data-ttu-id="eb38b-439">애니메이션 모델을 삽입하십시오(곧 Remix로 변경되지만, 현재는 여기에서 애니메이션 모델에 액세스하십시오.\\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="eb38b-439">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="eb38b-440">애니메이션 모델이 편집기에서 재생됩니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-440">The animated model will play in the editor!</span></span> <span data-ttu-id="eb38b-441">슬라이드 쇼 모드를 확인하십시오 - 거기에서도 재생됩니다!</span><span class="sxs-lookup"><span data-stu-id="eb38b-441">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="eb38b-442">3D 형식 리본에서 모델의 더 많은 애니메이션 장면 탐색</span><span class="sxs-lookup"><span data-stu-id="eb38b-442">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-443">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-443">Scenarios to Try:</span></span>

1. <span data-ttu-id="eb38b-444">애니메이션 모델을 삽입하고 편집기에서 재생되는 것을 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-444">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="eb38b-445">장면 갤러리(3차원 서식 리본에서 사용 가능)를 통해 애니메이션 모델에서 사용할 수 있는 애니메이션 장면을 탐색합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-445">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="eb38b-446">리본, floatie 또는 스페이스 바를 사용하여 애니메이션을 간편하게 재생하고 일시 중지합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-446">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eb38b-447">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-447">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="eb38b-448">모든 응용 프로그램</span><span class="sxs-lookup"><span data-stu-id="eb38b-448">All Applications</span></span>
- <span data-ttu-id="eb38b-449">상황에 맞는 메뉴에서 Excel에 대해 잘못된 앱 아이콘이 나타나는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-449">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="eb38b-450">업데이트를 설치한 후 파일 메뉴 단추가 사라지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-450">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="eb38b-451">사용자 라이선스를 변경할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-451">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-452">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-452">Word</span></span> 
- <span data-ttu-id="eb38b-453">특정 줌 레벨에서 텍스트가 올바르게 렌더링되지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-453">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-454">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-454">Excel</span></span>
- <span data-ttu-id="eb38b-455">편집한 후 통합 문서 저장 메시지가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-455">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="eb38b-456">사용자가 통합 문서를 공유한 경우 BeforeSave 이벤트가 트리거되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-456">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="eb38b-457">열 크기를 6픽셀 미만으로 조정하면 잘못된 오류 메시지가 나타나는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-457">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="eb38b-458">Excel에서 Application.Visible 플래그를 무시하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-458">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="eb38b-459">비활성 상태의 고정된 창에 추적 화살표가 남아 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-459">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="eb38b-460">통합 문서를 열 때 날짜 및 통화에 대한 셀 서식이 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-460">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="eb38b-461">도구 설명이 예기치 않게 이동되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-461">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="eb38b-462">파워 쿼리 편집기의 지역화 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-462">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="eb38b-463">통합 문서를 전자 메일을 통해 첨부 파일로 보낼 때 통합 문서가 제거되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-463">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-464">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-464">PowerPoint</span></span>
- <span data-ttu-id="eb38b-465">도형 복사에 예상보다 시간이 오래 걸리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-465">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-466">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-466">Outlook</span></span>
- <span data-ttu-id="eb38b-467">그리기 도구를 사용하는 동안 Outlook이 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-467">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="eb38b-468">html 전자 메일을 작성할 때 지역화 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-468">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="eb38b-469">사용자가 아래쪽 창을 선택하기 힘든 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-469">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-470">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-470">Access</span></span>
- <span data-ttu-id="eb38b-471">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-471">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-472">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-472">Project</span></span>
- <span data-ttu-id="eb38b-473">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-473">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="eb38b-474">2019년 3월 22일</span><span class="sxs-lookup"><span data-stu-id="eb38b-474">March 22, 2019</span></span>
<span data-ttu-id="eb38b-475">버전 1904(빌드 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="eb38b-475">Version 1904 (build 11514.20004)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eb38b-476">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-476">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-477">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-477">Word</span></span> 
- <span data-ttu-id="eb38b-478">UI에 지속적으로 “변경 내용을 확인하는 중”이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-478">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-479">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-479">Excel</span></span>
- <span data-ttu-id="eb38b-480">워크시트 이동 후 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-480">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="eb38b-481">PDF로 저장한 후 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-481">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="eb38b-482">저장 대화 상자에서 일부 한국어 문자를 허용하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-482">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-483">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-483">PowerPoint</span></span>
- <span data-ttu-id="eb38b-484">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-484">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-485">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-485">Outlook</span></span>
- <span data-ttu-id="eb38b-486">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-486">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-487">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-487">Access</span></span>
- <span data-ttu-id="eb38b-488">Access에서 Access로 추가 바로 가기가 만들어졌다는 오류 메시지가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-488">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="eb38b-489">연결된 SharePoint의 데이터가 올바르게 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-489">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-490">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-490">Project</span></span>
- <span data-ttu-id="eb38b-491">언어 설정이 중국어에서 영어로 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-491">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="eb38b-492">SharePoint와 동기화할 때 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-492">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="eb38b-493">2019년 3월 15일</span><span class="sxs-lookup"><span data-stu-id="eb38b-493">March 15, 2019</span></span>
<span data-ttu-id="eb38b-494">버전 1904(빌드 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="eb38b-494">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eb38b-495">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="eb38b-495">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-496">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-496">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="eb38b-497">포커스 모드</span><span class="sxs-lookup"><span data-stu-id="eb38b-497">Focus Mode</span></span>

<span data-ttu-id="eb38b-498">보기 메뉴에서 포커스로 전환하면 주의를 산만하게 하는 요인들을 제거하고 작업에 집중할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-498">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="eb38b-499">Office 365 구독자만 해당합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-499">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eb38b-500">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-500">Getting Started:</span></span>

<span data-ttu-id="eb38b-501">보기 탭 리본 상태 막대 "포커스" 버튼의 "포커스 "버튼 </span><span class="sxs-lookup"><span data-stu-id="eb38b-501">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-502">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-502">Scenarios to Try:</span></span>

<span data-ttu-id="eb38b-503">포커스 모드를 시작하 고 주요 환경을 경험해 보세요.</span><span class="sxs-lookup"><span data-stu-id="eb38b-503">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eb38b-504">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-504">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-505">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-505">Word</span></span> 
- <span data-ttu-id="eb38b-506">PDF로 저장된 문서의 이미지에 잘못된 DPI가 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-506">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-507">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-507">Excel</span></span>
- <span data-ttu-id="eb38b-508">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-508">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-509">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-509">PowerPoint</span></span>
- <span data-ttu-id="eb38b-510">메모 창이 적절하게 열리거나 닫히지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-510">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="eb38b-511">비디오를 삭제할 때 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-511">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="eb38b-512">경우에 따라 응용 프로그램을 시작할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-512">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-513">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-513">Outlook</span></span>
- <span data-ttu-id="eb38b-514">일본어로 표시할 때 읽음 확인이 올바르지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-514">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-515">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-515">Access</span></span>
- <span data-ttu-id="eb38b-516">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-516">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-517">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-517">Project</span></span>
- <span data-ttu-id="eb38b-518">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-518">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="eb38b-519">2019년 3월 8일</span><span class="sxs-lookup"><span data-stu-id="eb38b-519">March 8, 2019</span></span> 
<span data-ttu-id="eb38b-520">버전 1903(빌드 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="eb38b-520">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eb38b-521">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="eb38b-521">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-522">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-522">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="eb38b-523">Microsoft Search를 통해 원하는 것을 찾으십시오.</span><span class="sxs-lookup"><span data-stu-id="eb38b-523">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="eb38b-524">Microsoft Search를 사용하면 모든 파일, 작업, 사람을 찾고 작업을 수행하는 데 필요한 도움을 받을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-524">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eb38b-525">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-525">Getting Started:</span></span>

- <span data-ttu-id="eb38b-526">이 기능은 머리글의 UI 위에 눈에 띄도록 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-526">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-527">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-527">Scenarios to Try:</span></span>

- <span data-ttu-id="eb38b-528">대학이나 최근 문서를 검색하거나 가장 자주 사용하는 리본 명령을 검색해 보세요.</span><span class="sxs-lookup"><span data-stu-id="eb38b-528">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="eb38b-529">화제나 주제를 검색하여 더 많은 정보를 얻으세요.</span><span class="sxs-lookup"><span data-stu-id="eb38b-529">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="eb38b-530">공동 작성</span><span class="sxs-lookup"><span data-stu-id="eb38b-530">Co-authoring</span></span>

<span data-ttu-id="eb38b-531">매크로 포함하는 문서가 잠기는게 번거롭습니까?</span><span class="sxs-lookup"><span data-stu-id="eb38b-531">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="eb38b-532">이제 비즈니스용 OneDrive의 .docm 파일을 사용하여 여러 작성자가 동시에 편집할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-532">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eb38b-533">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-533">Getting Started:</span></span>

<span data-ttu-id="eb38b-534">사용자가 이 기능에 액세스 하기 위해 UI에서 버튼을 누를 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-534">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="eb38b-535">OneDrive for Business docm 파일에서는 기본적으로 활성화되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-535">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="eb38b-536">따라서 사용자는 OneDrive for Business에 docm 파일을 저장하여 사용해 봐야 합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-536">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-537">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-537">Scenarios to Try:</span></span>

<span data-ttu-id="eb38b-538">OneDrive for Business에 docm 파일을 만들고 동료와 공유하고 공동 작업해 보십시오!</span><span class="sxs-lookup"><span data-stu-id="eb38b-538">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eb38b-539">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-539">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-540">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-540">Word</span></span> 
- <span data-ttu-id="eb38b-541">Options에서 ‘ESC’를 누를 때 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-541">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="eb38b-542">메모에 회신할 때 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-542">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="eb38b-543">Word에서 PowerPoint Online으로 복사 및 붙여넣기를 할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-543">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-544">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-544">Excel</span></span>
- <span data-ttu-id="eb38b-545">보호되고 편집 가능한 문서를 열었을 때 Excel에서 셀을 복사하는 경우 높은 CPU 사용량을 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-545">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-546">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-546">PowerPoint</span></span>
- <span data-ttu-id="eb38b-547">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-547">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-548">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-548">Outlook</span></span>
- <span data-ttu-id="eb38b-549">Outlook Search가 선택한 연대순 정렬을 반영하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-549">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="eb38b-550">"이 작업 열기" 워크플로우 리본 버튼이 특정 이메일에 응답하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-550">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="eb38b-551">사용자가 회의실 찾기를 통해 사용 가능한 회의실을 선택한 후 Outlook이 사내 회의실을 지우지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-551">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-552">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-552">Access</span></span>
- <span data-ttu-id="eb38b-553">어두운 테마에서 흰색 배경에 흰색 텍스트가 있던 저장된 가져오기/내보내기 대화 상자의 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-553">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="eb38b-554">테이블 디자인에서 사용자가 표시 컨트롤 속성의 Yes/No 필드를 Textbox로 설정하지 못했던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-554">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-555">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-555">Project</span></span>
- <span data-ttu-id="eb38b-556">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-556">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="eb38b-557">2019년 3월 1일</span><span class="sxs-lookup"><span data-stu-id="eb38b-557">March 1, 2019</span></span> 
<span data-ttu-id="eb38b-558">버전 1903(빌드 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="eb38b-558">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eb38b-559">새로운 기능</span><span class="sxs-lookup"><span data-stu-id="eb38b-559">What's New</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-560">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-560">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="eb38b-561">동기화 중 변경 내용 추적, 메모, 실시간 공동 작업을 표시하는 색상</span><span class="sxs-lookup"><span data-stu-id="eb38b-561">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="eb38b-562">이제 제품의 개선을 통해 공동 작업자의 메모, 변경 내용 추적 및 커서를 동일한 색상으로 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-562">Colors for Track Changes, Comments and Real-Time Collaboration in Sync: Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eb38b-563">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-563">Getting Started:</span></span>

<span data-ttu-id="eb38b-564">다른 사용자가 연 SharePoint 또는 OneDrive문서를 엽니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-564">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="eb38b-565">사용자의 변경 내용 추적과 해당 사용자 커서의 색이 일치 하는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-565">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-566">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-566">Scenarios to Try:</span></span>

<span data-ttu-id="eb38b-567">다른 사용자가 연 SharePoint 또는 OneDrive문서를 엽니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-567">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="eb38b-568">사용자의 변경 내용 추적과 해당 사용자 커서의 색이 일치 하는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-568">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eb38b-569">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-569">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-570">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-570">Word</span></span> 
- <span data-ttu-id="eb38b-571">Options에서 ‘ESC’를 누를 때 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-571">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="eb38b-572">Word에서 PowerPoint Online으로 복사 및 붙여넣기를 할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-572">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-573">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-573">Excel</span></span>
- <span data-ttu-id="eb38b-574">보호되고 편집 가능한 문서를 열었을 때 Excel에서 셀을 복사하는 경우 높은 CPU 사용량을 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-574">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-575">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-575">PowerPoint</span></span>
- <span data-ttu-id="eb38b-576">PowerPoint에서 @Mentions를 사용 시의 슬라이드 이미지 크기 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-576">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-577">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-577">Outlook</span></span>
- <span data-ttu-id="eb38b-578">Outlook Search가 선택한 연대순 정렬을 반영하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-578">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="eb38b-579">"이 작업 열기" 워크플로우 리본 버튼이 특정 이메일에 응답하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-579">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="eb38b-580">사용자가 회의실 찾기를 통해 사용 가능한 회의실을 선택한 후 Outlook이 사내 회의실을 지우지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-580">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-581">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-581">Access</span></span>
- <span data-ttu-id="eb38b-582">데이터 전송 발신기와 테이블의 재연결을 확인 시 표시되는 프롬프트 텍스트를 업데이트했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-582">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="eb38b-583">어두운 테마에서 흰색 배경에 흰색 텍스트가 있던 저장된 가져오기/내보내기 대화 상자의 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-583">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="eb38b-584">테이블 디자인에서 사용자가 표시 컨트롤 속성의 Yes/No 필드를 Textbox로 설정하지 못했던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-584">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-585">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-585">Project</span></span>
- <span data-ttu-id="eb38b-586">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-586">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="eb38b-587">2019년 2월 15일</span><span class="sxs-lookup"><span data-stu-id="eb38b-587">February 15, 2019</span></span> 
<span data-ttu-id="eb38b-588">버전 1903(빌드 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="eb38b-588">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eb38b-589">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="eb38b-589">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-590">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-590">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="eb38b-591">모핑 전환 개선 사항 - 이름으로 모핑</span><span class="sxs-lookup"><span data-stu-id="eb38b-591">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="eb38b-592">모핑하려는 도형 지정</span><span class="sxs-lookup"><span data-stu-id="eb38b-592">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eb38b-593">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-593">Getting Started:</span></span>

- <span data-ttu-id="eb38b-594">두 개체를 같은 개체로 처리하도록 모핑을 사용하기 위해 사용자는 선택 창을 사용하여 도형 이름을 바꿀 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-594">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="eb38b-595">이름은 "!!"로 시작해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-595">The name must be prefaced with “!!”</span></span> <span data-ttu-id="eb38b-596">모핑에서 이름을 사용하여 기본 일치 동작을 무시하도록 하려면, 예를 들어 “!!이름”</span><span class="sxs-lookup"><span data-stu-id="eb38b-596">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="eb38b-597">사용자는 계속 “!!”로 시작하지 않는 셰이프 이름을 바꿀 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-597">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="eb38b-598">모핑 작동 방식의 변경에 대해 우려할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-598">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-599">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-599">Scenarios to Try:</span></span>

- <span data-ttu-id="eb38b-600">슬라이드에 도형을 삽입합니다. 직사각형을 가정해 보겠습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-600">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="eb38b-601">새 슬라이드를 만듭니다 
</span><span class="sxs-lookup"><span data-stu-id="eb38b-601">Create a new slide</span></span>
- <span data-ttu-id="eb38b-602">두 번째 슬라이드에 다른 도형을 삽입합니다. 삼각형을 가정해 보겠습니다</span><span class="sxs-lookup"><span data-stu-id="eb38b-602">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="eb38b-603">SelectionPane을 열고, 슬라이드 1에서 직사각형을 "!!도형"으로 이름을 바꾸고, 슬라이드 2에서 삼각형을 “!!도형”으로 이름을 바꿉니다</span><span class="sxs-lookup"><span data-stu-id="eb38b-603">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="eb38b-604">두 번째 슬라이드에 모핑 적용</span><span class="sxs-lookup"><span data-stu-id="eb38b-604">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="eb38b-605">모핑 전환 개선 사항 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="eb38b-605">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="eb38b-606">더 원활한 전환으로 SmartArt 모핑</span><span class="sxs-lookup"><span data-stu-id="eb38b-606">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eb38b-607">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-607">Getting Started:</span></span>

<span data-ttu-id="eb38b-608">SmartArt를 사용하는 것과 같은 방법으로 모핑 사용</span><span class="sxs-lookup"><span data-stu-id="eb38b-608">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-609">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-609">Scenarios to Try:</span></span>

- <span data-ttu-id="eb38b-610">슬라이드에 SmartArt 삽입</span><span class="sxs-lookup"><span data-stu-id="eb38b-610">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="eb38b-611">슬라이드를 복제합니다</span><span class="sxs-lookup"><span data-stu-id="eb38b-611">Duplicate the Slide</span></span>
- <span data-ttu-id="eb38b-612">복제된 슬라이드에서 SmartArt를 크기 조정/변경/이동합니다</span><span class="sxs-lookup"><span data-stu-id="eb38b-612">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="eb38b-613">복제된 슬라이드에서 모핑 적용</span><span class="sxs-lookup"><span data-stu-id="eb38b-613">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="eb38b-614">모핑 전환 개선 사항 - 표</span><span class="sxs-lookup"><span data-stu-id="eb38b-614">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="eb38b-615">더 원활한 전환으로 표 모핑</span><span class="sxs-lookup"><span data-stu-id="eb38b-615">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eb38b-616">시작:</span><span class="sxs-lookup"><span data-stu-id="eb38b-616">Getting Started:</span></span>
<span data-ttu-id="eb38b-617">표를 사용하는 것과 같은 방법으로 모핑 사용</span><span class="sxs-lookup"><span data-stu-id="eb38b-617">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-618">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-618">Scenarios to Try:</span></span>

- <span data-ttu-id="eb38b-619">슬라이드에서 표 추가</span><span class="sxs-lookup"><span data-stu-id="eb38b-619">Insert a Table in a slide</span></span>
- <span data-ttu-id="eb38b-620">슬라이드를 복제합니다</span><span class="sxs-lookup"><span data-stu-id="eb38b-620">Duplicate the slide</span></span>
- <span data-ttu-id="eb38b-621">복제된 슬라이드에서 Table을 크기 조정/변경/이동합니다</span><span class="sxs-lookup"><span data-stu-id="eb38b-621">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="eb38b-622">복제된 슬라이드에서 모핑 적용</span><span class="sxs-lookup"><span data-stu-id="eb38b-622">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="eb38b-623">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher 및 Visio</span><span class="sxs-lookup"><span data-stu-id="eb38b-623">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="eb38b-624">원활한 계정 전환</span><span class="sxs-lookup"><span data-stu-id="eb38b-624">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="eb38b-625">새 계정 관리자를 통해 사용자의 모든 회사 및 개인 계정을 한곳에서 볼 수 있으며, 사용자가 직접 여러 계정 간에 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-625">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="eb38b-626">업데이트된 환경에서는 사용자의 로그인 방법이 명확해지며, 이제 먼저 로그아웃하거나 복잡한 대화 상자를 거치지 않고 회사 및 개인 계정 사이를 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-626">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="eb38b-628">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="eb38b-628">Scenarios to Try:</span></span>
- <span data-ttu-id="eb38b-629">계정 간 전환</span><span class="sxs-lookup"><span data-stu-id="eb38b-629">Switch between accounts</span></span>
- <span data-ttu-id="eb38b-630">새 계정 추가 [참고: 먼저 파일 | 계정 | 연결된 서비스에 가서 회사 계정에 연결된 개인 서비스를 제거 또는 그 반대로 하고자 할 수 있습니다]</span><span class="sxs-lookup"><span data-stu-id="eb38b-630">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="eb38b-631">계정에서 로그아웃</span><span class="sxs-lookup"><span data-stu-id="eb38b-631">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="eb38b-632">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-632">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-633">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-633">Word</span></span> 
- <span data-ttu-id="eb38b-634">표 및 이미지에 대한 상황에 맞는 미리 보기 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-634">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-635">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-635">Excel</span></span>
- <span data-ttu-id="eb38b-636">자동 필터 검색 필드의 텍스트는 검은색 테마에서 흰색인 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-636">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="eb38b-637">새 Office 추가 기능에 있는 동의 UI 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-637">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-638">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-638">PowerPoint</span></span>
- <span data-ttu-id="eb38b-639">노트북 또는 태블릿에 슬라이드 쇼를 표시할 때 자동으로 확장하는 디스플레이 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-639">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-640">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-640">Outlook</span></span>
- <span data-ttu-id="eb38b-641">OneNote로 보내기 버튼 디스플레이 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-641">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-642">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-642">Access</span></span>
- <span data-ttu-id="eb38b-643">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-643">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-644">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-644">Project</span></span>
- <span data-ttu-id="eb38b-645">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-645">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="eb38b-646">2019년 2월 11일</span><span class="sxs-lookup"><span data-stu-id="eb38b-646">February 11, 2019</span></span>
<span data-ttu-id="eb38b-647">버전 1903(빌드 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="eb38b-647">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="eb38b-648">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="eb38b-648">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-649">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-649">Word</span></span> 
- <span data-ttu-id="eb38b-650">일부 사용자 지정된 스타일을 Word Online에 적용할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-650">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="eb38b-651">Word에서 서식 있는 개체의 컨텍스트 미리 보기 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-651">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="eb38b-652">Word에서 목록을 붙여넣으면 작동이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-652">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-653">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-653">Excel</span></span>
- <span data-ttu-id="eb38b-654">통화 기호가 없을 때 숫자 서식 뒤에 추가된 공백이 더 이상 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-654">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="eb38b-655">주식 자동 검색 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-655">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-656">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-656">PowerPoint</span></span>
- <span data-ttu-id="eb38b-657">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-657">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-658">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-658">Outlook</span></span>
- <span data-ttu-id="eb38b-659">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-659">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-660">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-660">Access</span></span>
- <span data-ttu-id="eb38b-661">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-661">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-662">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-662">Project</span></span>
- <span data-ttu-id="eb38b-663">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-663">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="eb38b-664">2019년 2월 1일</span><span class="sxs-lookup"><span data-stu-id="eb38b-664">February 1, 2019</span></span> 
<span data-ttu-id="eb38b-665">버전 1902(빌드 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="eb38b-665">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="eb38b-666">중요 수정 사항</span><span class="sxs-lookup"><span data-stu-id="eb38b-666">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="eb38b-667">Word</span><span class="sxs-lookup"><span data-stu-id="eb38b-667">Word</span></span> 
- <span data-ttu-id="eb38b-668">임베디드 Excel 테이블에서 셀 크기를 조정하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-668">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="eb38b-669">그리기 캔버스에서 도형 복사 / 붙여 넣기 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-669">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="eb38b-670">Excel</span><span class="sxs-lookup"><span data-stu-id="eb38b-670">Excel</span></span>
- <span data-ttu-id="eb38b-671">Excel 웹 응용 프로그램에서 파일을 열 때 발생하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-671">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="eb38b-672">파일 이름 크기로 인해 .XLSX가 실패하여 CSV 파일을 저장하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-672">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="eb38b-673">컨텍스트 메뉴를 수정하여 컨텍스트 메뉴 옵션을 표시했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-673">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eb38b-674">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eb38b-674">PowerPoint</span></span>
- <span data-ttu-id="eb38b-675">사용자가 키보드 단축키 ctrl + alt + 7 / ctrl + alt + 8을 사용하여 대괄호를 입력할 수 없는 부분을 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-675">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="eb38b-676">PPT에 로컬 비디오를 삽입하면 'C'드라이브의 디스크 공간이 줄어드는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-676">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="eb38b-677">일부 사용자에게 표시되지 않는 Microsoft Stream에 게시 버튼이 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-677">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="eb38b-678">Outlook</span><span class="sxs-lookup"><span data-stu-id="eb38b-678">Outlook</span></span>
- <span data-ttu-id="eb38b-679">일정의 작업 보기에 작업 제목이 올바르게 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-679">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="eb38b-680">Access</span><span class="sxs-lookup"><span data-stu-id="eb38b-680">Access</span></span>
- <span data-ttu-id="eb38b-681">차트 관련 배율 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-681">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="eb38b-682">Project</span><span class="sxs-lookup"><span data-stu-id="eb38b-682">Project</span></span>
- <span data-ttu-id="eb38b-683">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="eb38b-683">Various performance and stability fixes</span></span>
