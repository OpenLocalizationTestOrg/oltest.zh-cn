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
 [e2e\4fc6571c-4f9e-45bf-94c4-0c2ba267a73e.md](https://github.com/OpenLocalizationTest/oltest/blob/c6da3cfa8f980cac4c0a429afee6fb4ef15a62b7/e2e/4fc6571c-4f9e-45bf-94c4-0c2ba267a73e.md) | HandedOffFailed | [Details](#c4f57c0f572f7bfe9cc6dbeedd0648084d844a721)
 [e2e\f7da928c-d7d0-444a-8080-a32e5c51d041.md](https://github.com/OpenLocalizationTest/oltest/blob/c6da3cfa8f980cac4c0a429afee6fb4ef15a62b7/e2e/f7da928c-d7d0-444a-8080-a32e5c51d041.md) | HandedOffFailed | [Details](#8cfe007d748623d7a83ccb6dc41eae1863be220b2)

## <a name='handoff-success-list'></a> Handoff Sucess File List

## <a name='handback-failed-list'></a> Handback Failed File List

## <a name='outofsync-handback-success-list'></a> Out Of Sync Handback Success File List

## <a name='insync-handback-success-list'></a> In Sync Handback File Success List

## <a name='ignored-list'></a> Ignored File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/c6da3cfa8f980cac4c0a429afee6fb4ef15a62b7/.localization-config) | Ignored | [Details](#e4725be8631cbe979bbe0fa8b97cd75f1fd41d4d0)

## Item Details
##### <a name='e4725be8631cbe979bbe0fa8b97cd75f1fd41d4d0'></a> Source: [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/c6da3cfa8f980cac4c0a429afee6fb4ef15a62b7/.localization-config)
* Status: Ignored
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='c4f57c0f572f7bfe9cc6dbeedd0648084d844a721'></a> Source: [e2e\4fc6571c-4f9e-45bf-94c4-0c2ba267a73e.md](https://github.com/OpenLocalizationTest/oltest/blob/c6da3cfa8f980cac4c0a429afee6fb4ef15a62b7/e2e/4fc6571c-4f9e-45bf-94c4-0c2ba267a73e.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#c4f57c0f572f7bfe9cc6dbeedd0648084d844a721handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='8cfe007d748623d7a83ccb6dc41eae1863be220b2'></a> Source: [e2e\f7da928c-d7d0-444a-8080-a32e5c51d041.md](https://github.com/OpenLocalizationTest/oltest/blob/c6da3cfa8f980cac4c0a429afee6fb4ef15a62b7/e2e/f7da928c-d7d0-444a-8080-a32e5c51d041.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#8cfe007d748623d7a83ccb6dc41eae1863be220b2handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)


## Error Details
##### <a name='c4f57c0f572f7bfe9cc6dbeedd0648084d844a721handoff_transform_failed'></a> Source: [e2e\4fc6571c-4f9e-45bf-94c4-0c2ba267a73e.md](#c4f57c0f572f7bfe9cc6dbeedd0648084d844a721)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\4fc6571c-4f9e-45bf-94c4-0c2ba267a73e.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\4fc6571c-4f9e-45bf-94c4-0c2ba267a73e.md transformed failed.","internal_error_retriable":false,"exception_message":"Could not load file or assembly 'EdgeJs, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null' or one of its dependencies. The system cannot find the file specified.","exception_type":"System.IO.FileNotFoundException","stack_trace":"   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.Initialize()\r\n   at System.Lazy`1.CreateValue()\r\n   at System.Lazy`1.LazyInitValue()\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.MarkdownToXliffCore(Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion, Boolean useJavascriptTransformer) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationOptions config, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 251","extended_information":null}

##### <a name='8cfe007d748623d7a83ccb6dc41eae1863be220b2handoff_transform_failed'></a> Source: [e2e\f7da928c-d7d0-444a-8080-a32e5c51d041.md](#8cfe007d748623d7a83ccb6dc41eae1863be220b2)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\f7da928c-d7d0-444a-8080-a32e5c51d041.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\f7da928c-d7d0-444a-8080-a32e5c51d041.md transformed failed.","internal_error_retriable":false,"exception_message":"Could not load file or assembly 'EdgeJs, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null' or one of its dependencies. The system cannot find the file specified.","exception_type":"System.IO.FileNotFoundException","stack_trace":"   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.Initialize()\r\n   at System.Lazy`1.CreateValue()\r\n--- End of stack trace from previous location where exception was thrown ---\r\n   at System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()\r\n   at System.Lazy`1.get_Value()\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.MarkdownToXliffCore(Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion, Boolean useJavascriptTransformer) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationOptions config, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 251","extended_information":null}


Generated by OpenLocalization.
