---
uid: crmscript_ref_NSDiagnosticsAgent_GetWebAppUsagesForPeriod
title: WebAppUsage[] GetWebAppUsagesForPeriod(DateTime fromDate, DateTime toDate, String searchTerm)
intellisense: NSDiagnosticsAgent.GetWebAppUsagesForPeriod
keywords: NSDiagnosticsAgent, GetWebAppUsagesForPeriod
so.topic: reference
---

# WebAppUsage[] GetWebAppUsagesForPeriod(DateTime fromDate, DateTime toDate, String searchTerm)

Get all WebAppUsages for a given period, that match an optional search term

## Parameters

| Parameter | Type | Description |
|---|---|---|
| fromDate | DateTime | |
| toDate | DateTime | |
| searchTerm | String | ViewState search term. '%' is the wildcard character, for example, 'Pocket%' will match all viewstates starting with 'Pocket'. If empty, all viewstates will be matched |