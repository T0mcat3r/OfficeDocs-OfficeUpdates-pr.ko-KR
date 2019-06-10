---
title: Office 참가자에 대한 릴리스 정보
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 6/7/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 초기 참가자 대상 그룹에게 주요 새 기능, 수정 사항 또는 알려진 문제의 최신 목록을 제공합니다.
ms.openlocfilehash: 6fca274c0acf56aa2ba5d926e7b4f61a1c8f33d1
ms.sourcegitcommit: 664eea7a20324858da3503f54d0efac97e2299e4
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/07/2019
ms.locfileid: "34773754"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="2cf0c-103">Office 참가자에 대한 릴리스 정보</span><span class="sxs-lookup"><span data-stu-id="2cf0c-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="2cf0c-104">이 문서에는 Windows 데스크톱용 Word, Excel, PowerPoint, Outlook, Access 및 Project 의 참가자 빌드에 대한 릴리스 정보가 포함되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="2cf0c-105">매주 Microsoft는 흥미로운 새 기능, 중요한 수정 사항, 알리고자 하는 중요한 문제를 강조합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="2cf0c-106">Microsoft는 일정 기간 동안 자주 참가자들에게 기능을 배포하며 때로는 수정 사항도 배포합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="2cf0c-107">이로서 더욱 광범위한 사용자들에게 기능을 릴리스하기 전에 원활하게 작동하는지 확인할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="2cf0c-108">따라서 아래에 설명된 기능이 보이지 않더라도 곧 제공되게 되므로 걱정할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="2cf0c-109">릴리스 정보는 매주 게시되며 여러 빌드의 컴파일일 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="2cf0c-110">릴리스 정보 게시 날짜는 실제 빌드 릴리스 날짜와 일치하지 않을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-110">The release notes publication date may not match the actual build release date</span></span>


