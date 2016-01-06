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
 [e2e\8e82e117-73ae-493d-ad39-87726cb8f311.md](https://github.com/OpenLocalizationTest/oltest/blob/11412e727f13cd7ba46d57177374278f01e93b36/e2e/8e82e117-73ae-493d-ad39-87726cb8f311.md) | HandedOffFailed | [Details](#db720e1e0ab8a3de12f432b665b4b7500d65317b1)

## <a name='handoff-success-list'></a> Handoff Sucess File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [e2e\cc808abe-04cc-4c0f-bb9e-aba438973ee1.md](https://github.com/OpenLocalizationTest/oltest/blob/11412e727f13cd7ba46d57177374278f01e93b36/e2e/cc808abe-04cc-4c0f-bb9e-aba438973ee1.md) | HandedOffSuccess | [Details](#e411eaa3e657c37c1f0d66d90eb3d0ff45193d312)

## <a name='handback-failed-list'></a> Handback Failed File List

## <a name='outofsync-handback-success-list'></a> Out Of Sync Handback Success File List

## <a name='insync-handback-success-list'></a> In Sync Handback File Success List

## <a name='ignored-list'></a> Ignored File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/11412e727f13cd7ba46d57177374278f01e93b36/.localization-config) | Ignored | [Details](#e4725be8631cbe979bbe0fa8b97cd75f1fd41d4d0)

## Item Details
##### <a name='e4725be8631cbe979bbe0fa8b97cd75f1fd41d4d0'></a> Source: [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/11412e727f13cd7ba46d57177374278f01e93b36/.localization-config)
* Status: Ignored
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='db720e1e0ab8a3de12f432b665b4b7500d65317b1'></a> Source: [e2e\8e82e117-73ae-493d-ad39-87726cb8f311.md](https://github.com/OpenLocalizationTest/oltest/blob/11412e727f13cd7ba46d57177374278f01e93b36/e2e/8e82e117-73ae-493d-ad39-87726cb8f311.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#db720e1e0ab8a3de12f432b665b4b7500d65317b1handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='e411eaa3e657c37c1f0d66d90eb3d0ff45193d312'></a> Source: [e2e\cc808abe-04cc-4c0f-bb9e-aba438973ee1.md](https://github.com/OpenLocalizationTest/oltest/blob/11412e727f13cd7ba46d57177374278f01e93b36/e2e/cc808abe-04cc-4c0f-bb9e-aba438973ee1.md)
* Status: HandedOffSuccess
* Target File: 
* Handoff File: [cc808abe-04cc-4c0f-bb9e-aba438973ee1.208a6956643531cba6ee7ab49aad3a7609ec2802.zh-cn.xlf](https://github.com/OpenLocalizationTestOrg/olhandoff/blob/f22202dbb29c17d3b7442c20d361bc8aa847689c/ol-handoff/OpenLocalizationTestOrg/oltest.zh-cn/qimu/cc808abe-04cc-4c0f-bb9e-aba438973ee1.208a6956643531cba6ee7ab49aad3a7609ec2802.zh-cn.xlf)
* Handoff Datetime: 2016-01-06 03:52:45
* Handoff Reason: Include
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)


## Error Details
##### <a name='db720e1e0ab8a3de12f432b665b4b7500d65317b1handoff_transform_failed'></a> Source: [e2e\8e82e117-73ae-493d-ad39-87726cb8f311.md](#db720e1e0ab8a3de12f432b665b4b7500d65317b1)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\8e82e117-73ae-493d-ad39-87726cb8f311.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\8e82e117-73ae-493d-ad39-87726cb8f311.md transformed failed.","internal_error_retriable":false,"exception_message":"Invalid Xml when parsing: <p>hello <br> world</p>.","exception_type":"System.ArgumentException","stack_trace":"   at Microsoft.Content.Build.Components.MarkdownHtmlBlock..ctor(String value)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.<ParseHtmlQuote>b__c(Match match, List`1 itemList)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.ParseBlockItemCommon(List`1 inputItems, Regex regex, Action`2 action)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.ParseHtmlQuote(List`1 inputItems)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadInternal(String fileContent)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadFromContent(String fileContent)\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownTransformer.MarkdownToXliffCore(Stream markdownStream, Stream xliffStream, Stream sklStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion) in D:\\Workspace\\OpenLocalization\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationConfig config, Dictionary`2 filePathInfo) in D:\\Workspace\\OpenLocalization\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 255","extended_information":null}


Generated by OpenLocalization.
