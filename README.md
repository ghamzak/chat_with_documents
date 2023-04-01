# chat_with_documents
Using ChatGPT to search a document.

For document reading, you can use pdftotext if it's a pdf, or whatever package you normally use to read a text document. Note that this code is only text-based only and does not perform image search. In other words, it is not multimodal. 

Note also that the current text chunking algorithm is simply based on token count. You can of course change the chunking function based on your use case. 
