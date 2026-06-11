
After cloning, install papermod theme:

```
git submodule update --init --recursive
```

hugo from apt repo wont work, install latest version from [official github repo](https://github.com/gohugoio/hugo/releases)

after install, to create a new post
```
hugo new posts/your_post.md
```

To serve even the draft files locally:
```
hugo serve -D
```

To build:

```
hugo
```


