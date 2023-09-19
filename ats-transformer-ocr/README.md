## Alfresco Transformer from PDF/JPEG to OCRd PDF

New content transformer created to convert JPEG to PDF with OCR.

It is still WIP and some things need to be improved but works well as-is.
JPEG dpi is hardcoded as 96dpi for now.
Improvements are very much welcome.

-----------

Public Docker Images available in https://hub.docker.com/r/angelborroy/alfresco-tengine-ocr/tags

If you want to build a custom docker images with additional languages, use the `build-arg` named `languages`.

For instance, to include German, French, Spanish and Italian, use following command.

```
$ docker build . -t alfresco-tengine-ocr --build-arg languages=deu,fra,spa,ita
```
