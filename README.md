# BERT_Key_Value_Extraction
A tool that extracts a set of key value pairs from receipts.
In this repository I create a tool that extracts key value pairs from scanned images of receipts. Values extracted include company name, receipt date and total of receipt. I use pytesseract for OCR and BERTForTokenClassification to label sequences of tokens extracted from receipts as company name, date or total. Results of a basic model are very promissing with 77% macro-average F1 score. Further details on used libraries and implementation are found in the notebook.
