# How to make a google docs embedded

1. Create a new docs from [here](https://docs.new/).
1. Publish the content from the tab `File > Share > Publish to Web`.
1. Share the content.
1. Copy the URL for the google docs, go to your HTML file and put it in the `src` of iframe, also put `embedded=true` at the end of the URL.

```html
<iframe
  title="DOCS TITLE"
  height="50%"
  width="100%"
  src="https://docs.google.com/document/d/1CniJ6Xf0S7tBHau3Nim15a4zQUr0TLUqM-ksAXj2s_0/edit?embedded=true"
></iframe>
```
