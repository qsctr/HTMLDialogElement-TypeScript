# htmldialogelement-typescript

TypeScript type definition for HTMLDialogElement

spec: https://html.spec.whatwg.org/multipage/forms.html#the-dialog-element

MDN: https://developer.mozilla.org/en-US/docs/Web/API/HTMLDialogElement

## Installation

    typings install github:qsctr/htmldialogelement-typescript#[latest commit] --global --save

## Usage

tsconfig.json

    {
        "files": [
            "typings/index.d.ts"
        ]
    }
    
or

    /// <reference path="path/to/typings/index.d.ts" />
    
then

    let dialog = document.querySelector('dialog') as HTMLDialogElement;
    dialog.show();
    // etc
