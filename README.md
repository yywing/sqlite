# GORM Sqlite Driver

![CI](https://github.com/yywing/sqlite/workflows/CI/badge.svg)

## Detail

use **pure go** sqlite driver [https://gitlab.com/cznic/sqlite](https://gitlab.com/cznic/sqlite)

**notice**: Although you could see mattn's driver (github.com/mattn/go-sqlite3) in go.mod file, we import it for tests only.

## USAGE

```go
import (
  "github.com/yywing/sqlite"
  "gorm.io/gorm"
)

db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```

## BUILD

https://modern-c.appspot.com/-/builder/?importpath=modernc.org%2fsqlite
