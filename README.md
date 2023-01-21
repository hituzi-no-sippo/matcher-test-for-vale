# matcher-test-for-vale

## Test text

We need Ascidoctor to lint AsciiDoc files.

```console
$ vale --no-wrap README.md

 README.md
 1:3  suggestion  'matcher-test-for-vale' should use sentence-style capitalization.  Microsoft.Headings
 5:1  warning     Try to avoid using first-person plural like 'We'.                  Microsoft.We
 5:9  error       Did you really mean 'Ascidoctor'?                                  Vale.Spelling

✖ 1 error, 1 warning and 1 suggestion in 1 file.
```
