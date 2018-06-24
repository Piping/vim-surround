# surround.vim <variation>

Surround.vim is all about "surroundings": parentheses, brackets, quotes,
XML tags, and more.  The plugin provides mappings to easily delete,
change and add such surroundings in pairs.

surround.vim apply vim's concept `text-object` to maniplaute text.

The plugin provides three useful operators through normal mode key-mapping (thus timeout applied).  
- `ds`
  - delete the suround. E.g. type `ds'` will delete the single quote surround current crusor.
- `cs`
  - change the surround. E.g. type `cs'"` will change the single quote surround current cursor.
- `ss`
  - surrond the following text-objetcs. E.g. `ssiw"` will add double quote around the word.

Common text-objects are `iw` inner word, `ip` inner paragraph, `i(` inner parenthese...etc.
For more information about `text-object` itself, check out `:help text-object` in vim. 

In the visual mode, press `S` to add surroundings.

## License

Copyright (c) Tim Pope.  Distributed under the same terms as Vim itself.
See `:help license`. (Contributor Robin)
