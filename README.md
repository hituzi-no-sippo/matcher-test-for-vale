# matcher-test-for-vale

- [GitHub Actions Result](https://github.com/hituzi-no-sippo/matcher-test-for-vale/actions/runs/3974529244)
- [Annotations](https://github.com/hituzi-no-sippo/matcher-test-for-vale/commit/09d205c2e6d2e48259950734eb18e70f86553be3#annotation_8155580982)

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
