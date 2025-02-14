# Shopify Section Schema Snippets

VSCode / Cursor snippets for Shopify Section schema input types.

[Shopify Docs](https://shopify.dev/docs/storefronts/themes/architecture/settings/input-settings)

## Installation

1. Copy contents of `liquid.json` into your clipboard.
2. In VSCode or Cursor, open the command palette (cmd + shift + p) and type 'Snippets' then select 'Configure Snippets'
3. Select the 'liquid.json' file in the list.
4. Paste the contents of your clipboard into the file.
5. Save the file.

You should now be able to use these inside `.liquid` files.

EG. type `sstext` and hit `TAB`, it will expand to:

```liquid
{
  "type": "text",
  "id": "text_input",
  "label": "Text input",
  "default": "A basic text input's content"
}
```

## Demo

![Demo](./demo.gif)

All snippets are prefixed with `ss` (section settings)and then the type of input.

### Full list of snippets:

| Input setting    | shortcode     | aliases                |
| ---------------- | ------------- | ---------------------- |
| checkbox         | ssc           | sscheckbox, sscheck    |
| number           | ssn           | ssnumber               |
| radio            | ssr           | ssradio                |
| range            | ssrs          | ssrange                |
| select           | sss           | ssselect               |
| text             | sst           | sstext                 |
| textarea         | ssta          | sstextarea             |
| article          | ssart         | ssarticle              |
| blog             | ssblog        | -                      |
| collection       | sscols        | sscollection           |
| collection_list  | sscollist     | sscollectionlist       |
| color            | sscol         | sscolor                |
| color_background | sscolbg       | sscolbackground        |
| color_scheme     | sscolorscheme | -                      |
| font_picker      | ssf           | ssfont                 |
| html             | sshtml        | -                      |
| image_picker     | ssimg         | ssimagepicker, ssimage |
| inline_richtext  | ssinl         | ssinline               |
| link_list        | ssnav         | sslinklist, ssmenu     |
| liquid           | ssliq         | ssliquid               |
| metaobject       | ssmetaobj     | ssmetaobject           |
| metaobject_list  | ssmetaobjlist | ssmetaobjectlist       |
| page             | sspg          | sspage                 |
| product          | ssprod        | ssproduct              |
| product_list     | ssprodlist    | ssproductlist          |
| richtext         | ssrich        | ssrichtext, ssrte      |
| text_alignment   | sstextalign   | sstextalignment        |
| url              | sslink        | ssurl                  |
| video            | ssvid         | ssvideo                |
| video_url        | ssvid         | ssvideourl, ssvideo    |
