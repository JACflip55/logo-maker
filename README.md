# Logo Maker
Easy to make your two word box logo

轻松制作你的 PornHub 以及 YouTube 风格的 Logo

在线制作：https://logomaker.akkariin.com/

## Licence

This project is open sourced using the GPL v3 license.

此项目使用 GPL v3 许可协议开放源代码。

## Fork addition: name ideas

`index.html` has a "Need a name?" panel. Describe a business, press **Suggest names**, and it asks
Claude (`claude-opus-5-5`) for eight two-word names; click one to load it into the logo.

The page stays static: the request goes straight from the browser to `api.anthropic.com` using an
Anthropic API key that the visitor pastes in. The key is kept in that browser's local storage and
is not sent anywhere else. Because the key is visible to anything running in the page, use one you
can revoke, and do not hard-code a key into the page.
