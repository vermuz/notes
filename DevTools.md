# DevTools

_ http://www.cnblogs.com/Wayou/p/chrome-console-tips-and-tricks.html

## Hotkey
Remember **all** chrome related hotkeys are trigger with `Option+CMD` or `ALT+CMD`:
- `ALT+CMD+arrow`: go to left or right tab
- `ALT+CMD+0`: go to first tab
- `ALT+CMD+9`: go to last tab
- `ALT+CMD+C`: inspect element
- `ALT+CMD+i`: open dev tools

## API
[Command Line API Reference for Chrome](https://developers.google.com/web/tools/chrome-devtools/debug/command-line/command-line-reference?hl=en)

- `$(selector)` 
    - returns the first element, is alias of `docuemnt.querySelector()`
- `$$(selector)` 
    - returns `NodeList`, is alias of `docuemnt.querySelectorAll()`
    - `NodeList` is not array, to convert to array: `Array.prototype.slice.call(div_list)` or `[...div_list]`
    

Debug Help
- `dir(object)`
- `keys(object)`
- `monitor(function)` outputs when this function is called and what arguments; `unmonitor`
- `monitorEvents(window, "resize")`
- `table(data)`
```js
var names = {
	0: { firstName: "John", lastName: "Smith" },
	1: { firstName: "Jane", lastName: "Doe" }
};
table(names);
```

---

## Chrome Extensions
- https://chrome.google.com/webstore/detail/builtwith-technology-prof/dapjbgnjinbpoindlpdmhochffioedbn
- https://chrome.google.com/webstore/detail/merge-windows/adjadgadeebehakpgamlnafmdkegkmph
- https://chrome.google.com/webstore/detail/web-developer-checklist/iahamcpedabephpcgkeikbclmaljebjp
- http://chrispederick.com/work/web-developer/
- http://chengyinliu.com/whatfont.html
- https://chrome.google.com/webstore/detail/emmet-review/epejoicbhllgiimigokgjdoijnpaphdp
- https://chrome.google.com/webstore/detail/onetab/chphlpgkkbolifaimnlloiipkdnihall
- postman: https://chrome.google.com/webstore/detail/postman-interceptor/aicmkgpgakddgnaphhhpliifpcfhicfo
- https://chrome.google.com/webstore/detail/dimensions/baocaagndhipibgklemoalmkljaimfdj
- feedly, evernote
