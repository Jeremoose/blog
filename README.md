# Blog

My blog made using go hugo and using the PaperMod theme.

## running

running with server to test

```bash
docker run --rm -it -v $(pwd):/src -p 1313:1313 klakegg/hugo:latest server
```

building to deploy

```bash
docker run --rm -it -v $(pwd):/src klakegg/hugo:0.92.1
```
