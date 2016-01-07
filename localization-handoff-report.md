# <a name='report-top'></a> Localization Handoff Report

## Summary
 Total Files | 2

## File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [e2e\3708ebb1-f26c-4a09-870b-4d99a370a274.md](https://github.com/OpenLocalizationTest/oltest/blob/78b708c282b049768b27781dacfaff13daa0c5cf/e2e/3708ebb1-f26c-4a09-870b-4d99a370a274.md) | HandedOffFailed | [Details](#9046f52f29eab4c8b87da4efd2a16177efb04b091)
 [e2e\fbcead5c-34c5-4743-a04b-69afe840fc62.md](https://github.com/OpenLocalizationTest/oltest/blob/78b708c282b049768b27781dacfaff13daa0c5cf/e2e/fbcead5c-34c5-4743-a04b-69afe840fc62.md) | HandedOffFailed | [Details](#9174c21f8401352712f0f4666a274294550ec9072)

## Item Details
##### <a name='9046f52f29eab4c8b87da4efd2a16177efb04b091'></a> Source: [e2e\3708ebb1-f26c-4a09-870b-4d99a370a274.md](https://github.com/OpenLocalizationTest/oltest/blob/78b708c282b049768b27781dacfaff13daa0c5cf/e2e/3708ebb1-f26c-4a09-870b-4d99a370a274.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#9046f52f29eab4c8b87da4efd2a16177efb04b091handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='9174c21f8401352712f0f4666a274294550ec9072'></a> Source: [e2e\fbcead5c-34c5-4743-a04b-69afe840fc62.md](https://github.com/OpenLocalizationTest/oltest/blob/78b708c282b049768b27781dacfaff13daa0c5cf/e2e/fbcead5c-34c5-4743-a04b-69afe840fc62.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#9174c21f8401352712f0f4666a274294550ec9072handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)


## Error Details
##### <a name='9046f52f29eab4c8b87da4efd2a16177efb04b091handoff_transform_failed'></a> Source: [e2e\3708ebb1-f26c-4a09-870b-4d99a370a274.md](#9046f52f29eab4c8b87da4efd2a16177efb04b091)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\3708ebb1-f26c-4a09-870b-4d99a370a274.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\3708ebb1-f26c-4a09-870b-4d99a370a274.md transformed failed.","internal_error_retriable":false,"exception_message":"Could not load file or assembly 'EdgeJs, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null' or one of its dependencies. The system cannot find the file specified.","exception_type":"System.IO.FileNotFoundException","stack_trace":"   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.Initialize()\r\n   at System.Lazy`1.CreateValue()\r\n   at System.Lazy`1.LazyInitValue()\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.MarkdownToXliffCore(Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion, Boolean useJavascriptTransformer) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationOptions config, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 251","extended_information":null}

##### <a name='9174c21f8401352712f0f4666a274294550ec9072handoff_transform_failed'></a> Source: [e2e\fbcead5c-34c5-4743-a04b-69afe840fc62.md](#9174c21f8401352712f0f4666a274294550ec9072)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\fbcead5c-34c5-4743-a04b-69afe840fc62.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\fbcead5c-34c5-4743-a04b-69afe840fc62.md transformed failed.","internal_error_retriable":false,"exception_message":"Could not load file or assembly 'EdgeJs, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null' or one of its dependencies. The system cannot find the file specified.","exception_type":"System.IO.FileNotFoundException","stack_trace":"   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.Initialize()\r\n   at System.Lazy`1.CreateValue()\r\n--- End of stack trace from previous location where exception was thrown ---\r\n   at System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()\r\n   at System.Lazy`1.get_Value()\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.MarkdownToXliffCore(Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion, Boolean useJavascriptTransformer) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationOptions config, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 251","extended_information":null}


Generated by OpenLocalization.
