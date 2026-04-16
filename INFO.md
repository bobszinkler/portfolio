# Portfolio (INFO)

o-section : teljes, szelesseg, hatter, padding, margin
o-container : max-width, közepre igazitas
o-row : elemek (vizszintes)
o-stack : elemek (függöleges)
o-inline : vizszintes, töressel

h1, h2, h3 stb. : __title
__subtitle, __text, __label, __description


## Commit Style

```MD
 feat_    - hozzáadott funckió
 style_   - stílus módosítás
 fix_     - javított hiba
 refact_  - kényelmi vagy teljesítményi módosítás
 chore_   - file-ok hozzáadása, törlése
 doc_     - dokumentáció írása

 ds_        - design-system fejelsztés
 template_  - template fejlesztés

 _add     -   új dolog
 _update  -   viselkedés / módosítás
 _rename  -   átnevezés
 _move    -   átrakás másik helyre
 _cleanup -   takarítás, fölös kódok
 _config  -   beállításokhoz
 _docs    -   dokumentációhoz

 `feat_atoms-import-to-template_add`
```

## Semantic Versioning

> v1.0.0 = MAJOR.MINOR.PATCH

### MAJOR (1.0.0)

#### Törő változás. Olyan módosítás, ami megtöri a régi kódot

- class neveket átírod (.btn-primary → .button--primary)
- törölsz tokeneket / mixineket
- teljesen másra szervezed a layout API-t

### MINOR (1.1.0)

#### Új cuccok, de nem törik el a régit

- új atom (pl. .chip, .tag)
- új utility osztály
- új theme / új spacing token, de a régiek maradnak

### PATCH (1.0.1)

#### Apró javítás, bugfix, vizuális finomhang

- padding kicsit jobb
- szebbre állítod a line-height-et
- fixálsz egy hibás breakpointot → API nem változik, csak „jobb lett”.
