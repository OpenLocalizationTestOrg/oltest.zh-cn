# <a name='report-top'></a> Localization Handback Report

## Summary
 Total Files | 2

## File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [e2e\9c9fbe9d-6af6-4262-99c0-c8477e4ffe30.md](https://github.com/OpenLocalizationTest/oltest/blob/d4c75478f9af1f7d466c596bb66dfddd06d22a4d/e2e/9c9fbe9d-6af6-4262-99c0-c8477e4ffe30.md) | HandedBackFailed | [Details](#e120a5ddd640c2700e52d6c06381b3b5716576751)
 [e2e\e0b546bc-17a2-405d-8be7-ab8f42080f05.md](https://github.com/OpenLocalizationTest/oltest/blob/d4c75478f9af1f7d466c596bb66dfddd06d22a4d/e2e/e0b546bc-17a2-405d-8be7-ab8f42080f05.md) | HandedBackFailed | [Details](#1916f2cbff0c8eb82674fbd29825c24c8ad77f5f2)

## Item Details
##### <a name='e120a5ddd640c2700e52d6c06381b3b5716576751'></a> Source: [e2e\9c9fbe9d-6af6-4262-99c0-c8477e4ffe30.md](https://github.com/OpenLocalizationTest/oltest/blob/d4c75478f9af1f7d466c596bb66dfddd06d22a4d/e2e/9c9fbe9d-6af6-4262-99c0-c8477e4ffe30.md)
* Status: HandedBackFailed
* Target File: 
* Handoff File: [9c9fbe9d-6af6-4262-99c0-c8477e4ffe30.1f2bfeed8592a682a5ee09d090a000c9541be0f3.zh-cn.xlf](https://github.com/OpenLocalizationTestOrg/olhandoff/blob/00889f019f3b159da8f83b22fd226c19849c8d42/ol-handoff/OpenLocalizationTestOrg/oltest.zh-cn/yufeih/9c9fbe9d-6af6-4262-99c0-c8477e4ffe30.1f2bfeed8592a682a5ee09d090a000c9541be0f3.zh-cn.xlf)
* Handoff Datetime: 2016-01-07 07:55:53
* Handoff Reason: Include
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* Handback Error: [handback_transform_failed](#e120a5ddd640c2700e52d6c06381b3b5716576751handback_transform_failed)
* [Back to Top](#report-top)

##### <a name='1916f2cbff0c8eb82674fbd29825c24c8ad77f5f2'></a> Source: [e2e\e0b546bc-17a2-405d-8be7-ab8f42080f05.md](https://github.com/OpenLocalizationTest/oltest/blob/d4c75478f9af1f7d466c596bb66dfddd06d22a4d/e2e/e0b546bc-17a2-405d-8be7-ab8f42080f05.md)
* Status: HandedBackFailed
* Target File: 
* Handoff File: [e0b546bc-17a2-405d-8be7-ab8f42080f05.32c764deb1b7887dc8e5cdf1ba138b8ec8c787a5.zh-cn.xlf](https://github.com/OpenLocalizationTestOrg/olhandoff/blob/00889f019f3b159da8f83b22fd226c19849c8d42/ol-handoff/OpenLocalizationTestOrg/oltest.zh-cn/yufeih/e0b546bc-17a2-405d-8be7-ab8f42080f05.32c764deb1b7887dc8e5cdf1ba138b8ec8c787a5.zh-cn.xlf)
* Handoff Datetime: 2016-01-07 07:55:53
* Handoff Reason: Include
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* Handback Error: [handback_transform_failed](#1916f2cbff0c8eb82674fbd29825c24c8ad77f5f2handback_transform_failed)
* [Back to Top](#report-top)


## Error Details
##### <a name='e120a5ddd640c2700e52d6c06381b3b5716576751handback_transform_failed'></a> Source: [e2e\9c9fbe9d-6af6-4262-99c0-c8477e4ffe30.md](#e120a5ddd640c2700e52d6c06381b3b5716576751)
* Error Code: handback_transform_failed
* Error Message: Handback file: C:\gittest\OpenLocalizationTest\olhandback\f824b1\ol-handback\OpenLocalizationTestOrg\oltest.zh-cn\yufeih\9c9fbe9d-6af6-4262-99c0-c8477e4ffe30.1f2bfeed8592a682a5ee09d090a000c9541be0f3.zh-cn.xlf failed.
* Retriable: False
* Error Details: {"internal_error_code":"handback_transform_failed","internal_error_message":"Handback file: C:\\gittest\\OpenLocalizationTest\\olhandback\\f824b1\\ol-handback\\OpenLocalizationTestOrg\\oltest.zh-cn\\yufeih\\9c9fbe9d-6af6-4262-99c0-c8477e4ffe30.1f2bfeed8592a682a5ee09d090a000c9541be0f3.zh-cn.xlf failed.","internal_error_retriable":false,"exception_message":"Data at the root level is invalid. Line 1, position 1.","exception_type":"System.Xml.XmlException","stack_trace":"   at System.Xml.XmlTextReaderImpl.Throw(Exception e)\r\n   at System.Xml.XmlTextReaderImpl.ParseRootLevelWhitespace()\r\n   at System.Xml.XmlTextReaderImpl.ParseDocumentContent()\r\n   at System.Xml.XmlReader.MoveToContent()\r\n   at System.Xml.XmlReader.ReadStartElement(String name)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadSkeletonInternal(XmlReader reader)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadSkeleton(Stream stream)\r\n   at Microsoft.Content.Build.Components.XliffToMarkdownTransformHandler.Transform(ILocalizationFile source)\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownTransformer.XliffToMarkdownCore(Stream xliffStream, Stream sklStream, Stream markdownStream)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.XliffToMarkdown(IMarkdownTransformer markdownTransformer, Stream xliffStream, Stream skeletonStream, Stream targetStream)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.XliffToMarkdown(IMarkdownTransformer markdownTransformer, String xliffFile, String skeletonFile, String markdownFile)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.XliffToMarkdown(String skeletonFile, String xliffFile, String mdfile) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 40\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandbackFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, GitRepo handbackRepo, TranslationState translationInfo, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandbackCore.cs:line 356","extended_information":null}

##### <a name='1916f2cbff0c8eb82674fbd29825c24c8ad77f5f2handback_transform_failed'></a> Source: [e2e\e0b546bc-17a2-405d-8be7-ab8f42080f05.md](#1916f2cbff0c8eb82674fbd29825c24c8ad77f5f2)
* Error Code: handback_transform_failed
* Error Message: Handback file: C:\gittest\OpenLocalizationTest\olhandback\f824b1\ol-handback\OpenLocalizationTestOrg\oltest.zh-cn\yufeih\e0b546bc-17a2-405d-8be7-ab8f42080f05.32c764deb1b7887dc8e5cdf1ba138b8ec8c787a5.zh-cn.xlf failed.
* Retriable: False
* Error Details: {"internal_error_code":"handback_transform_failed","internal_error_message":"Handback file: C:\\gittest\\OpenLocalizationTest\\olhandback\\f824b1\\ol-handback\\OpenLocalizationTestOrg\\oltest.zh-cn\\yufeih\\e0b546bc-17a2-405d-8be7-ab8f42080f05.32c764deb1b7887dc8e5cdf1ba138b8ec8c787a5.zh-cn.xlf failed.","internal_error_retriable":false,"exception_message":"Data at the root level is invalid. Line 1, position 1.","exception_type":"System.Xml.XmlException","stack_trace":"   at System.Xml.XmlTextReaderImpl.Throw(Exception e)\r\n   at System.Xml.XmlTextReaderImpl.ParseRootLevelWhitespace()\r\n   at System.Xml.XmlTextReaderImpl.ParseDocumentContent()\r\n   at System.Xml.XmlReader.MoveToContent()\r\n   at System.Xml.XmlReader.ReadStartElement(String name)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadSkeletonInternal(XmlReader reader)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadSkeleton(Stream stream)\r\n   at Microsoft.Content.Build.Components.XliffToMarkdownTransformHandler.Transform(ILocalizationFile source)\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownTransformer.XliffToMarkdownCore(Stream xliffStream, Stream sklStream, Stream markdownStream)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.XliffToMarkdown(IMarkdownTransformer markdownTransformer, Stream xliffStream, Stream skeletonStream, Stream targetStream)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.XliffToMarkdown(IMarkdownTransformer markdownTransformer, String xliffFile, String skeletonFile, String markdownFile)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.XliffToMarkdown(String skeletonFile, String xliffFile, String mdfile) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 40\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandbackFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, GitRepo handbackRepo, TranslationState translationInfo, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandbackCore.cs:line 356","extended_information":null}


Generated by OpenLocalization.
