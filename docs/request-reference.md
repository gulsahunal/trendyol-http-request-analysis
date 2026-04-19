# Request Reference

This document summarizes the key HTTP requests captured from Chrome DevTools during Trendyol website analysis.

| Task | Method | Status | Request URL |
| --- | --- | --- | --- |
| 1 | GET | 200 OK | https://www.trendyol.com/ |
| 2 | POST | 400 Bad Request | https://auth.trendyol.com/login |
| 3 | GET | 200 OK | Captured in network panel (request URL not fully visible in export). |
| 4 | GET | 301 Moved Permanently | https://www.trendyol.com/Hesabim/Favoriler |
| 5 | PUT | 200 OK | https://apigw.trendyol.com/discovery-web-websfxcheckoutbasket-santral/quantity?channelId=1 |
| 6 | DELETE | 204 No Content | https://apigw.trendyol.com/discovery-web-websfxcheckoutbasket-santral/remove/830255823-8737943da37c4d9060b9372f0940b085-61?channelId=1 |
| 7 | POST | 400 Bad Request | https://apigw.trendyol.com/discovery-web-websfxmember-santral/guest-user?channelId=1 |

Notes:
- Some exported screenshots do not show the full request URL in visible area.
- Values were taken from captured network panel evidence when visible.
