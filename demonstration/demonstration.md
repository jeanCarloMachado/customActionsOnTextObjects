```vim
"Put mappings like these in your .vimrc
"translate German to English
call toop#mapShell('trans -b  -no-theme -no-auto -no-ansi de:en', '<leader>ge')
"translate English to German
call toop#mapShell('trans -b  -no-theme -no-auto -no-ansi en:de', '<leader>eg')
```
## Use cases:

- translate inside word (`<leader>geiw`)
- repeat translate inside word (`.`)
- translate around sentence (`<leader>geas`)
- translate inside paragraph (`<leader>geip`)
- repeat translate inside paragraph (`.`)
- translate to German the selection (`<leader>eg`)
- translate to German the current line (`<leader>egg`)

```
Das Veilchen

Ein Veilchen auf der Wiese stand,
gebückt in sich und unbekannt;
es war ein herzigs Veilchen.
Da kam ein' junge Schäferin
mit leichtem Schritt und munterm Sinn, daher,
die Wiese her und sang.

Ach. denkt das Veilchen, wär' ich nur
die schönste Blume der Natur,
ach, nur ein kleines Weilchen,
bis mich das Liebchen abgepflückt
und an dem Busen matt gedrückt,
ach, nur, ach nur
ein Viertelstündchen lang

Ach, aber ach. Das Mädchen kam
und nicht in acht das Veilchen nahm,
ertrat das arme Veilchen.
Es sank und starb, und freut' sich noch:
und sterb' ich denn, so sterb' ich doch
durch sie, durch sie,
zu ihren Füßen doch!

```


