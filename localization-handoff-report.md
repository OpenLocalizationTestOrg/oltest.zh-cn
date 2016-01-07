# <a name='report-top'></a> Localization Handoff Report

## Summary
 Total Files | 2

## File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [e2e\7c434650-4068-4d17-92ac-8e5d58f6cfd2.md](https://github.com/OpenLocalizationTest/oltest/blob/57a2062f9578cb3944fbebecc1ca74c90f7bc98a/e2e/7c434650-4068-4d17-92ac-8e5d58f6cfd2.md) | HandedOffFailed | [Details](#fb094a45821f2d440d56f9b90b5fb0f998c0feb51)
 [e2e\a5ad255b-ddd9-4b6a-9e5f-8b0a511c55ab.md](https://github.com/OpenLocalizationTest/oltest/blob/57a2062f9578cb3944fbebecc1ca74c90f7bc98a/e2e/a5ad255b-ddd9-4b6a-9e5f-8b0a511c55ab.md) | HandedOffFailed | [Details](#244c3452b18e65c150172a3ef0fd6a817a37a1132)

## Item Details
##### <a name='fb094a45821f2d440d56f9b90b5fb0f998c0feb51'></a> Source: [e2e\7c434650-4068-4d17-92ac-8e5d58f6cfd2.md](https://github.com/OpenLocalizationTest/oltest/blob/57a2062f9578cb3944fbebecc1ca74c90f7bc98a/e2e/7c434650-4068-4d17-92ac-8e5d58f6cfd2.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#fb094a45821f2d440d56f9b90b5fb0f998c0feb51handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='244c3452b18e65c150172a3ef0fd6a817a37a1132'></a> Source: [e2e\a5ad255b-ddd9-4b6a-9e5f-8b0a511c55ab.md](https://github.com/OpenLocalizationTest/oltest/blob/57a2062f9578cb3944fbebecc1ca74c90f7bc98a/e2e/a5ad255b-ddd9-4b6a-9e5f-8b0a511c55ab.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#244c3452b18e65c150172a3ef0fd6a817a37a1132handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)


## Error Details
##### <a name='fb094a45821f2d440d56f9b90b5fb0f998c0feb51handoff_transform_failed'></a> Source: [e2e\7c434650-4068-4d17-92ac-8e5d58f6cfd2.md](#fb094a45821f2d440d56f9b90b5fb0f998c0feb51)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\7c434650-4068-4d17-92ac-8e5d58f6cfd2.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\7c434650-4068-4d17-92ac-8e5d58f6cfd2.md transformed failed.","internal_error_retriable":false,"exception_message":"Could not load file or assembly 'EdgeJs, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null' or one of its dependencies. The system cannot find the file specified.","exception_type":"System.IO.FileNotFoundException","stack_trace":"   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.Initialize()\r\n   at System.Lazy`1.CreateValue()\r\n   at System.Lazy`1.LazyInitValue()\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.MarkdownToXliffCore(Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion, Boolean useJavascriptTransformer) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationOptions config, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 251","extended_information":null}

##### <a name='244c3452b18e65c150172a3ef0fd6a817a37a1132handoff_transform_failed'></a> Source: [e2e\a5ad255b-ddd9-4b6a-9e5f-8b0a511c55ab.md](#244c3452b18e65c150172a3ef0fd6a817a37a1132)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\a5ad255b-ddd9-4b6a-9e5f-8b0a511c55ab.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\a5ad255b-ddd9-4b6a-9e5f-8b0a511c55ab.md transformed failed.","internal_error_retriable":false,"exception_message":"Could not load file or assembly 'EdgeJs, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null' or one of its dependencies. The system cannot find the file specified.","exception_type":"System.IO.FileNotFoundException","stack_trace":"   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.Initialize()\r\n   at System.Lazy`1.CreateValue()\r\n--- End of stack trace from previous location where exception was thrown ---\r\n   at System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()\r\n   at System.Lazy`1.get_Value()\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.MarkdownToXliffCore(Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion, Boolean useJavascriptTransformer) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationOptions config, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 251","extended_information":null}


Generated by OpenLocalization.
