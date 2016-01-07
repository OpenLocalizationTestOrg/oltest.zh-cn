# <a name='report-top'></a> Localization Handoff Report

## Summary
 Total Files | 2

## File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [e2e\f78c965a-23de-4b03-8d6e-4a67edd5ef21.md](https://github.com/OpenLocalizationTest/oltest/blob/c70e7e5c33f0dac2acffca3611b6669ad4c27dd0/e2e/f78c965a-23de-4b03-8d6e-4a67edd5ef21.md) | HandedOffFailed | [Details](#283547b757121e51dff28a2d1114cb6e0653cf4a1)
 [e2e\fa2618e4-8d31-432e-a5b0-5569971aa063.md](https://github.com/OpenLocalizationTest/oltest/blob/c70e7e5c33f0dac2acffca3611b6669ad4c27dd0/e2e/fa2618e4-8d31-432e-a5b0-5569971aa063.md) | HandedOffFailed | [Details](#3e11d45546f1038014b8704d436ae8f0fb71d2ad2)

## Item Details
##### <a name='283547b757121e51dff28a2d1114cb6e0653cf4a1'></a> Source: [e2e\f78c965a-23de-4b03-8d6e-4a67edd5ef21.md](https://github.com/OpenLocalizationTest/oltest/blob/c70e7e5c33f0dac2acffca3611b6669ad4c27dd0/e2e/f78c965a-23de-4b03-8d6e-4a67edd5ef21.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#283547b757121e51dff28a2d1114cb6e0653cf4a1handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='3e11d45546f1038014b8704d436ae8f0fb71d2ad2'></a> Source: [e2e\fa2618e4-8d31-432e-a5b0-5569971aa063.md](https://github.com/OpenLocalizationTest/oltest/blob/c70e7e5c33f0dac2acffca3611b6669ad4c27dd0/e2e/fa2618e4-8d31-432e-a5b0-5569971aa063.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#3e11d45546f1038014b8704d436ae8f0fb71d2ad2handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)


## Error Details
##### <a name='283547b757121e51dff28a2d1114cb6e0653cf4a1handoff_transform_failed'></a> Source: [e2e\f78c965a-23de-4b03-8d6e-4a67edd5ef21.md](#283547b757121e51dff28a2d1114cb6e0653cf4a1)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\f78c965a-23de-4b03-8d6e-4a67edd5ef21.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\f78c965a-23de-4b03-8d6e-4a67edd5ef21.md transformed failed.","internal_error_retriable":false,"exception_message":"Could not load file or assembly 'EdgeJs, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null' or one of its dependencies. The system cannot find the file specified.","exception_type":"System.IO.FileNotFoundException","stack_trace":"   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.Initialize()\r\n   at System.Lazy`1.CreateValue()\r\n   at System.Lazy`1.LazyInitValue()\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.MarkdownToXliffCore(Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion, Boolean useJavascriptTransformer) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationOptions config, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 251","extended_information":null}

##### <a name='3e11d45546f1038014b8704d436ae8f0fb71d2ad2handoff_transform_failed'></a> Source: [e2e\fa2618e4-8d31-432e-a5b0-5569971aa063.md](#3e11d45546f1038014b8704d436ae8f0fb71d2ad2)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\fa2618e4-8d31-432e-a5b0-5569971aa063.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\fa2618e4-8d31-432e-a5b0-5569971aa063.md transformed failed.","internal_error_retriable":false,"exception_message":"Could not load file or assembly 'EdgeJs, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null' or one of its dependencies. The system cannot find the file specified.","exception_type":"System.IO.FileNotFoundException","stack_trace":"   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.Initialize()\r\n   at System.Lazy`1.CreateValue()\r\n--- End of stack trace from previous location where exception was thrown ---\r\n   at System.Runtime.ExceptionServices.ExceptionDispatchInfo.Throw()\r\n   at System.Lazy`1.get_Value()\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.MarkdownToXliffCore(Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion, Boolean useJavascriptTransformer) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationOptions config, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 251","extended_information":null}


Generated by OpenLocalization.
