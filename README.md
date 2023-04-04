# AppMeasurement for Adobe Analytics

>ℹ️ For new implementations we recommend using [Adobe Experience Platform Web SDK][1] which can be used to collect data for Analytics as well as other Adobe solutions and even third parties.

AppMeasurement is a stand alone JavaScript library used to implement Adobe Analytics when not using the [Adobe Tag Management Analytics Extension][2]. You can download the [latest release][3] of AppMeasurement to get started.

## Source Files

|File                                            |Documentation                     |
|:-----------------------------------------------|:---------------------------------|
|AppMeasurement.js                               |[Main analytics library][4]            |
|AppMeasurement_Module_AudienceManagement.js     |[Server side forwarding module][5]     |
|AppMeasurement_Module_Integrate.js              |[Partner integration module][6]        |
|VisitorAPI.js                                   |[Identity service library][7]          |

[1]: https://experienceleague.adobe.com/docs/experience-platform/edge/home.html
[2]: https://experienceleague.adobe.com/docs/experience-platform/tags/extensions/adobe/analytics/overview.html
[3]: https://git.corp.adobe.com/analytics-data-collection/appmeasurement/releases/latest
[4]: https://experienceleague.adobe.com/docs/analytics/implementation/js/overview.html
[5]: https://experienceleague.adobe.com/docs/analytics/admin/admin-tools/server-side-forwarding/ssf-requirements.html
[6]: https://experienceleague.adobe.com/docs/analytics/implementation/vars/integrate.html
[7]: https://experienceleague.adobe.com/docs/id-service/using/implementation/setup-analytics.html
