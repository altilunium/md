# rtnF md
Yet another notetaking app. Markdown formatting, autosave feature, stored locally inside your own browser, p2p note sharing.

## How to use

1. Visit [altilunium.github.io/md](https://altilunium.github.io/md)
2. Click the dark green button to start editing.
3. Write your post by using [markdown syntax](https://daringfireball.net/projects/markdown/syntax.text).
4. Click the dark green button once more to preview the post.
5. You can also make a local draft post, saved offline on your browser indexedDB. Just click the yellow button to access the local filesystem, and click the green "m" icon to create a new file.

## Advanced usage

* You can paste image directly to this text editor.
* You can also paste the original formatting. Press ctrl+shift+v to paste without formatting.
* To print the document, switch to markdown-rendered mode by clicking the green "m" icon, then add the URL `?r=y` to hide the toolbar, then print it by using browser's built-in print function (ctrl+p)
* ~~Click the light green button to publish. Enter the URL key and password. Store your password somewhere if you want to edit this published post later.~~ (Deprecated feature : replaced with [p2p note sharing feature](https://rtnf.bearblog.dev/experimenting-with-peerjs/))


## Tech Stack
1. Markdown Parser & Compiler : [MarkedJS](https://marked.js.org/)
2. Syntax Highlighter : [HighlightJS](https://highlightjs.org/)
3. Text Editor : [rtnF](https://github.com/altilunium/rtnf)
4. P2P : [PeerJS](https://peerjs.com)


