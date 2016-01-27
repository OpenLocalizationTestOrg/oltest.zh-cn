# <a name='report-top'></a> Localization Report

## Summary
 Property | Value 
 -------- | ----- 
 Total Files | 2
[ Handoff Failed Files ](#handoff-failed-list)| 1
[ Handoff Success Files ](#handoff-success-list)| 0
[ Archive Failed Files ](#archive-failed-list)| 0
[ Archive Success Files ](#archive-success-list)| 0
[ Handback Failed Files ](#handback-failed-list)| 0
[ Out Of Sync Handback Files ](#outofsync-handback-success-list)| 0
[ In Sync Handback Files ](#insync-handback-success-list)| 0
[ Ignored Files ](#ignored-list)| 1

## <a name='handoff-failed-list'></a> Handoff Failed File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [e2e\fc9bd0dc-745f-45f5-8096-bf9b461f5a24.md](https://github.com/OpenLocalizationTest/oltest/blob/6bb0f631995bc33ad54c39ced02eac6a756347b7/e2e/fc9bd0dc-745f-45f5-8096-bf9b461f5a24.md) | HandedOffFailed | [Details](#c1afa8896535d68e3e9d26835ec37c48388531121)

## <a name='handoff-success-list'></a> Handoff Success File List

## <a name='archive-failed-list'></a> Archive Failed File List

## <a name='archive-success-list'></a> Archive Success File List

## <a name='handback-failed-list'></a> Handback Failed File List

## <a name='outofsync-handback-success-list'></a> Out Of Sync Handback Success File List

## <a name='insync-handback-success-list'></a> In Sync Handback File Success List

## <a name='ignored-list'></a> Ignored File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/6bb0f631995bc33ad54c39ced02eac6a756347b7/.localization-config) | Ignored | [Details](#e4725be8631cbe979bbe0fa8b97cd75f1fd41d4d0)

## Item Details
##### <a name='e4725be8631cbe979bbe0fa8b97cd75f1fd41d4d0'></a> Source: [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/6bb0f631995bc33ad54c39ced02eac6a756347b7/.localization-config)
* Status: Ignored
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Archive File: 
* Archive Datetime: 0001-01-01 00:00:00
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='c1afa8896535d68e3e9d26835ec37c48388531121'></a> Source: [e2e\fc9bd0dc-745f-45f5-8096-bf9b461f5a24.md](https://github.com/OpenLocalizationTest/oltest/blob/6bb0f631995bc33ad54c39ced02eac6a756347b7/e2e/fc9bd0dc-745f-45f5-8096-bf9b461f5a24.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#c1afa8896535d68e3e9d26835ec37c48388531121handoff_transform_failed)
* Archive File: 
* Archive Datetime: 0001-01-01 00:00:00
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)


## Error Details
##### <a name='c1afa8896535d68e3e9d26835ec37c48388531121handoff_transform_failed'></a> Source: [e2e\fc9bd0dc-745f-45f5-8096-bf9b461f5a24.md](#c1afa8896535d68e3e9d26835ec37c48388531121)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\fc9bd0dc-745f-45f5-8096-bf9b461f5a24.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\fc9bd0dc-745f-45f5-8096-bf9b461f5a24.md transformed failed.","internal_error_retriable":false,"exception_message":"Invalid Xml when parsing: <p>hello <br> world</p>.","exception_type":"System.ArgumentException","stack_trace":"   at Microsoft.Content.Build.Components.MarkdownHtmlBlock..ctor(String value)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.<ParseHtmlQuote>b__c(Match match, List`1 itemList)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.ParseBlockItemCommon(List`1 inputItems, Regex regex, Action`2 action)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.ParseHtmlQuote(List`1 inputItems)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadInternal(String fileContent)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadFromContent(String fileContent)\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownTransformer.MarkdownToXliffCore(Stream markdownStream, Stream xliffStream, Stream sklStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion, Boolean useJavascriptTransformer) in E:\\VSC\\OL\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationOptions config, Dictionary`2 filePathInfo) in E:\\VSC\\OL\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 275","extended_information":null}


Generated by OpenLocalization.
