# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 90`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 31
      index: 31
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExportExternalDeclaration {
      defaultSpecifier: undefined
      exportKind: undefined
      namespaceSpecifier: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 31
          index: 31
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      source: StringLiteral {
        value: 'other'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 31
            index: 31
            line: 1
          }
          start: Object {
            column: 24
            index: 24
            line: 1
          }
        }
      }
      namedSpecifiers: Array [
        ExportExternalSpecifier {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 16
              index: 16
              line: 1
            }
            start: Object {
              column: 9
              index: 9
              line: 1
            }
          }
          exported: Identifier {
            name: 'default'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 16
                index: 16
                line: 1
              }
              start: Object {
                column: 9
                index: 9
                line: 1
              }
            }
          }
          local: Identifier {
            name: 'default'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 16
                index: 16
                line: 1
              }
              start: Object {
                column: 9
                index: 9
                line: 1
              }
            }
          }
        }
      ]
    }
  ]
}
```