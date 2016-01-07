# <a name='report-top'></a> Localization Report

## Summary
 Property | Value 
 -------- | ----- 
 Total Files | 3
[ Handoff Failed Files ](#handoff-failed-list)| 2
[ Handoff Success Files ](#handoff-success-list)| 0
[ Handback Failed Files ](#handback-failed-list)| 0
[ Out Of Sync Handback Files ](#outofsync-handback-success-list)| 0
[ In Sync Handback Files ](#insync-handback-success-list)| 0
[ Ignored Files ](#ignored-list)| 1

## <a name='handoff-failed-list'></a> Handoff Failed File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [e2e\6393be14-00c4-4a0b-bdf6-8d63adef929f.md](https://github.com/OpenLocalizationTest/oltest/blob/df34c5c6f4668089ffed8bc40c00fa04a40c67ae/e2e/6393be14-00c4-4a0b-bdf6-8d63adef929f.md) | HandedOffFailed | [Details](#acff2d9ba879e028ae4f5961d1ef51c96befc37b1)
 [e2e\c271d128-5818-4470-8486-8762ce2a9bf4.md](https://github.com/OpenLocalizationTest/oltest/blob/df34c5c6f4668089ffed8bc40c00fa04a40c67ae/e2e/c271d128-5818-4470-8486-8762ce2a9bf4.md) | HandedOffFailed | [Details](#53a1b9674bdcd372cd86e99b3064b7346838c6b12)

## <a name='handoff-success-list'></a> Handoff Sucess File List

## <a name='handback-failed-list'></a> Handback Failed File List

## <a name='outofsync-handback-success-list'></a> Out Of Sync Handback Success File List

## <a name='insync-handback-success-list'></a> In Sync Handback File Success List

## <a name='ignored-list'></a> Ignored File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/df34c5c6f4668089ffed8bc40c00fa04a40c67ae/.localization-config) | Ignored | [Details](#e4725be8631cbe979bbe0fa8b97cd75f1fd41d4d0)

## Item Details
##### <a name='e4725be8631cbe979bbe0fa8b97cd75f1fd41d4d0'></a> Source: [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/df34c5c6f4668089ffed8bc40c00fa04a40c67ae/.localization-config)
* Status: Ignored
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='acff2d9ba879e028ae4f5961d1ef51c96befc37b1'></a> Source: [e2e\6393be14-00c4-4a0b-bdf6-8d63adef929f.md](https://github.com/OpenLocalizationTest/oltest/blob/df34c5c6f4668089ffed8bc40c00fa04a40c67ae/e2e/6393be14-00c4-4a0b-bdf6-8d63adef929f.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#acff2d9ba879e028ae4f5961d1ef51c96befc37b1handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='53a1b9674bdcd372cd86e99b3064b7346838c6b12'></a> Source: [e2e\c271d128-5818-4470-8486-8762ce2a9bf4.md](https://github.com/OpenLocalizationTest/oltest/blob/df34c5c6f4668089ffed8bc40c00fa04a40c67ae/e2e/c271d128-5818-4470-8486-8762ce2a9bf4.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#53a1b9674bdcd372cd86e99b3064b7346838c6b12handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)


## Error Details
##### <a name='acff2d9ba879e028ae4f5961d1ef51c96befc37b1handoff_transform_failed'></a> Source: [e2e\6393be14-00c4-4a0b-bdf6-8d63adef929f.md](#acff2d9ba879e028ae4f5961d1ef51c96befc37b1)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\6393be14-00c4-4a0b-bdf6-8d63adef929f.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\6393be14-00c4-4a0b-bdf6-8d63adef929f.md transformed failed.","internal_error_retriable":false,"exception_message":"Could not load file or assembly 'EdgeJs, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null' or one of its dependencies. The system cannot find the file specified.","exception_type":"System.IO.FileNotFoundException","stack_trace":"   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.Initialize()\r\n   at System.Lazy`1.CreateValue()\r\n   at System.Lazy`1.LazyInitValue()\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.MarkdownToXliffCore(Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion, Boolean useJavascriptTransformer) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationOptions config, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 251","extended_information":null}

##### <a name='53a1b9674bdcd372cd86e99b3064b7346838c6b12handoff_transform_failed'></a> Source: [e2e\c271d128-5818-4470-8486-8762ce2a9bf4.md](#53a1b9674bdcd372cd86e99b3064b7346838c6b12)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\c271d128-5818-4470-8486-8762ce2a9bf4.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\c271d128-5818-4470-8486-8762ce2a9bf4.md transformed failed.","internal_error_retriable":false,"exception_message":"Could not load file or assembly 'EdgeJs, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null' or one of its dependencies. The system cannot find the file specified.","exception_type":"System.IO.FileNotFoundException","stack_trace":"   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.Initialize()\r\n   at System.Lazy`1.CreateValue()\r\n--- End of stack trace from previous location where exception was thrown ---\r\n   at System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()\r\n   at System.Lazy`1.get_Value()\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.MarkdownToXliffCore(Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion, Boolean useJavascriptTransformer) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationOptions config, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 251","extended_information":null}


Generated by OpenLocalization.
