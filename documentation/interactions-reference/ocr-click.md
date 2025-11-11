# OCR Click

## Description

If click is not working (maybe because element can't be found with the XML) use ocr-click which will use OCR and will probably work. UNDERSTAND THAT ocr-click WORKS ONLY FOR VISIBLE ELEMENTS ON THE CURRENT VIEW. IF YOU CAN'T SEE THE ELEMENT, YOU CAN'T USE IT. Like if you see a sequence of clicks that changed nothing in the UI, or you see repeated instructions, that might mean that the click is not performing the required action. And you need to use ocr-click. Also, if the element doesn't have the clickable="true" it's probably a good sign that you should be using ocr-click.

## Metadata

Return what needs to be clicked on metadata.

## Supported Engines

- Web
- Mobile

## Example Prompts

- ocr-click on the login button
- ocr click on the sign up button
- ocr click on 241