## <a name="june-7-2019"></a><span data-ttu-id="2cf0c-111">2019년 6월 7일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-111">June 7, 2019</span></span>
<span data-ttu-id="2cf0c-112">버전 1907 (빌드 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-112">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-113">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-113">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-114">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-114">Word</span></span> 
- <span data-ttu-id="2cf0c-115">문장의 첫 글자를 대문자로 자동 고침을 설정했을 때 Word에서 종종 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-115">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="2cf0c-116">SharePoint에서 문서를 편집할 때의 성능이 개선되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-116">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="2cf0c-117">Adobe Illustrator에서 만든 벡터 기반 이미지가 올바르게 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-117">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-118">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-118">Excel</span></span>
- <span data-ttu-id="2cf0c-119">매크로가 기록될 때 정렬 필드가 제대로 설정 되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-119">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="2cf0c-120">배열 수식을 다시 계산하는 동안 멈춤 또는 충돌이 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-120">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-121">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-121">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-122">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-122">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-123">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-123">Outlook</span></span>
- <span data-ttu-id="2cf0c-124">인라인 첨부 파일의 크기가 잘못 조정되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-124">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-125">액세스</span><span class="sxs-lookup"><span data-stu-id="2cf0c-125">Access</span></span>
- <span data-ttu-id="2cf0c-126">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-126">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-127">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-127">Project</span></span>
- <span data-ttu-id="2cf0c-128">일정 기간의 작업표에서 과제 완료 날짜가 간혹 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-128">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="2cf0c-129">이전 버전에서 프로젝트를 열 때 완료율 값이 잘못될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-129">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="2cf0c-130">2019년 5월 31일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-130">May 31, 2019</span></span>
<span data-ttu-id="2cf0c-131">버전 1906 (빌드 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-131">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2cf0c-132">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-132">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-133">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-133">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="2cf0c-134">현재 고객 지원팀에 문의하기 위한 대화 상자는 도킹할 수 있으며 오른쪽에 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-134">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="2cf0c-135">고객 지원팀에 문의하는데 사용되는 대화 상자가 이제 오른쪽 창에 표시되고 도킹된 창으로 시작 됩니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-135">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="2cf0c-136">이메일에서 잉크로 표시하세요!</span><span class="sxs-lookup"><span data-stu-id="2cf0c-136">Ink in Your Email!</span></span>

<span data-ttu-id="2cf0c-137">이제 Outlook 전자 메일에 그림을 그리고 주석을 달 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-137">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-138">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-138">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="2cf0c-139">Word로 문서 링크 열기</span><span class="sxs-lookup"><span data-stu-id="2cf0c-139">Open document links in Word</span></span>

<span data-ttu-id="2cf0c-140">Office에서 문서 링크를 클릭 시 기본 설정을 업데이트하여 Word 앱에서 기본적으로 열리도록 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-140">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="2cf0c-141">기본 설정을 업데이트하려면 파일 ->옵션->고급->링크 처리로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-141">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="2cf0c-142">자세한 정보: https://support.office.com/ko-KR/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="2cf0c-142">Learn morehttps://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2cf0c-143">시작하기:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-143">Getting Started:</span></span>

<span data-ttu-id="2cf0c-144">기능은 기본적으로 해제됩니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-144">Feature will default to off.</span></span> <span data-ttu-id="2cf0c-145">사용자는 옵션->고급->링크 처리 설정으로 이동하거나 Win32 WXP 앱이 옵트인 경험을 가능하게할 시 옵트인하여 기능을 켤 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-145">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="2cf0c-146">사용자가 Outlook/Word/PowerPoint/Excel에서 비즈니스/Sharepoint용 OneDrive/OneDrive에저장된 Word/PowerPoint/Excel 파일로의 링크를 클릭하는 경우 기본적으로 브라우저가 아닌 해당 Office 응용 프로그램에서 링크가 열립니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-146">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="2cf0c-147">이 기본 설정을 변경하려면 사용자는 Outlook/Word/Excel/PowerPoint에서 다음의 설정을 업데이트하면 됩니다:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-147">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="2cf0c-148">파일->옵션->고급->링크 처리</span><span class="sxs-lookup"><span data-stu-id="2cf0c-148">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="2cf0c-149">이 설정은 Outlook/Word/PowerPoint/Excel에서 공유되며 이들 앱에서 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-149">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-150">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-150">Scenarios to Try:</span></span>

<span data-ttu-id="2cf0c-151">옵트인 (opt in) 경험을 사용하려면 - Outlook/Word/PowerPoint/Excel에서 OneDrive/SharePoint에 저장된 Word 문서로의 링크를 엽니다 - 30일 창에서 이 과정을 두 번 시행합니다..</span><span class="sxs-lookup"><span data-stu-id="2cf0c-151">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="2cf0c-152">옵트인(opt-in) 한 후에는 기본적으로 Win32 앱에서 링크를 시작합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-152">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-153">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-153">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="2cf0c-154">PowerPoint에서 프레젠테이션을 링크를 엽니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-154">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="2cf0c-155">Office에서 프레젠테이션 링크를 클릭 시 기본 설정을 업데이트하여 PowerPoint 앱에서 기본적으로 열리도록 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-155">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="2cf0c-156">기본 설정을 업데이트하려면 파일 ->옵션->고급->링크 처리로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-156">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="2cf0c-157">자세한 정보: https://support.office.com/ko-KR/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="2cf0c-157">Learn morehttps://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2cf0c-158">시작하기:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-158">Getting Started:</span></span>

<span data-ttu-id="2cf0c-159">기능은 기본적으로 해제됩니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-159">Feature will default to off.</span></span> <span data-ttu-id="2cf0c-160">사용자는 옵션->고급->링크 처리 설정으로 이동하거나 Win32 WXP 앱이 옵트인 경험을 가능하게할 시 옵트인하여 기능을 켤 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-160">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="2cf0c-161">사용자가 Outlook/Word/PowerPoint/Excel에서 비즈니스/Sharepoint용 OneDrive/OneDrive에저장된 Word/PowerPoint/Excel 파일로의 링크를 클릭하는 경우 기본적으로 브라우저가 아닌 해당 Office 응용 프로그램에서 링크가 열립니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-161">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="2cf0c-162">이 기본 설정을 변경하려면 사용자는 Outlook/Word/Excel/PowerPoint에서 다음의 설정을 업데이트하면 됩니다:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-162">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="2cf0c-163">파일->옵션->고급->링크 처리</span><span class="sxs-lookup"><span data-stu-id="2cf0c-163">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="2cf0c-164">이 설정은 Outlook/Word/PowerPoint/Excel에서 공유되며 이들 앱에서 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-164">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-165">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-165">Scenarios to Try:</span></span>

<span data-ttu-id="2cf0c-166">옵트인 (opt in) 경험을 사용하려면 - Outlook/Word/PowerPoint/Excel에서 OneDrive/SharePoint에 저장된 PowerPoint 프레젠테이션으로의 링크를 엽니다 - 30일 창에서 이 과정을 두 번 시행합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-166">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="2cf0c-167">옵트인(opt-in) 한 후에는 기본적으로 Win32 앱에서 링크를 시작합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-167">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-168">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-168">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="2cf0c-169">Excel에서 워크북 링크 열기</span><span class="sxs-lookup"><span data-stu-id="2cf0c-169">Open workbook links in Excel</span></span>

<span data-ttu-id="2cf0c-170">Office에서 워크북 링크를 클릭 시 기본 설정을 업데이트하여 Excel 앱에서 기본적으로 열리도록 할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-170">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="2cf0c-171">기본 설정을 업데이트하려면 파일->옵션->고급->링크 처리로 이동합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-171">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="2cf0c-172">자세한 정보: https://support.office.com/ko-KR/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="2cf0c-172">Learn morehttps://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2cf0c-173">시작하기:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-173">Getting Started:</span></span>

<span data-ttu-id="2cf0c-174">기능은 기본적으로 해제됩니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-174">Feature will default to off.</span></span> <span data-ttu-id="2cf0c-175">사용자는 옵션->고급->링크 처리 설정으로 이동하거나 Win32 WXP 앱이 옵트인 경험을 가능하게할 시 옵트인하여 기능을 켤 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-175">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="2cf0c-176">사용자가 Outlook/Word/PowerPoint/Excel에서 비즈니스/Sharepoint용 OneDrive/OneDrive에저장된 Word/PowerPoint/Excel 파일로의 링크를 클릭하는 경우 기본적으로 브라우저가 아닌 해당 Office 응용 프로그램에서 링크가 열립니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-176">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="2cf0c-177">이 기본 설정을 변경하려면 사용자는 Outlook/Word/Excel/PowerPoint에서 다음의 설정을 업데이트하면 됩니다:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-177">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="2cf0c-178">파일->옵션->고급->링크 처리</span><span class="sxs-lookup"><span data-stu-id="2cf0c-178">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="2cf0c-179">이 설정은 Outlook/Word/PowerPoint/Excel에서 공유되며 이들 앱에서 설정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-179">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-180">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-180">Scenarios to Try:</span></span>

<span data-ttu-id="2cf0c-181">옵트인 (opt in) 경험을 사용하려면 - Outlook/Word/PowerPoint/Excel에서 OneDrive/SharePoint에 저장된 Excel 워크북으로의 링크를 엽니다 - 30일 창에서 이 과정을 두 번 시행합니다..</span><span class="sxs-lookup"><span data-stu-id="2cf0c-181">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="2cf0c-182">옵트인(opt-in) 한 후에는 기본적으로 Win32 앱에서 링크를 시작합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-182">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-183">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-183">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2cf0c-184">모두</span><span class="sxs-lookup"><span data-stu-id="2cf0c-184">All</span></span>
- <span data-ttu-id="2cf0c-185">자동 저장이 비활성화된 상태에서도 파일이 간혹 자동으로 저장되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-185">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-186">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-186">Word</span></span> 
- <span data-ttu-id="2cf0c-187">일부 사용자가 SharePoint에 저장하지 못하게 하는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-187">We fixed an issue which prevented some users from saving files to cloud locations</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-188">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-188">Excel</span></span>
- <span data-ttu-id="2cf0c-189">비활성 필터에 대해 올바르지 않은 아이콘이 표시될 수 있는 문제가 해결되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-189">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-190">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-190">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-191">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-191">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-192">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-192">Outlook</span></span>
- <span data-ttu-id="2cf0c-193">일부 사용자가 그룹 일정 보기에서 오프라인으로 잘못 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-193">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="2cf0c-194">SafeLink가 후행 공백이 있는 URL을 분석하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-194">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="2cf0c-195">방이 비 작업시간 외에 사용가능 하도록 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-195">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-196">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-196">Access</span></span>
- <span data-ttu-id="2cf0c-197">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-197">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-198">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-198">Project</span></span>
- <span data-ttu-id="2cf0c-199">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-199">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="2cf0c-200">2019년 5월 24일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-200">May 24, 2019</span></span>
<span data-ttu-id="2cf0c-201">버전 1906(빌드 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-201">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2cf0c-202">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-202">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="2cf0c-203">사용자 환경 업데이트</span><span class="sxs-lookup"><span data-stu-id="2cf0c-203">User Experience Updates</span></span>

<span data-ttu-id="2cf0c-204">출시 예정이었던 업데이트가 이제 시행되었으며, 이는 간소화된 리본과 폴더 창, 메시지 목록 및 읽기 창의 시각적 새로 고침 기능을 특징으로 합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-204">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-205">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-205">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2cf0c-206">모두</span><span class="sxs-lookup"><span data-stu-id="2cf0c-206">All</span></span>

- <span data-ttu-id="2cf0c-207">채팅 창이 표시되지 않는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-207">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-208">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-208">Word</span></span> 
- <span data-ttu-id="2cf0c-209">경우에 따라 Word에서 문법적 오류로 인해 텍스트가 잘못 강조될 수있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-209">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-210">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-210">Excel</span></span>
- <span data-ttu-id="2cf0c-211">차트 요소에 올바르지 않은 아이콘이 사용되는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-211">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="2cf0c-212">동일한 통합 문서가 이미 열려 있는 경우 VBA 스크립트에서 잘못 된 통합 문서를 활성화할 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-212">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-213">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-213">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-214">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-214">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-215">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-215">Outlook</span></span>
- <span data-ttu-id="2cf0c-216">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-216">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-217">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-217">Access</span></span>
- <span data-ttu-id="2cf0c-218">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-218">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-219">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-219">Project</span></span>
- <span data-ttu-id="2cf0c-220">작업 표시줄로 전환한 후 프로젝트가 중단될 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-220">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="2cf0c-221">2019년 5월 17일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-221">May 17, 2019</span></span>
<span data-ttu-id="2cf0c-222">버전 1906(빌드 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-222">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2cf0c-223">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-223">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-224">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-224">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="2cf0c-225">사용자 환경 업데이트</span><span class="sxs-lookup"><span data-stu-id="2cf0c-225">User Experience Updates</span></span>

<span data-ttu-id="2cf0c-226">출시 예정이었던 업데이트가 이제 시행되었으며, 이는 간소화된 리본과 폴더 창, 메시지 목록 및 읽기 창의 시각적 새로 고침 기능을 특징으로 합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-226">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2cf0c-227">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-227">Getting Started:</span></span>

<span data-ttu-id="2cf0c-228">이러한 변경 사항은 새로운 기본 UI의 일부가됩니다. 12월 중순 이래로 출시 예정 스위치 뒤에 숨겨진 상태였지만 100% prod가 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-228">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="2cf0c-229">사용자 지정이 가능한 간소화된 리본</span><span class="sxs-lookup"><span data-stu-id="2cf0c-229">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="2cf0c-230">클래식 및 요약 보기 간의 간편한 전환 및 명령 고정/고정 해제가 쉽도록 사용자 지정 가능</span><span class="sxs-lookup"><span data-stu-id="2cf0c-230">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2cf0c-231">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-231">Getting Started:</span></span>

<span data-ttu-id="2cf0c-232">사용자는 출시 예정(초기 설정)을 켜고 리본의 갈매기 모양을 클릭해 클래식 멀티 라인 리본과 새로운 단순 싱글 라인 리본 사이를 전환하여 간소화된 리본을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-232">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-233">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-233">Scenarios to Try:</span></span>

<span data-ttu-id="2cf0c-234">클래식 리본에서 간단한 리본으로 전환</span><span class="sxs-lookup"><span data-stu-id="2cf0c-234">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="2cf0c-235">즐겨찾기 선택 작업</span><span class="sxs-lookup"><span data-stu-id="2cf0c-235">Pick your favorite action</span></span>

<span data-ttu-id="2cf0c-236">플래그를 사용하지 않고 삭제?</span><span class="sxs-lookup"><span data-stu-id="2cf0c-236">Don't use Flag and Delete?</span></span> <span data-ttu-id="2cf0c-237">[보관] 또는 [읽은 상태로 표시]는 어떤가요?</span><span class="sxs-lookup"><span data-stu-id="2cf0c-237">How about Archive or Mark as Read?</span></span> <span data-ttu-id="2cf0c-238">가장 많이 사용하는 명령으로 빠른 작업 메뉴를 사용자 지정합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-238">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2cf0c-239">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-239">Getting Started:</span></span>

<span data-ttu-id="2cf0c-240">빠른 작업을 선택하려면 메시지 목록의 이메일을 마우스 오른쪽 버튼으로 클릭하여 상황에 맞는 메뉴를 불러 오십시오.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-240">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="2cf0c-241">그런 다음 "빠른 작업 설정..."을 클릭합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-241">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-242">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-242">Scenarios to Try:</span></span>

<span data-ttu-id="2cf0c-243">기본값을 플래그에서 변경하고 보관으로 삭제, 이동, 읽은 상태로 표시하거나 메시지 목록을 더 깔끔하게 하기 위해 모두 없앱니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-243">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="2cf0c-244">넓은 레이아웃 아니면 더 좁은 레이아웃?</span><span class="sxs-lookup"><span data-stu-id="2cf0c-244">Relaxed or tighter layout?</span></span> <span data-ttu-id="2cf0c-245">선택</span><span class="sxs-lookup"><span data-stu-id="2cf0c-245">You choose</span></span>

<span data-ttu-id="2cf0c-246">더 좁은 간격을 사용하면 항목 간에 더 넓은 공백을 할지 또는 더 좁은 레이아웃을 사용하여 더 많은 항목을 표시할지를 결정할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-246">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2cf0c-247">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-247">Getting Started:</span></span>

<span data-ttu-id="2cf0c-248">보기 탭, 촘촘한 간격 사용 확인란 - 기본 리본의 메시지 그룹, 단순 리본의 현재보기 설정</span><span class="sxs-lookup"><span data-stu-id="2cf0c-248">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-249">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-249">Scenarios to Try:</span></span>

<span data-ttu-id="2cf0c-250">Outlook을 사용하여 설정을 사용하거나 사용하지 않고 전자 메일을 분류하고 작성합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-250">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="2cf0c-251">간격을 좁게 사용하면 페이지당 메시지가 더 많이 표시되고 작성 양식의 컨트롤이 보다 간소화됩니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-251">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="2cf0c-252">Onedrive 동기화 클라이언트를 사용할 때 MRU 항목 중복 제거</span><span class="sxs-lookup"><span data-stu-id="2cf0c-252">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="2cf0c-253">mru 항목을 제거하고 동기화된 데이터에 대한 복사 동작으로 보다 신속하게 연결할 수 있도록 하여 클라우드 첨부가 포함된 onedrive 동기화 클라이언트와보다 잘 통합됩니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-253">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2cf0c-254">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-254">Getting Started:</span></span>

<span data-ttu-id="2cf0c-255">OneDrive 동기화 클라이언트를 사용하면 첨부 파일 MRU에서 중복 된 파일이 더 이상 표시되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-255">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-256">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-256">Scenarios to Try:</span></span>

<span data-ttu-id="2cf0c-257">OneDrive 동기화 클라이언트 사용 및 Outlook 데스크톱의 파일 첨부 메뉴 사용</span><span class="sxs-lookup"><span data-stu-id="2cf0c-257">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="2cf0c-258">여러 폴더가 있는 사서함에 대한 공유 폴더 동기화 기능 향상</span><span class="sxs-lookup"><span data-stu-id="2cf0c-258">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="2cf0c-259">수년 동안 Outlook은 공유 사서함을 동기화할 때 폴더 수를 최대 500개로 제한해 왔습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-259">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="2cf0c-260">이 변경을 통해 Outlook은 이 500개 폴더 제한이 더 이상 적용되지 않도록 동기화 방식을 개선했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-260">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2cf0c-261">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-261">Getting Started:</span></span>

<span data-ttu-id="2cf0c-262">사서함에 1000 폴더를 만들고, 다른 사용자에 게 사서함에 대 한 액세스 권한을 부여 하 고, "다른 사용자"를 위한 Outlook 프로필을 만들고, 동기화가 작동 하는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-262">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-263">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-263">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="2cf0c-264">조금만 지우기</span><span class="sxs-lookup"><span data-stu-id="2cf0c-264">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2cf0c-265">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-265">Getting Started:</span></span>

<span data-ttu-id="2cf0c-266">그리기 탭으로 이동하십시오. 지우개 드롭 다운을 선택하십시오.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-266">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="2cf0c-267">작은 지우개 또는 중간 지우개를 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-267">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-268">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-268">Scenarios to Try:</span></span>

<span data-ttu-id="2cf0c-269">그리기 탭으로 이동하 고 펜을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-269">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="2cf0c-270">잉크 스트로크를 그립니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-270">Draw an ink stroke.</span></span> <span data-ttu-id="2cf0c-271">지우개 드롭다운을 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-271">Select the Eraser dropdown.</span></span> <span data-ttu-id="2cf0c-272">작은 지우개 또는 중간 지우개를 선택합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-272">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="2cf0c-273">잉크 스트로크를 조금만 지웁니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-273">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-274">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-274">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2cf0c-275">모두</span><span class="sxs-lookup"><span data-stu-id="2cf0c-275">All</span></span> 
- <span data-ttu-id="2cf0c-276">일부 사용자가 PDF를 저장하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-276">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="2cf0c-277">사용자가 32 비트 시스템에서 대용량 파일을 저장하는 데 영향을 줄 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-277">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-278">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-278">Word</span></span> 
- <span data-ttu-id="2cf0c-279">받아쓰기 기능의 응답성을 크게 향상 시켰습니다</span><span class="sxs-lookup"><span data-stu-id="2cf0c-279">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-280">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-280">Excel</span></span>
- <span data-ttu-id="2cf0c-281">터치 스크린 장치에서 두 번 클릭 이벤트가 실패 할 수 있는 문제가 수정되었습니다</span><span class="sxs-lookup"><span data-stu-id="2cf0c-281">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="2cf0c-282">일부 사용자가 VBA 매크로를 편집하지 못할 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-282">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="2cf0c-283">슬라이스를 사용할 때 성능에 영향을 줄 수 있는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-283">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-284">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-285">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-285">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-286">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-286">Outlook</span></span>
- <span data-ttu-id="2cf0c-287">선택한 항목에서 잘못된 서식 파일을 표시할 수 있는 문제가 수정되었습니다</span><span class="sxs-lookup"><span data-stu-id="2cf0c-287">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-288">액세스</span><span class="sxs-lookup"><span data-stu-id="2cf0c-288">Access</span></span>
- <span data-ttu-id="2cf0c-289">확대/축소 빌더를 사용하여 긴 서식 있는 텍스트를 표시하면 읽기가 어려워지는 문제를 해결했습니다</span><span class="sxs-lookup"><span data-stu-id="2cf0c-289">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-290">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-290">Project</span></span>
- <span data-ttu-id="2cf0c-291">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-291">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="2cf0c-292">2019년 5월 10일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-292">May 10, 2019</span></span>
<span data-ttu-id="2cf0c-293">버전 1906(빌드 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-293">Version 1906 (build 11702.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-294">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-294">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2cf0c-295">모두</span><span class="sxs-lookup"><span data-stu-id="2cf0c-295">All</span></span>
- <span data-ttu-id="2cf0c-296">다른 이름으로 저장 대화 상자에서 잘못된 경로를 표시할 수 있는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-296">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-297">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-297">Word</span></span> 
- <span data-ttu-id="2cf0c-298">텍스트를 입력하세요의 일부 선택 항목이 삽입되지 않는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-298">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-299">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-299">Excel</span></span>
- <span data-ttu-id="2cf0c-300">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-300">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-301">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-301">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-302">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-302">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-303">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-303">Outlook</span></span>
- <span data-ttu-id="2cf0c-304">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-304">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-305">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-305">Access</span></span>
- <span data-ttu-id="2cf0c-306">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-306">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-307">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-307">Project</span></span>
- <span data-ttu-id="2cf0c-308">작업 ID에서 강조 표시가 필요할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-308">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="2cf0c-309">2019년 5월 3일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-309">May 3, 2019</span></span>
<span data-ttu-id="2cf0c-310">버전 1906(빌드 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-310">Version 1906 (build 11629.20008)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-311">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-311">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2cf0c-312">모두</span><span class="sxs-lookup"><span data-stu-id="2cf0c-312">All</span></span>
- <span data-ttu-id="2cf0c-313">일부 사용자를 대상으로 비즈니스용 OneDrive 동기화 중에 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-313">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-314">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-314">Word</span></span> 
- <span data-ttu-id="2cf0c-315">특정한 경우 Word를 시작하는 데 오랜 시간이 걸리는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-315">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-316">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-316">Excel</span></span>
- <span data-ttu-id="2cf0c-317">최신 버전 Excel로 업그레이드한 후 통합 문서에서 가끔 외부 링크가 제거되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-317">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="2cf0c-318">일부 사용자를 대상으로 새 통합 문서에서 셀을 선택할 때 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-318">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-319">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-319">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-320">드로잉을 텍스트로 변환할 때 글꼴 크기가 일정하지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-320">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-321">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-321">Outlook</span></span>
- <span data-ttu-id="2cf0c-322">.VCF 파일에서 연락처를 저장하면 빈 필드가 생길 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-322">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="2cf0c-323">전송되었음에도 불구하고 메시지가 보낼 편지함 폴더에 쌓일 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-323">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="2cf0c-324">DRM 메시지를 볼 때 Outlook이 충돌할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-324">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-325">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-325">Access</span></span>
- <span data-ttu-id="2cf0c-326">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-326">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-327">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-327">Project</span></span>
- <span data-ttu-id="2cf0c-328">편집기가 중국어에서 영어로 전환되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-328">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="2cf0c-329">게시되지 않은 작업이 게시된 마스터 프로젝트 사본에 표시될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-329">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="2cf0c-330">2019년 4월 26일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-330">April 26, 2019</span></span>
<span data-ttu-id="2cf0c-331">버전 1905(빌드 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-331">Version 1905 (build 11617.20002)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-332">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-332">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-333">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-333">Word</span></span> 
- <span data-ttu-id="2cf0c-334">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-334">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-335">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-335">Excel</span></span>
- <span data-ttu-id="2cf0c-336">해 찾기 매크로가 실행에 실패하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-336">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="2cf0c-337">Excel 파일를 SharePoint로 가져오지 못하게 하는 문제를 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-337">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-338">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-338">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-339">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-339">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-340">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-340">Outlook</span></span>
- <span data-ttu-id="2cf0c-341">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-341">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-342">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-342">Access</span></span>
- <span data-ttu-id="2cf0c-343">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-343">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-344">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-344">Project</span></span>
- <span data-ttu-id="2cf0c-345">다양한 성능 및 안정성 수정 사항</span><span class="sxs-lookup"><span data-stu-id="2cf0c-345">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="2cf0c-346">2019년 4월 19일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-346">April 19, 2019</span></span>
<span data-ttu-id="2cf0c-347">버전 1905 (빌드 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-347">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2cf0c-348">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-348">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-349">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-349">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="2cf0c-350">데이터 형식을 사용하여 등치 지역도 개선</span><span class="sxs-lookup"><span data-stu-id="2cf0c-350">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="2cf0c-351">이 기능은 Excel의 지리 데이터 형식을 사용하여 등치 지역도 차트를 그리는 사용자에게 유용한 개선 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-351">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="2cf0c-352">기능과 최종 사용자가 매핑하고자 하는 지역의 정확성의 통합성을 향상하는 이점을 최종 사용자에게 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-352">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="2cf0c-353">추가적인 이점은 도시 폴리곤을 매핑할 수 있다는 점입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-353">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2cf0c-354">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-354">Getting Started:</span></span>

- <span data-ttu-id="2cf0c-355">이 기능은 Excel의 기존 기능을 개선한 것입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-355">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="2cf0c-356">개선 사항을 사용하려면 위치를 서식이 있는 엔티티로 변환하고 등치 지역도를 사용해 그립니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-356">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-357">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-357">Scenarios to Try:</span></span>

- <span data-ttu-id="2cf0c-358">사용자는 국가, 시/도, 시/군/구 및 우편 번호를 매핑할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-358">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-359">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-359">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="2cf0c-360">모든 응용 프로그램</span><span class="sxs-lookup"><span data-stu-id="2cf0c-360">All Applications</span></span>
- <span data-ttu-id="2cf0c-361">응용 프로그램을 시작할 때마다 첫 번째 실행 대화 상자가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-361">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="2cf0c-362">"다른 이름으로 저장" 대화 상자에서 SharePoint 링크가 누락되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-362">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="2cf0c-363">사용자에게 "지금 복구" 대화 상자가 올바르게 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-363">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-364">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-364">Word</span></span> 
- <span data-ttu-id="2cf0c-365">일부 사용자가 글꼴을 요청할 때 메모리 또는 디스크 공간 부족에 대한 오류가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-365">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="2cf0c-366">메모 창에서 전환할 때 창 포커스를 잃는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-366">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-367">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-367">Excel</span></span>
- <span data-ttu-id="2cf0c-368">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-368">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-369">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-369">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-370">브랜드 셰이프 크기를 조정할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-370">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="2cf0c-371">제한된 보기 모드에서 파일을 열 때 PowerPoint에서 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-371">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-372">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-372">Outlook</span></span>
- <span data-ttu-id="2cf0c-373">일부 사용자가 중국어 단어를 선택하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-373">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="2cf0c-374">만료 날짜가 올바르게 계산되지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-374">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-375">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-375">Access</span></span>
- <span data-ttu-id="2cf0c-376">일부 사용자가 매크로 작성기를 사용하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-376">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="2cf0c-377">보고서를 인쇄할 때 첫 페이지만 인쇄하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-377">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="2cf0c-378">하이퍼 링크를 마우스로 가리킬 때 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-378">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="2cf0c-379">관계 보기를 사용하는 경우 일부 항목이 화면에 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-379">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-380">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-380">Project</span></span>
- <span data-ttu-id="2cf0c-381">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-381">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="2cf0c-382">2019년 4월 12일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-382">April 12, 2019</span></span>
<span data-ttu-id="2cf0c-383">버전 1905 (빌드 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-383">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2cf0c-384">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-384">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-385">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-385">Access</span></span>

#### <a name="new-in-access---data-connector-to-microsoft-graph"></a><span data-ttu-id="2cf0c-386">Access의 새로운 기능 - Microsoft Graph에 대한 데이터 커넥터</span><span class="sxs-lookup"><span data-stu-id="2cf0c-386">New in Access - Data Connector to Microsoft Graph</span></span>

<span data-ttu-id="2cf0c-387">그래프에 저장된 스마트 컨텍스트 데이터를 활용할 수있는 응용 프로그램을 만들기 위해 양식 Microsoft Graph 서비스에 링크하거나 가져옵니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-387">Link to or import form Microsoft Graph services to build applications that can leverage the smart contextual data stored in the Graph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2cf0c-388">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-388">Getting Started:</span></span>

<span data-ttu-id="2cf0c-389">리본의 외부 데이터 탭에서 새 데이터 소스를 클릭하고 온라인 서비스 메뉴에서 새 그래프 커넥터를 찾습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-389">External Data tab in the ribbon, click on New Data Sources and find the new Graph connector in the Online Services menu</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-390">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-390">Scenarios to Try:</span></span>

<span data-ttu-id="2cf0c-391">사람, 그룹 및 OneDrive 항목을 비롯한 다양한 그래프 서비스에서 가져오거나 링크할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-391">Import from or link to various Graph services including People, Groups and OneDrive Items.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-392">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-392">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="2cf0c-393">모든 응용 프로그램</span><span class="sxs-lookup"><span data-stu-id="2cf0c-393">All Applications</span></span>
 - <span data-ttu-id="2cf0c-394">일부 사용자가 클라우드 위치에 파일을 저장하지 못하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-394">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="2cf0c-395">잘못된 창이 리본에서 열릴 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-395">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-396">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-396">Word</span></span> 
- <span data-ttu-id="2cf0c-397">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-397">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-398">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-398">Excel</span></span>
- <span data-ttu-id="2cf0c-399">통합 문서에 연결된 데이터 유형이 없을 때 연결된 데이터 유형에 대한 오류 메시지가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-399">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="2cf0c-400">로컬에서 또는 온라인에서 볼 때 Word 문서 내 URL 링크가 변경될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-400">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-401">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-401">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-402">애니메이션 탭에서 변경 사항을 취소한 후 응용 프로그램이 중단될 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-402">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-403">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-403">Outlook</span></span>
- <span data-ttu-id="2cf0c-404">일부 사용자가 공용 폴더에서 연락처에 대한 메모 필드를 수정할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-404">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="2cf0c-405">만료 날짜와 삭제 날짜 간에 충돌이 발생할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-405">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-406">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-406">Access</span></span>
- <span data-ttu-id="2cf0c-407">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-407">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-408">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-408">Project</span></span>
- <span data-ttu-id="2cf0c-409">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-409">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="2cf0c-410">2019년 4월 5일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-410">April 5, 2019</span></span>
<span data-ttu-id="2cf0c-411">버전 1904(빌드 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-411">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2cf0c-412">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-412">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-413">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-413">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="2cf0c-414">Windows 용 Outlook: 중요 받은 편지함 설정 지정 및 공유</span><span class="sxs-lookup"><span data-stu-id="2cf0c-414">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="2cf0c-415">중요 받은 편지함 기본 설정은 클라우드에 저장되므로, 임의 컴퓨터에서 Windows용 Outlook 및 웹용 Outlook을 사용할 때 일관된 경험을 즐길 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-415">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2cf0c-416">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-416">Getting Started:</span></span>

<span data-ttu-id="2cf0c-417">파일 > 옵션 > 일반 탭에 새로운 ‘클라우드에 내 Outlook 설정 저장’ 기본 설정이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-417">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="2cf0c-418">다른 Desktop Outlook 설치 및 OWA로 로밍하려면 사용자가 중요 받은 편지함 설정을 사용으로 지정하는 상자를 선택해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-418">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-419">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-419">Scenarios to Try:</span></span>

<span data-ttu-id="2cf0c-420">클라우드 설정 기본 설정이 켜져 있는 컴퓨터에서 중요 받은 편지함을 변경하십시오.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-420">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="2cf0c-421">OWA로 이동하여 거기에 적용된 환경 설정을 확인하십시오.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-421">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="2cf0c-422">OWA에서 중요 받은 편지함을 변경하고 데스크톱 Outlook을 시작하여 환경 설정이 반영되었는지 확인하십시오.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-422">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-423">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-423">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="2cf0c-424">학습 도구 모드는 더 많은 페이지 색상을 지원합니다</span><span class="sxs-lookup"><span data-stu-id="2cf0c-424">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="2cf0c-425">Word 학습 도구는 페이지 테마 색을 추가로 지원하므로 페이지의 배경색을 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-425">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="2cf0c-426">많은 사람들이 흑백 또는 검정색 배경으로 읽는 것에 어려움을 느끼고 있으므로 PC 및 Mac의 Word에서 색상 선택을 확장했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-426">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2cf0c-427">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-427">Getting Started:</span></span>

<span data-ttu-id="2cf0c-428">이 기능을 사용하려면보기 탭으로 이동하여 학습 도구와 페이지 색상을 차례로 선택하십시오.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-428">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-429">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-429">Scenarios to Try:</span></span>

<span data-ttu-id="2cf0c-430">이 기능을 사용하려면보기 탭으로 이동하여 학습 도구와 페이지 색상을 차례로 선택하십시오.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-430">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-431">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-431">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="2cf0c-432">애니메이션 3D 모델로 독창성 높이기</span><span class="sxs-lookup"><span data-stu-id="2cf0c-432">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="2cf0c-433">이제 Office에서 애니메이션 모델을 지원하므로 편집기에서 재생되므로 시트를 실제로 사용할 수 있습니다!</span><span class="sxs-lookup"><span data-stu-id="2cf0c-433">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2cf0c-434">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-434">Getting Started:</span></span>

1. <span data-ttu-id="2cf0c-435">Excel을 엽니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-435">Open Excel 2007.</span></span>
2. <span data-ttu-id="2cf0c-436">애니메이션 모델을 삽입하십시오(곧 Remix로 변경되지만, 현재는 여기에서 애니메이션 모델에 액세스하십시오.\\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-436">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="2cf0c-437">애니메이션 모델이 편집기에서 재생됩니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-437">The animated model will play in the editor!</span></span> <span data-ttu-id="2cf0c-438">슬라이드 쇼 모드를 확인하십시오 - 거기에서도 재생됩니다!</span><span class="sxs-lookup"><span data-stu-id="2cf0c-438">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="2cf0c-439">3D 형식 리본에서 모델의 더 많은 애니메이션 장면 탐색</span><span class="sxs-lookup"><span data-stu-id="2cf0c-439">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-440">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-440">Scenarios to Try:</span></span>

1. <span data-ttu-id="2cf0c-441">애니메이션 모델을 삽입하고 편집기에서 재생되는 것을 확인합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-441">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="2cf0c-442">장면 갤러리(3차원 서식 리본에서 사용 가능)를 통해 애니메이션 모델에서 사용할 수 있는 애니메이션 장면을 탐색합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-442">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="2cf0c-443">리본, floatie 또는 스페이스 바를 사용하여 애니메이션을 간편하게 재생하고 일시 중지합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-443">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-444">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-444">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="2cf0c-445">모든 응용 프로그램</span><span class="sxs-lookup"><span data-stu-id="2cf0c-445">All Applications</span></span>
- <span data-ttu-id="2cf0c-446">상황에 맞는 메뉴에서 Excel에 대해 잘못된 앱 아이콘이 나타나는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-446">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="2cf0c-447">업데이트를 설치한 후 파일 메뉴 단추가 사라지는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-447">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="2cf0c-448">사용자 라이선스를 변경할 수 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-448">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-449">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-449">Word</span></span> 
- <span data-ttu-id="2cf0c-450">특정 줌 레벨에서 텍스트가 올바르게 렌더링되지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-450">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-451">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-451">Excel</span></span>
- <span data-ttu-id="2cf0c-452">편집한 후 통합 문서 저장 메시지가 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-452">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="2cf0c-453">사용자가 통합 문서를 공유한 경우 BeforeSave 이벤트가 트리거되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-453">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="2cf0c-454">열 크기를 6픽셀 미만으로 조정하면 잘못된 오류 메시지가 나타나는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-454">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="2cf0c-455">Excel에서 Application.Visible 플래그를 무시하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-455">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="2cf0c-456">비활성 상태의 고정된 창에 추적 화살표가 남아 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-456">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="2cf0c-457">통합 문서를 열 때 날짜 및 통화에 대한 셀 서식이 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-457">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="2cf0c-458">도구 설명이 예기치 않게 이동되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-458">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="2cf0c-459">파워 쿼리 편집기의 지역화 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-459">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="2cf0c-460">통합 문서를 전자 메일을 통해 첨부 파일로 보낼 때 통합 문서가 제거되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-460">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-461">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-461">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-462">도형 복사에 예상보다 시간이 오래 걸리는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-462">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-463">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-463">Outlook</span></span>
- <span data-ttu-id="2cf0c-464">그리기 도구를 사용하는 동안 Outlook이 충돌하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-464">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="2cf0c-465">html 전자 메일을 작성할 때 지역화 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-465">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="2cf0c-466">사용자가 아래쪽 창을 선택하기 힘든 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-466">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-467">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-467">Access</span></span>
- <span data-ttu-id="2cf0c-468">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-468">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-469">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-469">Project</span></span>
- <span data-ttu-id="2cf0c-470">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-470">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="2cf0c-471">2019년 3월 22일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-471">March 22, 2019</span></span>
<span data-ttu-id="2cf0c-472">버전 1904(빌드 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-472">Version 1904 (build 11514.20004)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-473">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-473">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-474">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-474">Word</span></span> 
- <span data-ttu-id="2cf0c-475">UI에 지속적으로 “변경 내용을 확인하는 중”이 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-475">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-476">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-476">Excel</span></span>
- <span data-ttu-id="2cf0c-477">워크시트 이동 후 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-477">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="2cf0c-478">PDF로 저장한 후 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-478">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="2cf0c-479">저장 대화 상자에서 일부 한국어 문자를 허용하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-479">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-480">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-480">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-481">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-481">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-482">Outlook</span></span>
- <span data-ttu-id="2cf0c-483">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-483">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-484">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-484">Access</span></span>
- <span data-ttu-id="2cf0c-485">Access에서 Access로 추가 바로 가기가 만들어졌다는 오류 메시지가 표시되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-485">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="2cf0c-486">연결된 SharePoint의 데이터가 올바르게 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-486">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-487">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-487">Project</span></span>
- <span data-ttu-id="2cf0c-488">언어 설정이 중국어에서 영어로 변경되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-488">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="2cf0c-489">SharePoint와 동기화할 때 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-489">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="2cf0c-490">2019년 3월 15일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-490">March 15, 2019</span></span>
<span data-ttu-id="2cf0c-491">버전 1904(빌드 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-491">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2cf0c-492">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-492">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-493">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-493">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="2cf0c-494">포커스 모드</span><span class="sxs-lookup"><span data-stu-id="2cf0c-494">Focus Mode</span></span>

<span data-ttu-id="2cf0c-495">보기 메뉴에서 포커스로 전환하면 주의를 산만하게 하는 요인들을 제거하고 작업에 집중할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-495">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="2cf0c-496">Office 365 구독자만 해당합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-496">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2cf0c-497">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-497">Getting Started:</span></span>

<span data-ttu-id="2cf0c-498">보기 탭 리본 상태 막대 "포커스" 버튼의 "포커스 "버튼 </span><span class="sxs-lookup"><span data-stu-id="2cf0c-498">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-499">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-499">Scenarios to Try:</span></span>

<span data-ttu-id="2cf0c-500">포커스 모드를 시작하 고 주요 환경을 경험해 보세요.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-500">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-501">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-501">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-502">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-502">Word</span></span> 
- <span data-ttu-id="2cf0c-503">PDF로 저장된 문서의 이미지에 잘못된 DPI가 있는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-503">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-504">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-504">Excel</span></span>
- <span data-ttu-id="2cf0c-505">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-505">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-506">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-506">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-507">메모 창이 적절하게 열리거나 닫히지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-507">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="2cf0c-508">비디오를 삭제할 때 응용 프로그램이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-508">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="2cf0c-509">경우에 따라 응용 프로그램을 시작할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-509">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-510">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-510">Outlook</span></span>
- <span data-ttu-id="2cf0c-511">일본어로 표시할 때 읽음 확인이 올바르지 않은 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-511">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-512">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-512">Access</span></span>
- <span data-ttu-id="2cf0c-513">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-513">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-514">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-514">Project</span></span>
- <span data-ttu-id="2cf0c-515">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-515">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="2cf0c-516">2019년 3월 8일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-516">March 8, 2019</span></span> 
<span data-ttu-id="2cf0c-517">버전 1903(빌드 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-517">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2cf0c-518">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-518">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-519">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-519">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="2cf0c-520">Microsoft Search를 통해 원하는 것을 찾으십시오.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-520">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="2cf0c-521">Microsoft Search를 사용하면 모든 파일, 작업, 사람을 찾고 작업을 수행하는 데 필요한 도움을 받을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-521">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2cf0c-522">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-522">Getting Started:</span></span>

- <span data-ttu-id="2cf0c-523">이 기능은 머리글의 UI 위에 눈에 띄도록 표시됩니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-523">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-524">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-524">Scenarios to Try:</span></span>

- <span data-ttu-id="2cf0c-525">대학이나 최근 문서를 검색하거나 가장 자주 사용하는 리본 명령을 검색해 보세요.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-525">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="2cf0c-526">화제나 주제를 검색하여 더 많은 정보를 얻으세요.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-526">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="2cf0c-527">공동 작성</span><span class="sxs-lookup"><span data-stu-id="2cf0c-527">Co-authoring</span></span>

<span data-ttu-id="2cf0c-528">매크로 포함하는 문서가 잠기는게 번거롭습니까?</span><span class="sxs-lookup"><span data-stu-id="2cf0c-528">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="2cf0c-529">이제 비즈니스용 OneDrive의 .docm 파일을 사용하여 여러 작성자가 동시에 편집할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-529">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2cf0c-530">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-530">Getting Started:</span></span>

<span data-ttu-id="2cf0c-531">사용자가 이 기능에 액세스 하기 위해 UI에서 버튼을 누를 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-531">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="2cf0c-532">OneDrive for Business docm 파일에서는 기본적으로 활성화되어 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-532">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="2cf0c-533">따라서 사용자는 OneDrive for Business에 docm 파일을 저장하여 사용해 봐야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-533">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-534">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-534">Scenarios to Try:</span></span>

<span data-ttu-id="2cf0c-535">OneDrive for Business에 docm 파일을 만들고 동료와 공유하고 공동 작업해 보십시오!</span><span class="sxs-lookup"><span data-stu-id="2cf0c-535">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-536">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-536">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-537">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-537">Word</span></span> 
- <span data-ttu-id="2cf0c-538">Options에서 ‘ESC’를 누를 때 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-538">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="2cf0c-539">메모에 회신할 때 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-539">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="2cf0c-540">Word에서 PowerPoint Online으로 복사 및 붙여넣기를 할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-540">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-541">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-541">Excel</span></span>
- <span data-ttu-id="2cf0c-542">보호되고 편집 가능한 문서를 열었을 때 Excel에서 셀을 복사하는 경우 높은 CPU 사용량을 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-542">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-543">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-543">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-544">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-544">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-545">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-545">Outlook</span></span>
- <span data-ttu-id="2cf0c-546">Outlook Search가 선택한 연대순 정렬을 반영하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-546">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="2cf0c-547">"이 작업 열기" 워크플로우 리본 버튼이 특정 이메일에 응답하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-547">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="2cf0c-548">사용자가 회의실 찾기를 통해 사용 가능한 회의실을 선택한 후 Outlook이 사내 회의실을 지우지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-548">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-549">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-549">Access</span></span>
- <span data-ttu-id="2cf0c-550">어두운 테마에서 흰색 배경에 흰색 텍스트가 있던 저장된 가져오기/내보내기 대화 상자의 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-550">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="2cf0c-551">테이블 디자인에서 사용자가 표시 컨트롤 속성의 Yes/No 필드를 Textbox로 설정하지 못했던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-551">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-552">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-552">Project</span></span>
- <span data-ttu-id="2cf0c-553">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-553">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="2cf0c-554">2019년 3월 1일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-554">March 1, 2019</span></span> 
<span data-ttu-id="2cf0c-555">버전 1903(빌드 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-555">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2cf0c-556">새로운 기능</span><span class="sxs-lookup"><span data-stu-id="2cf0c-556">What's New</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-557">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-557">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="2cf0c-558">동기화 중 변경 내용 추적, 메모, 실시간 공동 작업을 표시하는 색상</span><span class="sxs-lookup"><span data-stu-id="2cf0c-558">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="2cf0c-559">이제 제품의 개선을 통해 공동 작업자의 메모, 변경 내용 추적 및 커서를 동일한 색상으로 표시합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-559">Colors for Track Changes, Comments and Real-Time Collaboration in Sync: Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2cf0c-560">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-560">Getting Started:</span></span>

<span data-ttu-id="2cf0c-561">다른 사용자가 연 SharePoint 또는 OneDrive문서를 엽니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-561">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="2cf0c-562">사용자의 변경 내용 추적과 해당 사용자 커서의 색이 일치 하는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-562">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-563">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-563">Scenarios to Try:</span></span>

<span data-ttu-id="2cf0c-564">다른 사용자가 연 SharePoint 또는 OneDrive문서를 엽니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-564">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="2cf0c-565">사용자의 변경 내용 추적과 해당 사용자 커서의 색이 일치 하는지 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-565">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-566">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-566">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-567">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-567">Word</span></span> 
- <span data-ttu-id="2cf0c-568">Options에서 ‘ESC’를 누를 때 발생하는 충돌 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-568">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="2cf0c-569">Word에서 PowerPoint Online으로 복사 및 붙여넣기를 할 때 발생하는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-569">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-570">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-570">Excel</span></span>
- <span data-ttu-id="2cf0c-571">보호되고 편집 가능한 문서를 열었을 때 Excel에서 셀을 복사하는 경우 높은 CPU 사용량을 발생시키는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-571">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-572">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-572">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-573">PowerPoint에서 @Mentions를 사용 시의 슬라이드 이미지 크기 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-573">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-574">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-574">Outlook</span></span>
- <span data-ttu-id="2cf0c-575">Outlook Search가 선택한 연대순 정렬을 반영하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-575">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="2cf0c-576">"이 작업 열기" 워크플로우 리본 버튼이 특정 이메일에 응답하지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-576">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="2cf0c-577">사용자가 회의실 찾기를 통해 사용 가능한 회의실을 선택한 후 Outlook이 사내 회의실을 지우지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-577">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-578">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-578">Access</span></span>
- <span data-ttu-id="2cf0c-579">데이터 전송 발신기와 테이블의 재연결을 확인 시 표시되는 프롬프트 텍스트를 업데이트했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-579">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="2cf0c-580">어두운 테마에서 흰색 배경에 흰색 텍스트가 있던 저장된 가져오기/내보내기 대화 상자의 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-580">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="2cf0c-581">테이블 디자인에서 사용자가 표시 컨트롤 속성의 Yes/No 필드를 Textbox로 설정하지 못했던 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-581">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-582">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-582">Project</span></span>
- <span data-ttu-id="2cf0c-583">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-583">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="2cf0c-584">2019년 2월 15일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-584">February 15, 2019</span></span> 
<span data-ttu-id="2cf0c-585">버전 1903(빌드 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-585">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2cf0c-586">새로운 기능:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-586">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-587">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-587">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="2cf0c-588">모핑 전환 개선 사항 - 이름으로 모핑</span><span class="sxs-lookup"><span data-stu-id="2cf0c-588">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="2cf0c-589">모핑하려는 도형 지정</span><span class="sxs-lookup"><span data-stu-id="2cf0c-589">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2cf0c-590">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-590">Getting Started:</span></span>

- <span data-ttu-id="2cf0c-591">두 개체를 같은 개체로 처리하도록 모핑을 사용하기 위해 사용자는 선택 창을 사용하여 도형 이름을 바꿀 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-591">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="2cf0c-592">이름은 "!!"로 시작해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-592">The name must be prefaced with “!!”</span></span> <span data-ttu-id="2cf0c-593">모핑에서 이름을 사용하여 기본 일치 동작을 무시하도록 하려면, 예를 들어 “!!이름”</span><span class="sxs-lookup"><span data-stu-id="2cf0c-593">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="2cf0c-594">사용자는 계속 “!!”로 시작하지 않는 셰이프 이름을 바꿀 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-594">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="2cf0c-595">모핑 작동 방식의 변경에 대해 우려할 필요가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-595">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-596">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-596">Scenarios to Try:</span></span>

- <span data-ttu-id="2cf0c-597">슬라이드에 도형을 삽입합니다. 직사각형을 가정해 보겠습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-597">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="2cf0c-598">새 슬라이드를 만듭니다 
</span><span class="sxs-lookup"><span data-stu-id="2cf0c-598">Create a new slide</span></span>
- <span data-ttu-id="2cf0c-599">두 번째 슬라이드에 다른 도형을 삽입합니다. 삼각형을 가정해 보겠습니다</span><span class="sxs-lookup"><span data-stu-id="2cf0c-599">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="2cf0c-600">SelectionPane을 열고, 슬라이드 1에서 직사각형을 "!!도형"으로 이름을 바꾸고, 슬라이드 2에서 삼각형을 “!!도형”으로 이름을 바꿉니다</span><span class="sxs-lookup"><span data-stu-id="2cf0c-600">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="2cf0c-601">두 번째 슬라이드에 모핑 적용</span><span class="sxs-lookup"><span data-stu-id="2cf0c-601">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="2cf0c-602">모핑 전환 개선 사항 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="2cf0c-602">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="2cf0c-603">더 원활한 전환으로 SmartArt 모핑</span><span class="sxs-lookup"><span data-stu-id="2cf0c-603">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2cf0c-604">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-604">Getting Started:</span></span>

<span data-ttu-id="2cf0c-605">SmartArt를 사용하는 것과 같은 방법으로 모핑 사용</span><span class="sxs-lookup"><span data-stu-id="2cf0c-605">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-606">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-606">Scenarios to Try:</span></span>

- <span data-ttu-id="2cf0c-607">슬라이드에 SmartArt 삽입</span><span class="sxs-lookup"><span data-stu-id="2cf0c-607">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="2cf0c-608">슬라이드를 복제합니다</span><span class="sxs-lookup"><span data-stu-id="2cf0c-608">Duplicate the Slide</span></span>
- <span data-ttu-id="2cf0c-609">복제된 슬라이드에서 SmartArt를 크기 조정/변경/이동합니다</span><span class="sxs-lookup"><span data-stu-id="2cf0c-609">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="2cf0c-610">복제된 슬라이드에서 모핑 적용</span><span class="sxs-lookup"><span data-stu-id="2cf0c-610">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="2cf0c-611">모핑 전환 개선 사항 - 표</span><span class="sxs-lookup"><span data-stu-id="2cf0c-611">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="2cf0c-612">더 원활한 전환으로 표 모핑</span><span class="sxs-lookup"><span data-stu-id="2cf0c-612">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2cf0c-613">시작:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-613">Getting Started:</span></span>
<span data-ttu-id="2cf0c-614">표를 사용하는 것과 같은 방법으로 모핑 사용</span><span class="sxs-lookup"><span data-stu-id="2cf0c-614">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-615">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-615">Scenarios to Try:</span></span>

- <span data-ttu-id="2cf0c-616">슬라이드에서 표 추가</span><span class="sxs-lookup"><span data-stu-id="2cf0c-616">Insert a Table in a slide</span></span>
- <span data-ttu-id="2cf0c-617">슬라이드를 복제합니다</span><span class="sxs-lookup"><span data-stu-id="2cf0c-617">Duplicate the slide</span></span>
- <span data-ttu-id="2cf0c-618">복제된 슬라이드에서 Table을 크기 조정/변경/이동합니다</span><span class="sxs-lookup"><span data-stu-id="2cf0c-618">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="2cf0c-619">복제된 슬라이드에서 모핑 적용</span><span class="sxs-lookup"><span data-stu-id="2cf0c-619">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="2cf0c-620">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher 및 Visio</span><span class="sxs-lookup"><span data-stu-id="2cf0c-620">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="2cf0c-621">원활한 계정 전환</span><span class="sxs-lookup"><span data-stu-id="2cf0c-621">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="2cf0c-622">새 계정 관리자를 통해 사용자의 모든 회사 및 개인 계정을 한곳에서 볼 수 있으며, 사용자가 직접 여러 계정 간에 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-622">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="2cf0c-623">업데이트된 환경에서는 사용자의 로그인 방법이 명확해지며, 이제 먼저 로그아웃하거나 복잡한 대화 상자를 거치지 않고 회사 및 개인 계정 사이를 전환할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-623">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="2cf0c-625">시도해 볼 시나리오:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-625">Scenarios to Try:</span></span>
- <span data-ttu-id="2cf0c-626">계정 간 전환</span><span class="sxs-lookup"><span data-stu-id="2cf0c-626">Switch between accounts</span></span>
- <span data-ttu-id="2cf0c-627">새 계정 추가 [참고: 먼저 파일 | 계정 | 연결된 서비스에 가서 회사 계정에 연결된 개인 서비스를 제거 또는 그 반대로 하고자 할 수 있습니다]</span><span class="sxs-lookup"><span data-stu-id="2cf0c-627">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="2cf0c-628">계정에서 로그아웃</span><span class="sxs-lookup"><span data-stu-id="2cf0c-628">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-629">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-629">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-630">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-630">Word</span></span> 
- <span data-ttu-id="2cf0c-631">표 및 이미지에 대한 상황에 맞는 미리 보기 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-631">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-632">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-632">Excel</span></span>
- <span data-ttu-id="2cf0c-633">자동 필터 검색 필드의 텍스트는 검은색 테마에서 흰색인 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-633">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="2cf0c-634">새 Office 추가 기능에 있는 동의 UI 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-634">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-635">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-635">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-636">노트북 또는 태블릿에 슬라이드 쇼를 표시할 때 자동으로 확장하는 디스플레이 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-636">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-637">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-637">Outlook</span></span>
- <span data-ttu-id="2cf0c-638">OneNote로 보내기 버튼 디스플레이 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-638">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-639">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-639">Access</span></span>
- <span data-ttu-id="2cf0c-640">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-640">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-641">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-641">Project</span></span>
- <span data-ttu-id="2cf0c-642">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-642">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="2cf0c-643">2019년 2월 11일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-643">February 11, 2019</span></span>
<span data-ttu-id="2cf0c-644">버전 1903(빌드 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-644">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-645">중요 수정 사항:</span><span class="sxs-lookup"><span data-stu-id="2cf0c-645">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-646">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-646">Word</span></span> 
- <span data-ttu-id="2cf0c-647">일부 사용자 지정된 스타일을 Word Online에 적용할 수 없는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-647">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="2cf0c-648">Word에서 서식 있는 개체의 컨텍스트 미리 보기 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-648">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="2cf0c-649">Word에서 목록을 붙여넣으면 작동이 중단되는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-649">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-650">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-650">Excel</span></span>
- <span data-ttu-id="2cf0c-651">통화 기호가 없을 때 숫자 서식 뒤에 추가된 공백이 더 이상 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-651">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="2cf0c-652">주식 자동 검색 관련 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-652">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-653">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-653">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-654">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-654">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-655">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-655">Outlook</span></span>
- <span data-ttu-id="2cf0c-656">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-656">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-657">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-657">Access</span></span>
- <span data-ttu-id="2cf0c-658">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-658">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-659">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-659">Project</span></span>
- <span data-ttu-id="2cf0c-660">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-660">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="2cf0c-661">2019년 2월 1일</span><span class="sxs-lookup"><span data-stu-id="2cf0c-661">February 1, 2019</span></span> 
<span data-ttu-id="2cf0c-662">버전 1902(빌드 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="2cf0c-662">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="2cf0c-663">중요 수정 사항</span><span class="sxs-lookup"><span data-stu-id="2cf0c-663">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="2cf0c-664">Word</span><span class="sxs-lookup"><span data-stu-id="2cf0c-664">Word</span></span> 
- <span data-ttu-id="2cf0c-665">임베디드 Excel 테이블에서 셀 크기를 조정하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-665">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="2cf0c-666">그리기 캔버스에서 도형 복사 / 붙여 넣기 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-666">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="2cf0c-667">Excel</span><span class="sxs-lookup"><span data-stu-id="2cf0c-667">Excel</span></span>
- <span data-ttu-id="2cf0c-668">Excel 웹 응용 프로그램에서 파일을 열 때 발생하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-668">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="2cf0c-669">파일 이름 크기로 인해 .XLSX가 실패하여 CSV 파일을 저장하는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-669">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="2cf0c-670">컨텍스트 메뉴를 수정하여 컨텍스트 메뉴 옵션을 표시했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-670">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2cf0c-671">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2cf0c-671">PowerPoint</span></span>
- <span data-ttu-id="2cf0c-672">사용자가 키보드 단축키 ctrl + alt + 7 / ctrl + alt + 8을 사용하여 대괄호를 입력할 수 없는 부분을 수정했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-672">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="2cf0c-673">PPT에 로컬 비디오를 삽입하면 'C'드라이브의 디스크 공간이 줄어드는 문제가 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-673">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="2cf0c-674">일부 사용자에게 표시되지 않는 Microsoft Stream에 게시 버튼이 수정되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-674">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="2cf0c-675">Outlook</span><span class="sxs-lookup"><span data-stu-id="2cf0c-675">Outlook</span></span>
- <span data-ttu-id="2cf0c-676">일정의 작업 보기에 작업 제목이 올바르게 표시되지 않는 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-676">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="2cf0c-677">Access</span><span class="sxs-lookup"><span data-stu-id="2cf0c-677">Access</span></span>
- <span data-ttu-id="2cf0c-678">차트 관련 배율 문제를 해결했습니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-678">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="2cf0c-679">Project</span><span class="sxs-lookup"><span data-stu-id="2cf0c-679">Project</span></span>
- <span data-ttu-id="2cf0c-680">다양한 성능 및 안정성 수정 사항입니다.</span><span class="sxs-lookup"><span data-stu-id="2cf0c-680">Various performance and stability fixes</span></span>
