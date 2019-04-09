## Welcome to website of the SPQL programming language

### Getting start

```js
tokenizer("<input>")
```

```js
console.log( tokenizer("{}") );
```

# Tokens

- `{` : lb
- `}` : rb
- `(` : ls
- `)` : rs
- `[` : la
- `]` : ra
- `\s` : skip
- `;` : end
- `.` : fs
- `,` : rz
- `number([0-9]+)` : num
- `"<string>"` : str
- `'<string>'` : sts
- /<regex>/ : rgx
- `#<any>` : skip, single line comment
- letters (`[A-Za-z0-9\_\$]+`) : nm
- keyword (if else for while do func switch class break continue case default return try catch) : key
- operator (+ - * / \= % & | ! ? : < > ~ @ ^ `) : pnc

----------

For more details see [SPQL repository](https://github.com/spql-lang/spql).
