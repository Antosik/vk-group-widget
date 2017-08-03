## VKontakte community widget
built with [Web Components](https://www.webcomponents.org/)

### [Demo](https://antosik.github.io/vk-group-widget/index.html)
There are three widgets.  
First one only with `group-id`, second with additional attributes and last one without provided attributes (shows error).

### Usage
```html
<!-- Insert inside <head> tag -->
<link rel="import" href="group-widget.html">
 
<!-- Insert on your page -->
<group-widget group-id="GROUP_ID" [additional attributes]></group-widget>
```

### Attributes
* `group-id="NUMBER"` - Your group ID
* `view="participants"` - One of `news`, `name`, `participants`
* `wide="false"` - Wide mode for `news` view (`true`/`false`)
* `cover="true"` - Show community cover or not (`true`/`false`)
* `width="auto"` - Width of widget: `auto` or Number of pixels (`500`)
* `background="HEX_COLOR"` - Widget background color in hex (default: `FFFFFF`)
* `text="HEX_COLOR'` - Widget text color in hex (default: `000000`)
* `button="HEX_COLOR"` - Widget header and button color in hex (default: `5E81A8`)

### More
* [Widget playground (official)](https://vk.com/dev/Community)
* [Widget documentation (official)](https://vk.com/dev/widget_community)
