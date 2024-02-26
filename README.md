https://app.gitter.im/#/room/#Bg_Rehberi:gitter.im
https://cbddo.gov.tr/SharedFolderServer/Genel/File/bg_rehber.pdf

# Ulusal Bilgi Güvenliği Rehberi
Bilgi güvenliğinin sağlanması için belirlenen asgari güvenlik tedbirlerinin  ve hazırda bulunan güvenlik rehberinin geliştirilmesi 

Word Processing API for .NET
Aspose.Words for .NET is a powerful on-premise class library that can be used for numerous document processing tasks. It enables developers to enhance their own applications with features such as generating, modifying, converting, rendering, and printing documents, without relying on third-party applications, for example, Microsoft Word, or Office Automation.



This repository contains Demos, Examples, Plugins and Showcases for Aspose.Words for .NET to help you learn and write your own applications.

Directory	Description
Examples	A collection of .NET examples that help you learn and explore the API features
Showcases	Standalone ready-to-use applications that demonstrate some specific use cases
Plugins	Plugins that will demonstrate one or more features of Aspose.Words for .NET
.NET API for Various Document Formats
Aspose.Words for .NET is a powerful on-premise class library that can be used for numerous document processing tasks. It enables developers to enhance their own applications with features such as generating, modifying, converting, rendering, and printing documents, without relying on third-party applications, for example, Microsoft Word, or automation.

Word API Features
Aspose.Words can be used to develop applications for a vast range of operating systems such as Windows or Linux & Mac OS and platforms such as Windows Azure, Xamarin.Android, or Xamarin.iOS&Xamarin.Mac.
Comprehensive document import and export with 35+ supported file formats. This allows users to convert documents from one popular format to another, for example, from DOCX into PDF or Markdown, or from PDF into various Word formats.
Programmatic access to the formatting properties of all document elements. For example, using Aspose.Words users can split a document into parts or compare two documents.
High fidelity rendering of document pages. For example, if it is needed to render a document as in Microsoft Word, Aspose.Words will successfully cope with this task.
Ability to print a document programmatically using Aspose.Words and the XpsPrint API or via dialog boxes.
Generate reports with Mail Merge, which allows filling in merge templates with data from various sources to create merged documents.
LINQ Reporting Engine to fetch data from databases, XML, JSON, OData, external documents, and much more.
Read & Write Document Formats
Microsoft Word: DOC, DOCX, RTF, DOT, DOTX, DOTM, DOCM FlatOPC, FlatOpcMacroEnabled, FlatOpcTemplate, FlatOpcTemplateMacroEnabled
OpenOffice: ODT, OTT
WordprocessingML: WordML
Web: HTML, MHTML
Fixed Layout: PDF
Text: TXT

Save Word Files As
Fixed Layout: XPS, OpenXPS, PostScript (PS)
Images: TIFF, JPEG, PNG, BMP, SVG, EMF, GIF
Web: HtmlFixed
Others: PCL, EPUB, XamlFixed, XamlFlow, XamlFlowPack

Platform Independence
Aspose.Words for .NET API can be used to develop applications for a vast range of operating systems (Windows, Linux & Mac OS) and platforms. You can build both 32-bit and 64-bit applications including ASP.NET, WCF & WinForms. Aspose.Words for .NET can also be used via COM Interop from ASP, PHP, Perl and Python.

You can also build applications with Mono as well as on Windows Azure, Microsoft SharePoint, Microsoft Silverlight, Xamarin.Android, Xamarin.iOS & Xamarin.Mac.

Getting Started with Aspose.Words for .NET
Ready to give Aspose.Words for .NET a try? Simply run Install-Package Aspose.Words from Package Manager Console in Visual Studio to fetch the NuGet package. If you already have Aspose.Words for .NET and want to upgrade the version, please run Update-Package Aspose.Words to get the latest version.

Using C# to Create a DOC File from Scratch
You can execute this snippet in your environment to see how Aspose.Words performs or check the GitHub Repository for other common usage scenarios.

// create a blank document
Document doc = new Document();
// the DocumentBuilder class provides members to easily add content to a document
DocumentBuilder builder = new DocumentBuilder(doc);
// write a new paragraph in the document with the text "Hello World!"
builder.Writeln("Hello World!");
// save the document in DOCX format. 
// the format to save as is inferred from the extension of the file name.
doc.Save(dir + "output.docx");
Using C# to Export DOC to EPUB Format
Aspose.Words for .NET allows you to convert Microsoft Word® formats into bytes, HTML, EPUB, MHTML and other file formats. Following snippet demonstrates the conversion of a DOC file to an EPUB file:

// load the document from disc
Document doc = new Document(dir + "template.doc");
// save the document in EPUB format
doc.Save(dir + "output.epub");
Using C# to Import PDF and Save as a DOCX File
The following code sample demonstrates, how you can import a PDF document into your .NET application and export it as a DOCX format file without the need to install the Microsoft Word®:

// Load the PDF document from directory
Document doc = new Document(dir + "input.pdf");

// Save the document in DOCX format
doc.Save(dir + "output.docx");
Product Page | Docs | Demos | API Reference | Examples | Blog | Search | Free Support | Temporary License
