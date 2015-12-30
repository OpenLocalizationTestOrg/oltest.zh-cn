# <a name='report-top'></a> Localization Handoff Report

## Summary
 Total Files | 2

## File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [e2e\166d0865-89d6-48b5-8b20-17001340fff1.md](https://github.com/OpenLocalizationTest/oltest/blob/e96a5b4ddfac1d64b65b1e6f6fcd9d3eb83fa8a5/e2e/166d0865-89d6-48b5-8b20-17001340fff1.md) | HandedOffFailed | [Details](#82714d943ce4e9476e1cbb49309a3f99317b268e1)
 [e2e\ea47f8a5-68ee-4d90-adfd-4a20fea50ec0.md](https://github.com/OpenLocalizationTest/oltest/blob/040ad5e836c023d720156be65ce049ecc5140d34/e2e/ea47f8a5-68ee-4d90-adfd-4a20fea50ec0.md) | HandedOffFailed | [Details](#05e0c073487efdcb534c1b8134d5a43420d195885)

## Item Details
##### <a name='82714d943ce4e9476e1cbb49309a3f99317b268e1'></a> Source: [e2e\166d0865-89d6-48b5-8b20-17001340fff1.md](https://github.com/OpenLocalizationTest/oltest/blob/e96a5b4ddfac1d64b65b1e6f6fcd9d3eb83fa8a5/e2e/166d0865-89d6-48b5-8b20-17001340fff1.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#82714d943ce4e9476e1cbb49309a3f99317b268e1handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='05e0c073487efdcb534c1b8134d5a43420d195885'></a> Source: [e2e\ea47f8a5-68ee-4d90-adfd-4a20fea50ec0.md](https://github.com/OpenLocalizationTest/oltest/blob/040ad5e836c023d720156be65ce049ecc5140d34/e2e/ea47f8a5-68ee-4d90-adfd-4a20fea50ec0.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#05e0c073487efdcb534c1b8134d5a43420d195885handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)


## Error Details
##### <a name='82714d943ce4e9476e1cbb49309a3f99317b268e1handoff_transform_failed'></a> Source: [e2e\166d0865-89d6-48b5-8b20-17001340fff1.md](#82714d943ce4e9476e1cbb49309a3f99317b268e1)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\166d0865-89d6-48b5-8b20-17001340fff1.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\166d0865-89d6-48b5-8b20-17001340fff1.md transformed failed.","internal_error_retriable":false,"exception_message":"Invalid Xml when parsing: <p>hello <br> world</p>.","exception_type":"System.ArgumentException","stack_trace":"   at Microsoft.Content.Build.Components.MarkdownHtmlBlock..ctor(String value)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.<ParseHtmlQuote>b__c(Match match, List`1 itemList)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.ParseBlockItemCommon(List`1 inputItems, Regex regex, Action`2 action)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.ParseHtmlQuote(List`1 inputItems)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadInternal(String fileContent)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadFromContent(String fileContent)\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownTransformer.MarkdownToXliffCore(Stream markdownStream, Stream xliffStream, Stream sklStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion) in D:\\Workspace\\OpenLocalization\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationConfig config, Dictionary`2 filePathInfo) in D:\\Workspace\\OpenLocalization\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 261","extended_information":null}

##### <a name='05e0c073487efdcb534c1b8134d5a43420d195885handoff_transform_failed'></a> Source: [e2e\ea47f8a5-68ee-4d90-adfd-4a20fea50ec0.md](#05e0c073487efdcb534c1b8134d5a43420d195885)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\ea47f8a5-68ee-4d90-adfd-4a20fea50ec0.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\ea47f8a5-68ee-4d90-adfd-4a20fea50ec0.md transformed failed.","internal_error_retriable":false,"exception_message":"Invalid Xml when parsing: <p>hello <br> world</p>.","exception_type":"System.ArgumentException","stack_trace":"   at Microsoft.Content.Build.Components.MarkdownHtmlBlock..ctor(String value)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.<ParseHtmlQuote>b__c(Match match, List`1 itemList)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.ParseBlockItemCommon(List`1 inputItems, Regex regex, Action`2 action)\r\n   at Microsoft.Content.Build.Components.MarkdownBlockParser.ParseHtmlQuote(List`1 inputItems)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadInternal(String fileContent)\r\n   at Microsoft.Content.Build.Components.MarkdownFile.LoadFromContent(String fileContent)\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownTransformer.MarkdownToXliffCore(Stream markdownStream, Stream xliffStream, Stream sklStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion) in D:\\Workspace\\OpenLocalization\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 26\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationConfig config, Dictionary`2 filePathInfo) in D:\\Workspace\\OpenLocalization\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 261","extended_information":null}


Generated by OpenLocalization.
