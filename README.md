# aa
curl -i -H "Authorization: Bearer YOUR_PAT_TOKEN" -H "Accept: application/json" "https://alm-confluence.systems.uk.hsbc/confluence/rest/api/space?limit=1"


curl -i -H "Authorization: Bearer YOUR_PAT_TOKEN" -H "Accept: application/json" "https://alm-confluence.systems.uk.hsbc/confluence/rest/api/content/1864386183?expand=body.storage"


=IFERROR(SUMPRODUCT(--ISNUMBER(SEARCH(A2,'HK_Report_List'!F:F)),--ISNUMBER(SEARCH(B2,'HK_Report_List'!F:F)))>0,FALSE)
