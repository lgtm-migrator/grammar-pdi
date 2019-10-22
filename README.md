# Grammar of PDI

Provide the AST parser for BODL (Business Object Definition Language) and ABSL (ABAP Script Language)

## [BODL Parser](./bodl)

![](https://res.cloudinary.com/digf90pwi/image/upload/v1571731756/2019-10-22_16-08-35_rsokqx.png)

### Build

go to `./bodl/.antlr` and run (need vscode plugin)

```bash
antlr -Dlanguage=Go -package bodl ../BODLLexer.g4 
antlr -Dlanguage=Go -package bodl ../BODLParser.g4 
```

sometimes we need manually edit generated lexer/parser code.