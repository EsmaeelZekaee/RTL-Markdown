---
gfm: false
mangle: false
---

Here are some valid autolinks:

### Example 565

<https://foo.bar.baz>

### Example 566

<https://foo.bar.baz/test?q=hello&id=22&boolean>

### Example 567

<irc://foo.bar:2233/baz>

### Example 568

Uppercase is also fine:

<MAILTO:FOO@BAR.BAZ>

Note that many strings that count as absolute URIs for purposes of this spec are not valid URIs, because their schemes are not registered or because of other problems with their syntax:

### Example 569

<a+b+c:d>

### Example 570

<made-up-scheme://foo,bar>

### Example 571

<https://../>

### Example 572

<localhost:5001/foo>

### Example 573

Spaces are not allowed in autolinks:

<https://foo.bar/baz bim>

### Example 574

Backslash-escapes do not work inside autolinks:

<https://example.com/\[\>

Examples of email autolinks:

### Example 575

<foo@bar.example.com>

### Example 576

<foo+special@Bar.baz-bar0.com>

### Example 577

Backslash-escapes do not work inside email autolinks:

<foo\+@bar.example.com>

These are not autolinks:

### Example 578

<>

### Example 579

< https://foo.bar >

### Example 580

<m:abc>

### Example 581

<foo.bar.baz>

### Example 582

https://example.com

### Example 583

foo@bar.example.com