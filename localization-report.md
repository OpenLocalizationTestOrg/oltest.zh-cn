# <a name='report-top'></a> Localization Report

## Summary
 Property | Value 
 -------- | ----- 
 Total Files | 3
[ Handoff Failed Files ](#handoff-failed-list)| 1
[ Handoff Success Files ](#handoff-success-list)| 1
[ Handback Failed Files ](#handback-failed-list)| 0
[ Out Of Sync Handback Files ](#outofsync-handback-success-list)| 0
[ In Sync Handback Files ](#insync-handback-success-list)| 0
[ Ignored Files ](#ignored-list)| 1

## <a name='handoff-failed-list'></a> Handoff Failed File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [e2e\677c4ef2-71df-4671-820f-02614110ce22.md](https://github.com/OpenLocalizationTest/oltest/blob/4a6097a49941ccbf8592cb3c7eacd25328bfe862/e2e/677c4ef2-71df-4671-820f-02614110ce22.md) | HandedOffFailed | [Details](#cf696fe2466745f17c747a76e87a9b97928a84b01)

## <a name='handoff-success-list'></a> Handoff Sucess File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [e2e\90c8f006-935c-4f9c-ad38-5c5cc4f0d460.md](https://github.com/OpenLocalizationTest/oltest/blob/4a6097a49941ccbf8592cb3c7eacd25328bfe862/e2e/90c8f006-935c-4f9c-ad38-5c5cc4f0d460.md) | HandedOffSuccess | [Details](#7baaa5115d2f568a76284d43e4bf7a40ee2b26f92)

## <a name='handback-failed-list'></a> Handback Failed File List

## <a name='outofsync-handback-success-list'></a> Out Of Sync Handback Success File List

## <a name='insync-handback-success-list'></a> In Sync Handback File Success List

## <a name='ignored-list'></a> Ignored File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/4a6097a49941ccbf8592cb3c7eacd25328bfe862/.localization-config) | Ignored | [Details](#e4725be8631cbe979bbe0fa8b97cd75f1fd41d4d0)

## Item Details
##### <a name='e4725be8631cbe979bbe0fa8b97cd75f1fd41d4d0'></a> Source: [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/4a6097a49941ccbf8592cb3c7eacd25328bfe862/.localization-config)
* Status: Ignored
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='cf696fe2466745f17c747a76e87a9b97928a84b01'></a> Source: [e2e\677c4ef2-71df-4671-820f-02614110ce22.md](https://github.com/OpenLocalizationTest/oltest/blob/4a6097a49941ccbf8592cb3c7eacd25328bfe862/e2e/677c4ef2-71df-4671-820f-02614110ce22.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#cf696fe2466745f17c747a76e87a9b97928a84b01handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='7baaa5115d2f568a76284d43e4bf7a40ee2b26f92'></a> Source: [e2e\90c8f006-935c-4f9c-ad38-5c5cc4f0d460.md](https://github.com/OpenLocalizationTest/oltest/blob/4a6097a49941ccbf8592cb3c7eacd25328bfe862/e2e/90c8f006-935c-4f9c-ad38-5c5cc4f0d460.md)
* Status: HandedOffSuccess
* Target File: 
* Handoff File: [90c8f006-935c-4f9c-ad38-5c5cc4f0d460.e4b5d06be52ad15985cd21f84e6d3fb934ae48ec.zh-cn.xlf](https://github.com/OpenLocalizationTestOrg/olhandoff/blob/f1ed4f144f6602809f91bdca9d34491ebc6c22a8/ol-handoff/OpenLocalizationTestOrg/oltest.zh-cn/yufeih/90c8f006-935c-4f9c-ad38-5c5cc4f0d460.e4b5d06be52ad15985cd21f84e6d3fb934ae48ec.zh-cn.xlf)
* Handoff Datetime: 2016-01-07 09:17:56
* Handoff Reason: Include
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)


## Error Details
##### <a name='cf696fe2466745f17c747a76e87a9b97928a84b01handoff_transform_failed'></a> Source: [e2e\677c4ef2-71df-4671-820f-02614110ce22.md](#cf696fe2466745f17c747a76e87a9b97928a84b01)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\677c4ef2-71df-4671-820f-02614110ce22.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\677c4ef2-71df-4671-820f-02614110ce22.md transformed failed.","internal_error_retriable":false,"exception_message":"Invalid Xml when parsing: <p>hello <br> world</p>.","exception_type":"System.ArgumentException","stack_trace":"   at Microsoft.Content.Build.Components.MarkdownHtmlBlock..ctor(String value)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.<>c.<ParseHtmlQuote>b__23_0(Match match, List`1 itemList)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.ParseBlockItemCommon(List`1 inputItems, Regex regex, Action`2 action)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadInternal(String fileContent)\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownTransformer.MarkdownToXliffCore(Stream markdownStream, Stream xliffStream, Stream sklStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion, Boolean useJavascriptTransformer) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationOptions config, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 251","extended_information":null}


Generated by OpenLocalization.
