# Echo Product Overview

## Introduction

Echo is an AI-powered application designed to support me throughout the project lifecycle. It provides a chat-based interface with document management capabilities, allowing me to efficiently access information from project documents and call transcripts, receive architectural recommendations, and collaborate with team members.

  

[Figma screens](https://www.figma.com/proto/L48wWQLO7uSRPZKPGaIY9q/Echo?node-id=2-2&p=f&t=eoEIJjxAYde3BYDP-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=2%3A2&show-proto-sidebar=1)

  

## System Overview

### Application Architecture

![](https://t9016848416.p.clickup-attachments.com/t9016848416/1eeece4d-ba37-4f7b-a14d-c7d990202ddd/image.png)

### Database schema (ERD)

[![](https://mermaid.ink/img/pako:eNqtV9tu2zAM_RVDz2mRm9M2z1uBodiwYejLEMBQLSZxa0ueJHft0vz7KN8tS-1S1AgCW4ekeUiKlA8kFgzImoD8lNCdpNmGB3gVCqQKDtWDuRKuy8UoYcH3m279kcp4T2WJcZpBcPvty4_bz2MByGiSetGcKvVHSBbtqdp3sE4yUJpmeRBLoBpYRHWFHje8usmluIdYj5yt121_-zyuHTwaNcOl5wc86YCBimWS60TwkzxkIi4y4GMXG8DlY899l5ut6tDPBt4mKUQ51XsPpJ9zcHEo8lRQFjEk0sH3SvC7IANNcZ1a5GKapiNiZvEdpEo1NyEtKa-i76ElIcbySfjOwnv5MdZPYEZjk-ko0ZCNCPYwF8-G__WNP-F9rCyv2qa5t16mVLLjWFlaDLVaaqwAi1kTFsR1oU4qV8jugJlIjli3iIuzj5svHo9YCEJ2Nn1eRL8LKMB2pVz8EDdODpS9Y9gIbWzeizt7p5lEg5RCRmhA0R1YtLcJx91ZcEPc1KQCR9uo1t_TNWpN9x5rUPcGM2i0FTJzx8EVpVe3V5-pLPiIJa4589uRdzHMcJr5eoixaLX11n38lzoyzy4UOLMwX9lUlPeYdJlTnKagcY46IiKTWDka4B7ih1wgT7uL_W_dYAbKEIzCWQXGEdA6zqcGs8K8vfbUaogFf8RIUdMCx-OkB55Q9W-N-oHZjyoMF8s2g2maRfjWrsW3_OusjtNWrTuHjBUVm7pC58bkSz8aq8NZ09Fq797mVbfxxqKvnVfnyZeXszNx6I5s62BDqlJRG2Id52rZ7vBUCmPwaMK90tVpxCVZIbXYYLQb6R1wkH03utf6VCRsQQKPO50Bx5F8M8UDLbwv6Y1eo4JnYaf7fjG_xXqMGvnyjr1u2StuR9w5sFwJcAo6jJSzwBjAcDIsZJd-KWPpdp3PKKObrIj9ZTXsN1YUB4kcS5YtocvMAK-V2u3sisTA_EDSbFkUIxOSAQ7ahOGHWdkQNkTvAdsMMVKMygdj64hytNDi5zOPyVrLAiZEimK3J-stTRU-VYeT-sOuXc0p_yVE1qjgI1kfyBNZz8PzxXy-WEyns9XFcrpahRPyTNZns8vwfHm1upqt5iH-lqvL44T8LU3MzhfLeRiuLmbhdDYLr1YXEwIswZbwtfquLD8vj_8AUIacQQ?type=png)](https://mermaid.live/edit#pako:eNqtV9tu2zAM_RVDz2mRm9M2z1uBodiwYejLEMBQLSZxa0ueJHft0vz7KN8tS-1S1AgCW4ekeUiKlA8kFgzImoD8lNCdpNmGB3gVCqQKDtWDuRKuy8UoYcH3m279kcp4T2WJcZpBcPvty4_bz2MByGiSetGcKvVHSBbtqdp3sE4yUJpmeRBLoBpYRHWFHje8usmluIdYj5yt121_-zyuHTwaNcOl5wc86YCBimWS60TwkzxkIi4y4GMXG8DlY899l5ut6tDPBt4mKUQ51XsPpJ9zcHEo8lRQFjEk0sH3SvC7IANNcZ1a5GKapiNiZvEdpEo1NyEtKa-i76ElIcbySfjOwnv5MdZPYEZjk-ko0ZCNCPYwF8-G__WNP-F9rCyv2qa5t16mVLLjWFlaDLVaaqwAi1kTFsR1oU4qV8jugJlIjli3iIuzj5svHo9YCEJ2Nn1eRL8LKMB2pVz8EDdODpS9Y9gIbWzeizt7p5lEg5RCRmhA0R1YtLcJx91ZcEPc1KQCR9uo1t_TNWpN9x5rUPcGM2i0FTJzx8EVpVe3V5-pLPiIJa4589uRdzHMcJr5eoixaLX11n38lzoyzy4UOLMwX9lUlPeYdJlTnKagcY46IiKTWDka4B7ih1wgT7uL_W_dYAbKEIzCWQXGEdA6zqcGs8K8vfbUaogFf8RIUdMCx-OkB55Q9W-N-oHZjyoMF8s2g2maRfjWrsW3_OusjtNWrTuHjBUVm7pC58bkSz8aq8NZ09Fq797mVbfxxqKvnVfnyZeXszNx6I5s62BDqlJRG2Id52rZ7vBUCmPwaMK90tVpxCVZIbXYYLQb6R1wkH03utf6VCRsQQKPO50Bx5F8M8UDLbwv6Y1eo4JnYaf7fjG_xXqMGvnyjr1u2StuR9w5sFwJcAo6jJSzwBjAcDIsZJd-KWPpdp3PKKObrIj9ZTXsN1YUB4kcS5YtocvMAK-V2u3sisTA_EDSbFkUIxOSAQ7ahOGHWdkQNkTvAdsMMVKMygdj64hytNDi5zOPyVrLAiZEimK3J-stTRU-VYeT-sOuXc0p_yVE1qjgI1kfyBNZz8PzxXy-WEyns9XFcrpahRPyTNZns8vwfHm1upqt5iH-lqvL44T8LU3MzhfLeRiuLmbhdDYLr1YXEwIswZbwtfquLD8vj_8AUIacQQ)