# Loonpic Project

## Todo

## RUN

```console

export JEKYLL_VERSION=3.1.1
docker run --rm \
    --volume="$PWD:/srv/jekyll" \
    -it "jekyll/builder:$JEKYLL_VERSION" \
    jekyll build install

export JEKYLL_VERSION=3.1.1
docker run --rm \
    --volume="$PWD:/srv/jekyll" \
    -it "jekyll/builder:$JEKYLL_VERSION" \
    jekyll build

export JEKYLL_VERSION=3.1.1
docker run -it --rm \
    --volume="$PWD:/srv/jekyll" \
    -p 4000:4000 jekyll/jekyll \
    jekyll serve

```

## Source

[Template](https://wowthemesnet.github.io/template-pintereso-bootstrap-jekyll/index.html)
[GitHub](https://github.com/wowthemesnet/template-pintereso-bootstrap-jekyll)
