# hexo-asset-image


Give asset image in hexo a absolutely path automatically

# Usege

```shell
npm install hexo-asset-image --save
```

# Example  

```shell
#add a new article
hexo new example 
```

```shell
/source/_posts/
example
├── apppicker.jpg
├── logo.jpg
└── rules.jpg
example.md
```

Make sure `post_asset_folder: true` in your `_config.yml`.

Just use `![logo](example/logo.jpg)` to insert `logo.jpg`.
