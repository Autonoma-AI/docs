# Input Text

## Description

Input the text returned in metadata on an input field. You can only perform one action, so don't pass two tasks separated by comma or something similar.

## Metadata

RETURN ONLY WHAT NEEDS TO BE INPUTTED ON METADATA. DON'T RETURN THE INSTRUCTION. THIS INFORMATION WILL BE USED FOR TYPING AS IS ON THE APP INPUT BOX.
Example 1: 'for the input input the email tom@autonoma.app on the email input', the metadata will be 'tom@autonoma.app'
Example 2: 'input the password 123456 on the password input', the metadata will be '123456'
Example 3: 'input the email from memory on the email input', a memory function call will retrieve the memory email and will be returned as is on the metadata. let's say the email was 'nico@autonoma.app', then the metadata will be 'nico@autonoma.app'

## Supported Engines

- Web
- Mobile

## Example Prompts

- input the email tom@autonoma.app on the email input
- input the password 123456 on the password input
- input the email from memory on the email input