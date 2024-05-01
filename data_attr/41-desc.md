# `data-*` Attribute

## Definition:
The data-* attribute is used to store custom data private to the page or application.

The data-* attribute gives us the ability to embed custom data attributes on all HTML elements.

The stored (custom) data can then be used in the page's JavaScript to create a more engaging user experience (without any Ajax calls or server-side database queries).

The data-* attribute consist of two parts:

The attribute name should not contain any uppercase letters, and must be at least one character long after the prefix "data-"
The attribute value can be any string
Note: Custom attributes prefixed with "data-" will be completely ignored by the user agent.

### Simple syntax:
```
<div class="character" data-hp="100"></div>
```
### My summary:
An attribute, that at a first glance looks like it might be used the same way an id might but it's more about there being some possibly dynamic data/property that is associated with it. It's positive is probably that it can be interacted with in css like character[data-hp='50']{ stuff } or in js as character.dataset.hp = 20. 

Question:
As for usages, im a little worried that because it's all client side, if this was like a little html game of sorts, can't they just cheat their way through? To prevent this, would we do like some backend validation?

On a related note, can this "dynamically" be changed if we are turn off javascript? 

[Link to the simple demo](/time_tag/32-simple-demo.html)

### Sources:
[w3 school documetation](https://www.w3schools.com/tags/tag_time.asp)

[mdn documentation](https://developer.mozilla.org/en-US/docs/Learn/HTML/Howto/Use_data_attributes)

