---
# required metadata

title: Monitor Azure Advanced Threat Protection System Health and Events | Microsoft Docs
description: Use the Azure ATP workspace health center to check how the Azure ATP service is working and be alerted to potential problems and view system events in the Event viewer.
keywords:
author: mlottner
ms.author: mlottner
manager: mbaldwin
ms.date: 11/28/2018
ms.topic: conceptual
ms.prod:
ms.service: azure-advanced-threat-protection
ms.technology:
ms.assetid: 1b7e72c3-a538-443f-981c-398ffafa5ab8

# optional metadata

#ROBOTS:
#audience:
#ms.devlang:
ms.reviewer: itargoet
ms.suite: ems
#ms.tgt_pltfrm:
#ms.custom:

---

*Applies to: Azure Advanced Threat Protection*


# Working with Azure ATP workspace health and events

## Azure ATP workspace health center 

The Azure ATP workspace health center lets you know how your Azure ATP workspace is performing and alerts you when there are problems.

## Working with the Azure ATP workspace health center

The Azure ATP workspace health center lets you know that there's a problem by raising an alert (a red dot) above the Health Center icon in the menu bar.

![Azure ATP workspace health center red dot toolbar](media/atp-health-bar.png)

### Managing Azure ATP workspace health
To check up on your workspace's overall health, click the Health Center icon in the menu bar ![Azure ATP workspace health center icon](media/atp-red-dot.png)

-   All open issues can be managed by setting them to **Close**,  or **Suppress**, by clicking the three dots in the corner of the alert and making your selection.

-   **Open**: All new suspicious activities appear in this list.

-   **Close**: Is used to track suspicious activities that you identified, researched, and fixed for mitigated.

    > [!NOTE]
    > Azure ATP may reopen a closed activity if the same activity is detected again within a short period of time.
    
-   **Suppress**: Suppressing an activity means you want to ignore it for now, and only be alerted again if there's a new instance. If there's a similar alert Azure ATP doesn't reopen it. But if the alert stops for seven days, and is then seen again, you're alerted again.

-   **Reopen**: You can reopen a closed or suppressed alert so that it appears as **Open** in the timeline again.

-   **Delete**: From within the security alert timeline, you also have the option to delete a health issue. If you Delete an alert, it is deleted from the instance and you will NOT be able to restore it. After you click delete, you'll be able to delete all security alerts of the same type.



![Azure ATP health center issues image](media/atp-health-issue.png)






## See Also

- [Working with suspicious activities](working-with-suspicious-activities.md)
- [Check out the Azure ATP forum!](https://aka.ms/azureatpcommunity)
