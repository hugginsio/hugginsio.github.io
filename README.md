# [huggins.dev](https://huggins.dev)

Source for my GitHub Pages site.

The root page will redirect to my GitHub profile, whereas project pages are accessible as usual
(`huggins.dev/homelab`, `huggins.dev/whirligig`, etc). However, if a project page does not exist,
the logic in `404.html` will attempt to redirect to the repository of the same name (e.g.
`huggins.dev/kv2` -> `github.com/hugginsio/kv2`).
