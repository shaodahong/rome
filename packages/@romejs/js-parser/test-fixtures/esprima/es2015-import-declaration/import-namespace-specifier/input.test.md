# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-import-declaration > import-namespace-specifier`

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
      column: 0
      index: 28
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ImportDeclaration {
      defaultSpecifier: undefined
      importKind: undefined
      namedSpecifiers: Array []
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 27
          index: 27
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      source: StringLiteral {
        value: 'foo'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 26
            index: 26
            line: 1
          }
          start: Object {
            column: 21
            index: 21
            line: 1
          }
        }
      }
      namespaceSpecifier: ImportNamespaceSpecifier {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 15
            index: 15
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        local: ImportSpecifierLocal {
          name: BindingIdentifier {
            name: 'foo'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 15
                index: 15
                line: 1
              }
              start: Object {
                column: 12
                index: 12
                line: 1
              }
            }
          }
          importKind: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 15
              index: 15
              line: 1
            }
            start: Object {
              column: 12
              index: 12
              line: 1
            }
          }
        }
      }
    }
  ]
}
```