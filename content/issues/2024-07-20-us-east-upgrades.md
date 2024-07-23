---
section: issue
title: US East upgrades
date: 2024-07-18T14:12:00.000-04:00
resolved: true
draft: false
informational: false
pin: false
resolvedWhen: 2024-07-20T18:30:34.479-04:00
affected:
  - Mastodon
  - TTGit
  - STVRadio
  - AssistAI
  - TTWeb
  - CDN
severity: down
---
*Details* - We are planning a US East wide restore of its container as performance on it is not looking very good. This affection is only towards the identity site as we are aware. We are creating a redirection payload for all users to the Midwest server. Timing for the restore is unknown but will be planned later on today.

[﻿History]

[July 18, 2024 2:12 PM] - US East is back online and is cleaned up. Services are not online just yet as we don't have the required packages for it. We'll update you when we have more information.



[July 19, 2024 4:08 PM] - US East is almost complete of its restoration. TTWeb and the CDN are the only services online right now. TTGit, TTNRT ID and TTSocial should be back to service once the installation of Docker is complete and that login systems are fully working.



[July 20, 2024 6:23 PM] - We apologize for the lack of information. Since the site operates on a VM, memory resources have been increasing lately, and we assume it's due to Docker running inside of it. Our team has reached out to Netrocorp to give us a container version, but with no response from them. For now, this issue will be closed as we don't have any more information right now. Services that are down will not be restored to service until the issues with the site is resolved.

[﻿July 22, 2024 11:33 PM] - US East is fully restored to service. Currently, STVRadio and AssistAI are not up and running, but will be online by tomorrow at the latest. Issue is now closed.