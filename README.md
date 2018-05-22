# Documentation/reference

Find it at [godoc](https://godoc.org/github.com/sugoiuguu/go-irccol).

# Example usage

```go
// import col "github.com/sugoiuguu/go-irccol"
msg := col.F("Hello world!").Attr(col.Bold).Fg(col.Red).String()
irc.Send("#bots", msg)
```
