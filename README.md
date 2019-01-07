# Apps Website

## Development

### Hugo

```text
hugo server -D
hugo server --bind=192.168.0.200 --baseURL=http://192.168.0.200:1313
```

### Bootstrap & PostCSS

```text
npm install
npm install -g postcss-cli
npm install -g autoprefixer
```

## Hosting

+ Hugo builds to /public.
+ Git submodule linked to gh-pages branch.