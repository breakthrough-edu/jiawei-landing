# jiawei-landing

Static personal landing page for Jia Wei (brand strategist x AI) -- "Signal in the Dark" design.

Hosted on **GitHub Pages**, embedded into the GoHighLevel page at `kalozedu.com/breakthrough-lab`
as a full-width auto-resizing `<iframe>`. The GHL page is just a shell; all content lives here.

## Files
- `index.html` -- the page (mesh-dark + FF6600 signal, mobile-first single column)
- `jiawei-photo.jpg` -- hero photo

## Update loop
Edit `index.html`, commit, push to `main`. GitHub Pages redeploys automatically (~30-60s).
The GHL iframe reflects the change with no edits in GHL.

The page posts its height to the parent (`postMessage`) so the GHL iframe stays scrollbar-free.

Live: https://breakthrough-edu.github.io/jiawei-landing/
