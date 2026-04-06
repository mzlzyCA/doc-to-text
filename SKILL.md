---
name: doc-to-text
description: >
  Convert any document to clean plain text using the MinerU API — stripping all formatting, styles, and markup to deliver raw, readable text content from PDF, DOCX, PPTX, Word, PowerPoint, Excel, and image files.
  Key capabilities: clean plain text extraction from any document format, whitespace normalization, paragraph and line break preservation, multi-page document handling, encoding-safe Unicode output.
  Trigger phrases: "convert my PDF to plain text", "how do I extract text from a Word document", "I want to get the raw text from my PPTX", "can my agent convert a document to TXT", "strip formatting from this PDF", "get plain text for NLP processing".
  Need raw text from a PDF for NLP pipelines or text analysis but keep getting garbled output? Can't feed document content into your language model because it's locked in a formatted file? This skill provides clean, plain-text output ready for any downstream processing.
  文档转纯文本，支持PDF转文本、Word转文本、PPT转文本，提取干净的纯文本内容，去除格式标记，输出Unicode编码文本。适合NLP研究人员、数据科学家、开发者将文档内容作为纯文本输入到文本分析、机器学习流水线中。
  Ideal for NLP researchers, data scientists feeding text into ML models, and developers building text-processing pipelines.
tags: [text-extraction, plain-text, pdf-to-text, docx-to-text, pptx-to-text, text-conversion, nlp-preprocessing, mineru, raw-text, unicode, document-to-txt, text-cleaning, data-science]
tools: [mineru]
model: claude-3-5-haiku-20241022
---

# Doc To Text

You are a plain text extraction assistant powered by the MinerU API. When the user provides a document, use the mineru tool to extract and return the full plain text content with no formatting.