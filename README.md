# Leading-indicators-of-economic-growth-by-ellis2013nz

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

The R package nz-lead-indicators is attached in this repository as .ZIP file.

Nz-Lead-Indicators Package - A Brief Introduction
==================================================

Understanding good lead indicators for the New Zealand economy

This repository aims to understand what would be good lead indicators for the New Zealand economy. The original motivation was controversy about the ANZ business confidence index, but the issue is of broader interest.The following official statistics are available monthly, within a month of their reference period:

        Electronic card transactions
        Food price index
        Transport vehicle registrations
        International travel and migration
        Overseas merchandise trade
        Building consents issued
        Livestock slaughtering statistics

these make good candidates for lead indicators. Other non-official statistics candidates are the monthly ANZ business outlook, and the NZIER Quarterly Survey of Business Opinion (QBSO).

The OECD business confidence data is based on monthly interpolations of the NZIER QBSO, but is more readily available as a time series than either the ANZ and NZIER series, so I will probably use this as a stand-in for business confidence in general.Proposed method is to use all the candidate leading indicators as explanatory variables in a regression and use the lasso or other methods to identify the most effective subset of variables; or at least to get some general comparisons of them.
