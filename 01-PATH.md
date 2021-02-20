### /foo/bar/index.html
### /foo/index.html
### /index.html

↓

### /foo/bar/
### /foo/index.html
### /index.html


^(.*/)/*$
↓
\1

delete
(?!/*/).

