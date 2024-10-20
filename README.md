# Graphic Novel Builder

A tool to quickly view and edit a page or spread from a graphic novel. Made using Svelte and TailwindCSS.


## Usage
Head to https://david-saperstein.github.io/graphic-novel

By default, four panels will appear as a demo. Try moving and resizing the panels and speech bubbles. Take note of the snapping between panels and colored guidelines that appear at even divisions of the page.

If you want to edit a custom page, reference the following JSON corresponding to the demo layout.

```JSON
[
  {
    "dialogueBoxes": [
      {
        "text": "Example speech bubble",
        "type": "speech"
      },
      {
        "text": "Example caption",
        "type": "caption"
      }
    ]
  },
  {
    "dialogueBoxes": [
      {
        "text": "Example speech bubble",
        "type": "speech"
      },
      {
        "text": "Example caption",
        "type": "caption"
      }
    ]
  },
  {
    "dialogueBoxes": [
      {
        "text": "Example speech bubble",
        "type": "speech"
      },
      {
        "text": "Example caption",
        "type": "caption"
      }
    ]
  },
  {
    "dialogueBoxes": [
      {
        "text": "Example speech bubble",
        "type": "speech"
      },
      {
        "text": "Example caption",
        "type": "caption"
      }
    ]
  }
]
```

This JSON can be pasted into the input textarea on the website. Clicking the load button will parse the input and display the custom page.

Note: Valid HTML may be put in any "text" field to allow for bold, italics, etc.

You can download your designs using the 'save' button and continue to work on them by uploading the save file.

You can also use the screenshot button to render your current design as a PNG.

Lastly, use the 'Reference Page' drop-down to upload a view-only version of a previously saved design displayed side-by-side with your current work. This is especially useful for things like 2-page spreads.

## License

[MIT](https://choosealicense.com/licenses/mit/)
