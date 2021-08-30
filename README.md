# browser

Helpers to open URLs, readers, or files in the system default web browser.

This fork adds:

- `OpenReader` error wrapping;
- `ErrNotFound` error wrapping on BSD;

## Usage

```go
import "github.com/scmn-dev/browser"

err = browser.OpenURL(url)
err = browser.OpenFile(path)
err = browser.OpenReader(reader)
```
