# <a name='report-top'></a> Localization Report

## Summary
 Property | Value 
 -------- | ----- 
 Total Files | 2
[ Handoff Failed Files ](#handoff-failed-list)| 1
[ Handoff Success Files ](#handoff-success-list)| 0
[ Handback Failed Files ](#handback-failed-list)| 0
[ Out Of Sync Handback Files ](#outofsync-handback-success-list)| 0
[ In Sync Handback Files ](#insync-handback-success-list)| 0
[ Ignored Files ](#ignored-list)| 1

## <a name='handoff-failed-list'></a> Handoff Failed File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [e2e\4c875aaf-fe72-439b-b6c0-ada76404ea0b.md](https://github.com/OpenLocalizationTest/oltest/blob/edd1036e8decc3a71dd19c999436a41aa71c74eb/e2e/4c875aaf-fe72-439b-b6c0-ada76404ea0b.md) | HandedOffFailed | [Details](#b367efbae0d3eb909fcdd17549fbe0573f9a58ef1)

## <a name='handoff-success-list'></a> Handoff Sucess File List

## <a name='handback-failed-list'></a> Handback Failed File List

## <a name='outofsync-handback-success-list'></a> Out Of Sync Handback Success File List

## <a name='insync-handback-success-list'></a> In Sync Handback File Success List

## <a name='ignored-list'></a> Ignored File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/bb8555aa3c97004e447cc78f6c5feab189aab12d/.localization-config) | Ignored | [Details](#e4725be8631cbe979bbe0fa8b97cd75f1fd41d4d0)

## Item Details
##### <a name='e4725be8631cbe979bbe0fa8b97cd75f1fd41d4d0'></a> Source: [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/bb8555aa3c97004e447cc78f6c5feab189aab12d/.localization-config)
* Status: Ignored
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='b367efbae0d3eb909fcdd17549fbe0573f9a58ef1'></a> Source: [e2e\4c875aaf-fe72-439b-b6c0-ada76404ea0b.md](https://github.com/OpenLocalizationTest/oltest/blob/edd1036e8decc3a71dd19c999436a41aa71c74eb/e2e/4c875aaf-fe72-439b-b6c0-ada76404ea0b.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#b367efbae0d3eb909fcdd17549fbe0573f9a58ef1handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)


## Error Details
##### <a name='b367efbae0d3eb909fcdd17549fbe0573f9a58ef1handoff_transform_failed'></a> Source: [e2e\4c875aaf-fe72-439b-b6c0-ada76404ea0b.md](#b367efbae0d3eb909fcdd17549fbe0573f9a58ef1)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\4c875aaf-fe72-439b-b6c0-ada76404ea0b.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\4c875aaf-fe72-439b-b6c0-ada76404ea0b.md transformed failed.","internal_error_retriable":false,"exception_message":"Invalid Xml when parsing: <p>hello <br> world</p>.","exception_type":"System.ArgumentException","stack_trace":"   at Microsoft.Content.Build.Components.MarkdownHtmlBlock..ctor(String value)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.<ParseHtmlQuote>b__c(Match match, List`1 itemList)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.ParseBlockItemCommon(List`1 inputItems, Regex regex, Action`2 action)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.ParseHtmlQuote(List`1 inputItems)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadInternal(String fileContent)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadFromContent(String fileContent)\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownTransformer.MarkdownToXliffCore(Stream markdownStream, Stream xliffStream, Stream sklStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion) in D:\\Workspace\\OpenLocalization\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationConfig config, Dictionary`2 filePathInfo) in D:\\Workspace\\OpenLocalization\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 255","extended_information":null}


Generated by OpenLocalization.
