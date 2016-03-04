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
 [e2e\test-content-1.md](https://github.com/OpenLocalizationTest/oltest/blob/e3475a77498ac0546ea41f7931055032613cb3cd/e2e/test-content-1.md) | HandedOffFailed | [Details](#ac5610e14e35343352c9459b3e335b10c5a316371)

## <a name='handoff-success-list'></a> Handoff Success File List

## <a name='archive-failed-list'></a> Archive Failed File List

## <a name='archive-success-list'></a> Archive Success File List

## <a name='handback-failed-list'></a> Handback Failed File List

## <a name='outofsync-handback-success-list'></a> Out Of Sync Handback Success File List

## <a name='insync-handback-success-list'></a> In Sync Handback File Success List

## <a name='ignored-list'></a> Ignored File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/b54b1cab13d1ba4f6c1ac371a97c1b9011846b27/.localization-config) | Ignored | [Details](#66aca4b1c2f43b14ec41e0e427345df94af1d5e10)

## Item Details
##### <a name='66aca4b1c2f43b14ec41e0e427345df94af1d5e10'></a> Source: [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/b54b1cab13d1ba4f6c1ac371a97c1b9011846b27/.localization-config)
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

##### <a name='ac5610e14e35343352c9459b3e335b10c5a316371'></a> Source: [e2e\test-content-1.md](https://github.com/OpenLocalizationTest/oltest/blob/e3475a77498ac0546ea41f7931055032613cb3cd/e2e/test-content-1.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#ac5610e14e35343352c9459b3e335b10c5a316371handoff_transform_failed)
* Archive File: 
* Archive Datetime: 0001-01-01 00:00:00
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)


## Error Details
##### <a name='ac5610e14e35343352c9459b3e335b10c5a316371handoff_transform_failed'></a> Source: [e2e\test-content-1.md](#ac5610e14e35343352c9459b3e335b10c5a316371)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\test-content-1.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\test-content-1.md transformed failed.","internal_error_retriable":false,"exception_message":"Value cannot be null.\r\nParameter name: stream","exception_type":"System.ArgumentNullException","stack_trace":"   at System.IO.StreamReader..ctor(Stream stream, Encoding encoding, Boolean detectEncodingFromByteOrderMarks, Int32 bufferSize, Boolean leaveOpen)\r\n   at System.IO.StreamReader..ctor(Stream stream)\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.ReadScript()\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.Initialize()\r\n   at System.Lazy`1.CreateValue()\r\n   at System.Lazy`1.LazyInitValue()\r\n   at Microsoft.OpenLocalization.Transformer.MarkdownJavascriptTransformer.MarkdownToXliffCore(Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, Stream sourceStream, Stream xliffStream, Stream skeletonStream, String contentClass, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Transformer.XliffTransformerExtensions.MarkdownToXliff(IMarkdownTransformer markdownTransformer, String markdownFile, String xliffFile, String skeletonFile, String locale, String xliffVersion)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String targetLocale, String xliffVersion, Boolean useJavascriptTransformer) in D:\\Workspace\\OpenLocalization\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 27\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.<>c__DisplayClass9_0.<GetHandoffFiles>b__0(Tuple`3 handoff) in D:\\Workspace\\OpenLocalization\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 339","extended_information":null}


Generated by OpenLocalization.
