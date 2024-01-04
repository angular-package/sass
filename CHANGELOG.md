# @angular-package/sass changelog

### v0.19.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.19.0-beta)

- **Update** [`variant.property-set()`](https://github.com/angular-package/sass/blob/develop/variant/property/_property.set.function.scss) function to handle multiple properties. [8081d34]
- **Update** [`variant.transform()`](https://github.com/angular-package/sass/blob/develop/variant/_variant.transform.mixin.scss) to handle multiple properties. [305e6c1]
- **Update** [`schema.has-multiple-colors()`](https://github.com/angular-package/sass/blob/develop/color/palette/schema/_schema.has-multiple-colors.function.scss) function - add `$result` argument to return `bool` or `index` of found indicator. [eca4b74]
- **Add** [`color.name-indicator-remove()`](https://github.com/angular-package/sass/blob/develop/color/name/indicator/_indicator.remove.function.scss) function to remove indicator or multiple indicators from color name..[ce0cdc4]
- **Add** [`color.name-indicator-retrieve()`](https://github.com/angular-package/sass/blob/develop/color/name/indicator/_indicator.retrieve.function.scss) function to retrieve indicator or multiple indicators from color name. [b5679c6]
- **Update** [`color.palette-create()`](https://github.com/angular-package/sass/blob/develop/color/palette/_palette.create.function.scss) function - remove property indicator `':'` and assign property to color. [d853f93]
- **Update** [`variant.create()`](https://github.com/angular-package/sass/blob/develop/variant/_variant.create.function.scss) function to retrieve color, and use `no-property-name` among with `name` in `$type` equal to `color`. [5bfe892]
- **Add** [`variant.property-multiple-is()`](https://github.com/angular-package/sass/blob/develop/variant/property/_property.multiple-is.function.scss) function to check whether `$value` is multiple properties. [e97555c]
- **Add** [`variant.property-multiple()`](https://github.com/angular-package/sass/blob/develop/variant/property/_property.multiple.function.scss) function to handle multiple properties in variant. [dc7f92c]
- **Fix** [`color.name-replace()`](https://github.com/angular-package/sass/blob/develop/color/name/_name.replace.function.scss) function - change variable `$update` to `$replace`, set argument `$type` to `null` by default, use directly `adjustment.has()`. [5e7068e]
- **Update** [`color.variant-create()`](https://github.com/angular-package/sass/blob/develop/color/variant/_variant.create.mixin.scss) function - remove color indicator from class and property, and handle multiple properties. [fda9204]
- **Update** [`name.retrieve()`](https://github.com/angular-package/sass/blob/develop/color/name/_name.retrieve.function.scss) function - add  `input-name`, `property`, `property-name`, `no-property-name` properties - retrieve property from name. [534249e]
- **Update** [`property.name()`](https://github.com/angular-package/sass/blob/develop/property/_property.name.function.scss) function - remove duplicates from name. [7eb5e2e]
- **Update** add to [`list.remove-duplicate()`](https://github.com/angular-package/sass/blob/develop/list/remove/_remove.duplicate.function.scss) function `$remove` arbitrary argument to define what duplicate remove. [3fab0a7]
- **Update** move [`modifier-retrieve()`](https://github.com/angular-package/sass/blob/develop/variant/modifier/_modifier.retrieve.function.scss) function to module [`modifier`](https://github.com/angular-package/sass/tree/develop/variant/modifier). [15b13f1]
- **Fix** forward main index. [eb1b424]

[8081d34]: https://github.com/angular-package/sass/commit/8081d3444ddb73aff2f79055e97884b39c7be4eb
[305e6c1]: https://github.com/angular-package/sass/commit/305e6c1d06dfaf0152fa0976ace215dff8828337
[eca4b74]: https://github.com/angular-package/sass/commit/eca4b7488eafe9d7e4f72ec7bf914a5bc83d7e5d
[ce0cdc4]: https://github.com/angular-package/sass/commit/ce0cdc4ca1397c800b8e372e99fd3a31ea506a10
[b5679c6]: https://github.com/angular-package/sass/commit/b5679c6924547decd094f9a24c66d57540daa6ff
[d853f93]: https://github.com/angular-package/sass/commit/d853f939164eb919f5eb32c2b891600078461153
[5bfe892]: https://github.com/angular-package/sass/commit/5bfe8921086acadc1a77fe752640b19d874046e1
[e97555c]: https://github.com/angular-package/sass/commit/e97555c6b96a7b53d08cb3b7f1e0faa5868bf741
[dc7f92c]: https://github.com/angular-package/sass/commit/dc7f92c437d247e86d69844cb637b11dd81bc0b2
[5e7068e]: https://github.com/angular-package/sass/commit/5e7068ed58df3088b8ff686c71a6e8290bf77c05
[fda9204]: https://github.com/angular-package/sass/commit/fda92040fc088a2f78b26e44e4b4d39d38317271
[534249e]: https://github.com/angular-package/sass/commit/534249ecad780d6fa0fd6e85fb4acf310cce4745
[7eb5e2e]: https://github.com/angular-package/sass/commit/7eb5e2ea49300c778a916f4bc6fa208d496ea063
[3fab0a7]: https://github.com/angular-package/sass/commit/3fab0a7e552d6da685016f98e67494772d02dd40
[15b13f1]: https://github.com/angular-package/sass/commit/15b13f13c12bd5a03a375a0af648091e0906be3e
[eb1b424]: https://github.com/angular-package/sass/commit/eb1b424f717a59480ea47c6593caaf3f4e84bdae

### v0.18.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.18.0-beta)

- **Update** `color.palette-create()` handle multiple colors in nested colors and use `variant.create()` function from `palette`. [06544a7]
- **Fix** `variant.indicator-remove()` - remove indicator in nested list, by checking whether element contains indicator. [7eba13a]
- **Add** schema palette submodule with `has-multiple-colors()` function to check whether schema to create palette has multiple colors. [2cefe16]
- **Update** `variant.indicator-index()` use directly `string.index()`. [c21bdb6]
- **Add** `color.palette-variant-create()` function from `palette.create()` to create variant based on schema. [4d5d2b7]

[06544a7]: https://github.com/angular-package/sass/commit/06544a7c55007525da9ea797a3a68112b0e605b1
[7eba13a]: https://github.com/angular-package/sass/commit/7eba13ae7d997ddb0cac01dfd6b3cfbf9af9a2c4
[2cefe16]: https://github.com/angular-package/sass/commit/2cefe16f84eb3ff3b8e353d5af26ea0a0ef477f7
[c21bdb6]: https://github.com/angular-package/sass/commit/c21bdb6f934d70c975f6bc550f82569551edcff3
[4d5d2b7]: https://github.com/angular-package/sass/commit/4d5d2b7c8a25fd9a5be63ef97508a7bdb5e23b8a

### v0.17.1-beta [#](https://github.com/angular-package/sass/releases/tag/v0.17.1-beta)

- **Fix** `palette.create()` - adding color to variant colors. [2f277bf]
- **Fix** `name.adjust()` - change `> 0` to `!=`. [2ab64bc]

[2f277bf]: https://github.com/angular-package/sass/commit/2f277bf3baae46d385921619a2b2455c22d544cc
[2ab64bc]: https://github.com/angular-package/sass/commit/2ab64bcb8d161fbc8e8ed5571d3ef43600ecfbce

### v0.17.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.17.0-beta)

- **Update** `color/functions` - calculate using adjustment (from name too) all hsla values and move retrieve color to each hsla functions.
  Add `$shade` with `dark` and `light` by default and `$color` with retrieve arguments in each hsla functions.
  Add `$shade` also to `hsla-color()` function. [69010c0]
- **Fix** `color.alpha-var()` `color.hue-var()` `color.saturation-var()` `color.lightness-var()` use `$delimiter` in `var.get()` instead of `name()`. [341a929]
- **Fix** `class/variant` - add `$index` to `each()`. [b60fd3a]
- **Add** `palette.delete()` function to delete by palette name, variant class and its colors from palettes. [871103c]
- **Fix** `variant.nest()` - use `$variant-nested` instead of `$resolved-value` and change name of `$resolved-value` to intuitive `$class-color`. [5ae508a]
- **Add** `color.palette-get()` - add updated `get()` function to use instead of old get function. [72d34cc]
- **Add** `color.name-update()` - add function to update name especially with adjustment. [7ca383a]
- **Add** `name/hsla` module to check and remove hsla indicator. [080e37e]
- **Add** `name/adjustment` module with - function to `get()` and `remove()` operator from name adjustment and `calculate()`. [1bb2397]
- **Add** `color.palette-get-keys()` function to find keys using `name.index()`. [a7c63cf]
- **Add** `map.get-index()` - add function to get value based on key checked by `list.index()`. [e1459b9]
- **Add** `palette.each()` - add mixin to iterate palette. [8ac459b]
- **Update** `variant.create()` - add `$type` argument to retrieve from color name to set key. [30e19ae]
- **Remove** `color.name-nest()` function from index. [22fb98c]
- **Add** `palette.color-add()` check type of variant color and append or join into the list. [937586c]
- **Update** `variant.nest()` function to use nest from color. [d423b7c]
- **Update** `color.palette-create()` function to handle creation of multiple colors in variant. [d880d60]
- **Add** `color.palette-color-add()` function to add color to variant. [bd5ec62]
- **Add** `color.palette-color-remove()` to remove color from variant, `color.palette-variant-add()` to add variant. [2e53679]
- **Update** Set `color.name-nest()` as deprecated. [fa25fcb]
- **Add** `color.name-add-indicator-multiple()` function to add indicator(`color`) to multiple names. [d26d365]
- **Update** `color.name()` - use `name` module. [829a614]
- **Update** `color.name-adjust()` - add `$hue` `$saturation` `$lightness` `$alpha` `$separator` arguments. [8124aa0]
- **Update** `color.name-retrieve()` - check whether each attribute has number. [5d872b8]
- **Add** `color.name-append()` function to add color name to list of colors. [d1d571b] [3815399]
- **Add** `color.name-remove()` function to remove color from list of color names. [79ac36b]
- **Add** `color.name-create()` function to create color name with `color` indicator. [2897f63]
- **Add** `color.name-add-indicator()` function to `name` module to add `color` indicator including shades. [653b1b5]
- **Fix**  fix `list.index()` function - remove checking type of `$list`. [bece908]
- **Add** submodule `name` and add `color.name-adjust-multiple()` to adjust multiple color names, `color.name-index()` function to find `index` of specific name. [6587c4d] [e5fc8d6] [b15c567]
- **Add** `color.name-adjust()` to adjust `hsla` color attributes in name. [7699304]

[69010c0]: https://github.com/angular-package/sass/commit/69010c0361a75dceb42531a7f95d035137e417a4
[341a929]: https://github.com/angular-package/sass/commit/341a9299bf8ba73a7091f02b827e66e88aaf4c60
[b60fd3a]: https://github.com/angular-package/sass/commit/b60fd3a92f66027e5b77fb50d67b3336de42fd3a
[871103c]: https://github.com/angular-package/sass/commit/871103c30b050b43753a4eac8a9f8eb4f3b50d03
[5ae508a]: https://github.com/angular-package/sass/commit/5ae508a5f5b1934c61d1e2a3a39a998cda53319c
[72d34cc]: https://github.com/angular-package/sass/commit/72d34cc46a914618fe8e65e326182f67ca7d7a9e
[7ca383a]: https://github.com/angular-package/sass/commit/7ca383a582a53e0197d9866df17c13309a80eb90
[080e37e]: https://github.com/angular-package/sass/commit/080e37e0a088c1f6e2f464d4926081f097846dd0
[1bb2397]: https://github.com/angular-package/sass/commit/1bb2397abe6f43691f5ad92750a0cbe5c25ff501
[a7c63cf]: https://github.com/angular-package/sass/commit/a7c63cf45001c2765bc84511135552eb4cd4fba0
[e1459b9]: https://github.com/angular-package/sass/commit/e1459b9f59051db335d8c86349bbc14edaf80be6
[8ac459b]: https://github.com/angular-package/sass/commit/8ac459b410a021fe139e6d6f0c7c992ad5cd2f0c
[30e19ae]: https://github.com/angular-package/sass/commit/30e19ae629b8246f21936de20f89b02cd4cfeab5
[22fb98c]: https://github.com/angular-package/sass/commit/22fb98c9821f43b1bc2a9ad9eccd0aa24bb61ecd
[937586c]: https://github.com/angular-package/sass/commit/937586c5aec38f01e0e3c34e4e93521cf3d51cf1
[d423b7c]: https://github.com/angular-package/sass/commit/d423b7c6d585c170466840365d668561db9cf6fc
[d880d60]: https://github.com/angular-package/sass/commit/d880d60774d703abebcd96fdf5ca2e100365db8a
[bd5ec62]: https://github.com/angular-package/sass/commit/bd5ec621fed90830fa2b990b4871b937aa00da0e
[2e53679]: https://github.com/angular-package/sass/commit/2e53679636e120110e51e61cd3d91570ece151ec
[fa25fcb]: https://github.com/angular-package/sass/commit/fa25fcb2185c3d33e76cff098cb9df9b03c8f64d
[d26d365]: https://github.com/angular-package/sass/commit/d26d3659c7e2e4c34bf0752b6d39f2da26aab4ea
[829a614]: https://github.com/angular-package/sass/commit/829a614780119f17e2170ce1e90dd5eb2b57ac10
[8124aa0]: https://github.com/angular-package/sass/commit/8124aa0fb9e15cb91a93621673adc43bc23d491a
[5d872b8]: https://github.com/angular-package/sass/commit/5d872b82e39c862dc869ca5d5c237203f8d23c30
[3815399]: https://github.com/angular-package/sass/commit/38153994f181c65f76b37238598e3927c831aee7
[d1d571b]: https://github.com/angular-package/sass/commit/d1d571bcba3a2f2bf1b2b0a336422cbdf05e95f5
[79ac36b]: https://github.com/angular-package/sass/commit/79ac36bfd37a55f0195efdc525dc1aa1611c46a4
[2897f63]: https://github.com/angular-package/sass/commit/2897f637583aaa7c66fb98091f83a6db713771dc
[653b1b5]: https://github.com/angular-package/sass/commit/653b1b5aaac1677e5f606b17f28a38eea8600271
[bece908]: https://github.com/angular-package/sass/commit/bece9088dd3d28ab24164a16cc9a4d3b56adc82f
[b15c567]: https://github.com/angular-package/sass/commit/b15c567fe572165f1f15bf78cddc5bd8400f4da4
[e5fc8d6]: https://github.com/angular-package/sass/commit/e5fc8d670936f29ad158f494058339a26809d502
[6587c4d]: https://github.com/angular-package/sass/commit/6587c4d46bfb890617d59fa9a879e5ce75b59a20
[7699304]: https://github.com/angular-package/sass/commit/76993048381f7aea18f913fc037e3e5f7c8c82c5

### v0.16.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.16.0-beta)

- **Update** `indicator.remove()` - remove indicator from `string`. [30bdf0a]
- **Fix** `color.theme-load()` - add `$detect` argument and update spec. [5d095fe]
- **Fix** `color.theme-build()` - change the way of build theme to use color-scheme or theme name. Update spec. [48e2bf8]
- **Add** `color.scheme-set()` - add function to set `$color-scheme`. [9e5f583]
- **Update** `palette.create()` - first check type of `$color`, should be `map`. [0e7dafc]
- **Fix** `color.set-hsla-color()` - change the way to resolve `$name` - check the separator `comma` and type-of `string`. [331ff42]

[9e5f583]: https://github.com/angular-package/sass/commit/9e5f583e83bba383f8c72e33e672989670296f5c
[30bdf0a]: https://github.com/angular-package/sass/commit/30bdf0a699c6cf88d6a4c2031b9e4846b06a1bda
[5d095fe]: https://github.com/angular-package/sass/commit/5d095fe14009e4d40f3264ebb4f668ea3bb4945b
[48e2bf8]: https://github.com/angular-package/sass/commit/48e2bf84815151505d4c2e66aabbea0d366b1c77
[0e7dafc]: https://github.com/angular-package/sass/commit/0e7dafcca93c301867ec2fdb9605fd787f6d99b1
[331ff42]: https://github.com/angular-package/sass/commit/331ff428221f0cbddd52e8a602ba8438d8020127

### v0.15.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.15.0-beta)

- **Add** [`variant.nest()`](https://github.com/angular-package/sass/blob/develop/variant/_variant.nest.function.scss) - add function to nest variant of `map` or `list` type. [2ed7089]
- **Fix** [`color.palette-create()`](https://github.com/angular-package/sass/blob/develop/color/palette/_palette.create.mixin.scss) - add `deep-merge()` if `$color` is not `map`. [3c3482d]
- **Fix** [`color.theme-build()`](https://github.com/angular-package/sass/blob/develop/color/theme/_theme.build.function.scss) add `$name` to `$palette` as `map` and update spec. [7189d9e]
- **Fix** [`color.set-hsla-color`](https://github.com/angular-package/sass/blob/develop/color/mixins/set/_color.set-hsla-color.mixin.scss) mixin to use `$dictionary`. [727798d]
- **Update** [`class.variant-create()`](https://github.com/angular-package/sass/blob/develop/class/variant/_variant.create.mixin.scss) function to use relative `&` to class and update spec. [8ce0b5d]

[2ed7089]: https://github.com/angular-package/sass/commit/2ed708992081514bf9b269f84fa68bb537bfee22
[3c3482d]: https://github.com/angular-package/sass/commit/3c3482dd243396f420988ada47196256a1b2ea8d
[7189d9e]: https://github.com/angular-package/sass/commit/7189d9eeba1ceb2a949e67ccd1e0aaa85b4a65c6
[727798d]: https://github.com/angular-package/sass/commit/727798dfa5ea666082e35bd6fc6bac5d0e9f138d
[8ce0b5d]: https://github.com/angular-package/sass/commit/8ce0b5d724abda449491ac91bf2d7bd8fdce1f7f

### v0.14.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.14.0-beta)

- **Update** `palette.create()` - remove color indicator from map key. [2f9d8b8]
- **Fix** `variant.class-property()` - add `$index` to `list.each()`. [6b113c5]
- **Update** `variant/indicator` `remove()` function - remove indicator from nested lists. [9acd4a3]
- **Update** `map.keys()` by adding `keys-pattern()` - function to result. [2d90fbd]
- **Add** theme module to handle color themes. [178141f]
- **Add** `color/palette` - module to create color palette. [1025ed5] [fcdf0c9]
- **Update** `map.pick()` - add required `$key` argument, and ability to pick key with last element as pattern. [e66cea2]
- **Add** `map.key-pattern-index()` - function to get index of pattern `'*'`, `'^'`, `'$'`. [011e574]
- **Add** `map.keys()` function to retrieve keys or keys with pattern. [60c8ef5]
- **Update** `map.pick-pattern()` - add `'^'` start and `'$'` end string pattern to pick values. [1100a95]
- **Update** `map.pick-key-substring()` - add `'^'` start and `'$'` end `string` pattern to pick values. [a603ea4]
- **Add** `map.keys-pattern()` function that returns keys / nested keys with pattern where `'*'` is substring, `'^'` is start, and `'$'` is end of `string`, add patterns to variables. [0d90f5d]
- **Update** `pick.pattern()` - add `$pattern` argument and `by-pattern()` alias name. [35e3547]
- **Update** `map` module - add required `$key` argument `map.deep-merge-key()` `map.has-keys()` `map.remove()`. Add required `$type` argument, and change `auto` separator to `comma`. Add required `$substring` argument to `key-substring()`, `$type` argument to `key-type()` `value-type()`. Add `$field-types` arbitrary argument to `type()`. [a634e46]
- **Update** `color.name()` - add `$hue` `$saturation` `$lightness` `$alpha` `$shade` arguments to define color name. [e7fcb16]
- **Update** `color.set-hsla-color()` retrieve color name from `$name`. [59da59e]
- **Add** `color.name-nest()` function to nest color name with adjustments. [1210a86]
- **Add** `list.invert()` function to invert elements. [11f6dcf]
- **Update** `list.each()` - add `$index` argument of `$list`. [9a121bb]
- **Add** `name` and `tag()` function to `selector` module. [2a77e6b]
- **Add** `map.depth()` function to determine map depth. [41276b1]

[2f9d8b8]: https://github.com/angular-package/sass/commit/2f9d8b8d1b41989ba40796175b09a579a0d97fd7
[6b113c5]: https://github.com/angular-package/sass/commit/6b113c5284c065868e8e5036d398ba43f8e6a15e
[9acd4a3]: https://github.com/angular-package/sass/commit/9acd4a37ab5f85686a7bdd6b4833120af5651deb
[2d90fbd]: https://github.com/angular-package/sass/commit/2d90fbdc25d84fb38c70ac1eaa7a15addd1d99ec
[178141f]: https://github.com/angular-package/sass/commit/178141f420083cc390b3b1a15ba399ee24f83b92
[fcdf0c9]: https://github.com/angular-package/sass/commit/fcdf0c96126d8dc34ee4e7ce785aaf12a0464a4a
[1025ed5]: https://github.com/angular-package/sass/commit/1025ed52caeef1d2d82cd2d74277e7d16971fff7
[e66cea2]: https://github.com/angular-package/sass/commit/e66cea2ef7f40f81579d9d3997d6491124c8d280
[011e574]: https://github.com/angular-package/sass/commit/011e574e3f26313bad7d5a7ad38a1fb430166f44
[60c8ef5]: https://github.com/angular-package/sass/commit/60c8ef507fd43f1c4e1a79d794e5fc607baddd13
[1100a95]: https://github.com/angular-package/sass/commit/1100a958236a8acf730c8926c1b582f9c7aa488b
[a603ea4]: https://github.com/angular-package/sass/commit/a603ea4b000f1f669b4130f40a2fb5532293cf4e
[0d90f5d]: https://github.com/angular-package/sass/commit/0d90f5d0d6d923060453f2ea1ee43c77c0c1090c
[35e3547]: https://github.com/angular-package/sass/commit/35e35476b010ae468eaa29bbb0d0af57227df72d
[a634e46]: https://github.com/angular-package/sass/commit/a634e46b7cc0fab1569943d6782773deaac25290
[e7fcb16]: https://github.com/angular-package/sass/commit/e7fcb1611cfe035251af920f90969edf6e6cfdea
[59da59e]: https://github.com/angular-package/sass/commit/59da59e8a512f4a72c235fcca0baa53b9e78e820
[1210a86]: https://github.com/angular-package/sass/commit/1210a8676aa7fd152b5ef1e4eab8642f101d4ae5
[11f6dcf]: https://github.com/angular-package/sass/commit/11f6dcf623947a3b80dd9eed8bfce140e61d3d1e
[9a121bb]: https://github.com/angular-package/sass/commit/9a121bba33d89c9ba4de02f838e800a2f8a2f900
[2a77e6b]: https://github.com/angular-package/sass/commit/2a77e6b0b2cdf2f655dc05308a16548800d919ae
[41276b1]: https://github.com/angular-package/sass/commit/41276b1df455f6ff453322a6e70150c838740855

### v0.13.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.13.0-beta)

- **Add** `variant.modifier-retrieve()` function to retrieve modifier settings in `variant.transform()`. [dad3966]
- Move `variant` mixins to the `color/variant` directory. [a99dcd2]
- **Add** `color.variant-create()` to replace `color.variant()`. [3083e75]
- **Add** `class.variant-create()` mixin to replace `class.variant()`. [47e5a29]
- **Add** `property.class-variant()` as replacement for `property.variant()`. [ceed6b1]
- Update `property.name()` - move spec to separate file `_property.name.function.spec.scss`, update function to handle multiple `map` in arbitrary arguments, simplify code. [c9332e7]
- Fix `map.get()` function not returning `false` value. [caf0325]
- Add `class` and `property` sub modules for `variant.transform()` mixin and `item` as replacement for `update`. [3ac59ae]
- Add `variant.class-property()` mixin for `variant.transform()` mixin. [3ac59ae]
- Add `variant.append()` function to append variant to bracketed list(rows) as `map` type. [3ac59ae]
- **Add** `variant.transform()` mixin to transform variants into rows of `map` type prepared for `class.content()`. [3ac59ae]
- Update `update.property()` to use `middle` and `pre-base` name and ability to modify  variant item/level 1 - 3. [beabe0c]
- Update `variant.update()` to add ability to modify variant item/level 1 - 3. [0272f3c]
- Fix `property.variant()` mixin to use values.combine() instead values.join() to have proper name. Add additional examples. [b58f461]
- Update `class.variant()` mixin to use `+` indicator, `$modifier` with ability to modify variant 1, 2, 3. Additional property name `middle`, `pre-base`. [6ab09c8]
- Update `selector.nest()` to remove `null` and empty list `()` before nesting. [942e6b3]
- Add `variant/indicator` submodule to handle `+` in variants. [9fb0fca]

[dad3966]: https://github.com/angular-package/sass/commit/dad3966a15c4a19c1ef06c6e3f7689704ae18280
[a99dcd2]: https://github.com/angular-package/sass/commit/a99dcd253bad1fb4c6a3ade149cc3aff198db833
[ceed6b1]: https://github.com/angular-package/sass/commit/ceed6b1094417fdef9cf2989600fc01daa5c9cff
[3083e75]: https://github.com/angular-package/sass/commit/3083e75120cedb9daa26408d09db75269249a18f
[47e5a29]: https://github.com/angular-package/sass/commit/47e5a294027c7d68e8ae3f671bb0209d8737a19c
[c9332e7]: https://github.com/angular-package/sass/commit/c9332e755c7ec3d65c49a1d6b0120d6494a945a9
[caf0325]: https://github.com/angular-package/sass/commit/caf0325cad8aa7e5d8827f3400c65d17a5055480
[3ac59ae]: https://github.com/angular-package/sass/commit/3ac59ae4f6915d37984b334c5e4116bae9076ef2
[beabe0c]: https://github.com/angular-package/sass/commit/beabe0c14db8eb5b3e84e8a04b54dfff317bf8e6
[0272f3c]: https://github.com/angular-package/sass/commit/0272f3cd4310fa430fb4ff784f075c342ec1df4d
[b58f461]: https://github.com/angular-package/sass/commit/b58f461eb40c3827dc3d2f40c6fce41ee52674e6
[6ab09c8]: https://github.com/angular-package/sass/commit/6ab09c8ec7a7d37335209ba082e26fb805aa4397
[942e6b3]: https://github.com/angular-package/sass/commit/942e6b36fc6ccbb838603c18300eac1bfd1e3f89
[9fb0fca]: https://github.com/angular-package/sass/commit/9fb0fca94c96cc441d4a404581a2e024d4594e97

### v0.12.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.12.0-beta)

- Add [`variant.update()`](https://github.com/angular-package/sass/blob/main/variant/_variant.update.function.scss) to use instead `variant.modify()`. [69af150]
- Update [`variant.create()`](https://github.com/angular-package/sass/blob/main/variant/_variant.create.function.scss) to have functionality to add full variant. [a76c8ce]
- ~~Update `variant.modify()` to use `$modifier` argument to modify, use `update` sub module, and add `variant.update()` alias name. [410cc51]~~
- Update [`class/variant`](https://github.com/angular-package/sass/tree/main/class/variant) to use `@each` mixin and [`update.property()`](https://github.com/angular-package/sass/blob/main/variant/update/_update.property.function.scss) function from `variant` module. [1230281]
- Add [`list.each()`](https://github.com/angular-package/sass/blob/main/list/_list.each.mixin.scss) mixin. [6a7c2fe]
- Add [`class/affix`](https://github.com/angular-package/sass/tree/main/class/affix) sub module to handle class affixes. [b4a49d1]
- Update [`class.variant()`](https://github.com/angular-package/sass/blob/main/class/variant/_variant.mixin.scss) to use `$key` in `nest()` when its length > 0 and use [`update.property()`](https://github.com/angular-package/sass/blob/main/variant/update/_update.property.function.scss) from `variant` module. [1e8a29c]
- Add [`list.update()`](https://github.com/angular-package/sass/blob/main/list/_list.update.function.scss) function to update `$list` by provided `nth-value` pairs of `map` or `list` type. [104abd7]
- Add [`map.get-any()`](https://github.com/angular-package/sass/blob/main/map/_map.get-any.function.scss) function to get the value from any key where value is not `null`. [cef2405]

[69af150]: https://github.com/angular-package/sass/commit/69af1500dbae4a5008c32b7de04228b5cc634574
[a76c8ce]: https://github.com/angular-package/sass/commit/a76c8cec8593c6dcccc3c8f386759acd7410362f
[410cc51]: https://github.com/angular-package/sass/commit/410cc51677d97c069d19b8f1e8887d0da6434cfc
[1230281]: https://github.com/angular-package/sass/commit/1230281dea6d850f78f2122667f6256ab193c0da
[6a7c2fe]: https://github.com/angular-package/sass/commit/6a7c2fec33c28365352b91ba12657fbaf247fc48
[b4a49d1]: https://github.com/angular-package/sass/commit/b4a49d196dbee1578c033cf93175b0133cc5413c
[1e8a29c]: https://github.com/angular-package/sass/commit/1e8a29c0c5a1d39ec261f87e0907d92479403b4b
[104abd7]: https://github.com/angular-package/sass/commit/104abd7e02f21fe20b714361c5d5faa529f308f1
[cef2405]: https://github.com/angular-package/sass/commit/cef240521778b121fcb2bf8fe1a8cb5e6466e227

### v0.11.1-beta [#](https://github.com/angular-package/sass/releases/tag/v0.11.1-beta)

- Update [`color.variant()`](https://github.com/angular-package/sass/blob/main/color/mixins/_color.variant.mixin.scss) use `$modifier` argument in the `class.variant()`. [dd72913]

[dd72913]: https://github.com/angular-package/sass/commit/dd729133d09d7d9f581ece14ce7388dbcb2c457c

### v0.11.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.11.0-beta)

- Add new [`variant`](https://github.com/angular-package/sass/tree/main/variant) module to handle variants. [a7a8c1c]
- Update [`class.variant()`](https://github.com/angular-package/sass/blob/main/class/variant/_variant.mixin.scss) by adding `$modifier` argument to modify class and property. [89f34e3]
- Update [`property.variant()`](https://github.com/angular-package/sass/blob/main/property/_property.variant.mixin.scss) to use [`values.join()`](https://github.com/angular-package/sass/blob/develop/values/_values.join.function.scss) function and add `$modifier` argument to modify class and property. [c8c8f5b]
- Update [`property.name()`](https://github.com/angular-package/sass/blob/main/property/_property.name.function.scss) function to remove empty lists from `$name`. [21ef23a]
- Update [`class.variant()`](https://github.com/angular-package/sass/blob/main/class/variant/_variant.mixin.scss) function to use [`values.join()`](https://github.com/angular-package/sass/blob/develop/values/_values.join.function.scss) and update spec. [7d0c18e]
- Update [`variant.combine()`](https://github.com/angular-package/sass/blob/main/values/_values.combine.function.scss) to use [`values.join()`](https://github.com/angular-package/sass/blob/develop/values/_values.join.function.scss) and use and update spec. [5afd3c2]
- Add separate mixins in [`class/variant`](https://github.com/angular-package/sass/tree/main/class/variant) to create class variant and update spec. [e8d08d3]
- Add [`values.join()`](https://github.com/angular-package/sass/blob/main/values/_values.join.function.scss) **wrapper** function. [971af80]
- Add [`list.merge()`](https://github.com/angular-package/sass/blob/main/list/_list.merge.function.scss) function to merge smaller `$list2` into `$list1`. [9788cb3]

[a7a8c1c]: https://github.com/angular-package/sass/commit/a7a8c1c60ebe58f0b06dcac8865f5068709a1c8d
[89f34e3]: https://github.com/angular-package/sass/commit/89f34e3fcb03f77b6b5b0e659da533bf92518b81
[c8c8f5b]: https://github.com/angular-package/sass/commit/c8c8f5b1b67530023f3ecc5bf489bb3315bee69c
[21ef23a]: https://github.com/angular-package/sass/commit/21ef23a863551233b55be6a73e97e383c30c4a9a
[7d0c18e]: https://github.com/angular-package/sass/commit/7d0c18edc74f3a1945a9d42e7f02443cd3259914
[5afd3c2]: https://github.com/angular-package/sass/commit/5afd3c210a880284091709ee7136d38e15ef571d
[e8d08d3]: https://github.com/angular-package/sass/commit/e8d08d349b66cecc58a844ebd5f1a044d49f08fc
[971af80]: https://github.com/angular-package/sass/commit/971af807842804fe000e091440121deee29ac347
[9788cb3]: https://github.com/angular-package/sass/commit/9788cb36dd808d4dfcd3a7f43759e28e4493bd06

### v0.10.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.10.0-beta)

- Update [`dictionary`](https://github.com/angular-package/sass/tree/main/translator/v1.0.0/dictionary) use [`object wrapper`](https://github.com/angular-package/sass/blob/develop/object/_object.wrapper.scss) functions and update spec. [a68ed19]
- Update [`dictionary`](https://github.com/angular-package/sass/tree/main/translator/v1.0.0/dictionary) by adding `call()` function to use as separate object. [a349181]
- Update [`object.use()`](https://github.com/angular-package/sass/blob/main/object/_object.use.function.scss) by simply assign value. [83835d9]
- Update test [`object`](https://github.com/angular-package/sass/blob/main/object/_object.spec.scss) update. [fc324ed]
- Update [`object`](https://github.com/angular-package/sass/tree/main/object) by using internal [`map.set()`](https://github.com/angular-package/sass/blob/main/map/_map.set.function.scss) in the [`object.create()`](https://github.com/angular-package/sass/blob/main/object/_object.create.function.scss) and [`object.set()`](https://github.com/angular-package/sass/blob/main/object/_object.set.function.scss). [066b449]
- Add [`object.wrapper`](https://github.com/angular-package/sass/blob/main/object/_object.wrapper.scss) functions in combination with [`object.call()`](https://github.com/angular-package/sass/blob/main/object/_object.call.function.scss) function to use as different objects. [df03e46]
- Update [`object`](https://github.com/angular-package/sass/tree/main/object) module by removing `object.var` from [`move()`](https://github.com/angular-package/sass/blob/main/object/_object.move.function.scss) and [`keys()`](https://github.com/angular-package/sass/blob/main/object/_object.keys.function.scss) functions, and set as first in [`index`](https://github.com/angular-package/sass/blob/main/object/_index.scss). [847c2f0]

[a68ed19]: https://github.com/angular-package/sass/commit/a68ed199a578905e35f707d6c954fa3b818fb551
[a349181]: https://github.com/angular-package/sass/commit/a349181bf24ff1aac9c43963f3f730165e72fc00
[83835d9]: https://github.com/angular-package/sass/commit/83835d98a131198840a49cb903cba9b444174cad
[fc324ed]: https://github.com/angular-package/sass/commit/fc324edd26db0911985f958e23e18bd7508b3c43
[066b449]: https://github.com/angular-package/sass/commit/066b449e5afa1d20598635b14d1c548353c16fdd
[df03e46]: https://github.com/angular-package/sass/commit/df03e46bdca5c4384d4a3fd281f798d8fa68343e
[847c2f0]: https://github.com/angular-package/sass/commit/847c2f0f9806d74d8a80df0069e771876d0fdd61

### v0.9.4-beta [#](https://github.com/angular-package/sass/releases/tag/v0.9.4-beta)

- Fix `color` module mixins `color.background-color()`, `color.background()`, and `color.color()` by removing `$selector` argument not in use. [8884903]

[8884903]: https://github.com/angular-package/sass/commit/888490353c3831e66d604f2c5a6d0763e73e9526

### v0.9.3-beta [#](https://github.com/angular-package/sass/releases/tag/v0.9.3-beta)

- Fix [`color/mixins`](https://github.com/angular-package/sass/tree/main/color/mixins) by using function from functions and update imports. [159a652]

[159a652]: https://github.com/angular-package/sass/commit/159a6520c867320c1c39f02196fdba7fc11e92f5

### v0.9.2-beta [#](https://github.com/angular-package/sass/releases/tag/v0.9.2-beta)

- Remove function from `color/mixins`. [b7ff1af]

[b7ff1af]: https://github.com/angular-package/sass/commit/b7ff1afe3370499d6a1ee2fcdd9ed5146fafcf24

### v0.9.1-beta [#](https://github.com/angular-package/sass/releases/tag/v0.9.1-beta)

- Fix by adding `media` to ng-package assets. [5da60de]

[5da60de]: https://github.com/angular-package/sass/commit/5da60de6ae46298a4ee083e656aaa42989a9b3bd

### v0.9.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.9.0-beta)

- Update [`var.set()`](https://github.com/angular-package/sass/blob/main/var/mixins/_var.set.mixin.scss) add `$dictionary` argument to translate CSS variable names. [99647c2]
- Add [`media`](https://github.com/angular-package/sass/tree/main/media) module with function to add `@content` depending on `$color-scheme`. [439305e]
- Add `color.scheme-has()` function to check whether value has `dark`, `light`, or `normal` string. [a4b9f63]
- Add color mixins to set color CSS variable and CSS property. [ed33bb0]
- Fix [`list.remove-value()`](https://github.com/angular-package/sass/blob/main/list/remove/_remove.list.function.scss) function by using separator from `$list` in the returned result. [0c35160]
- Fix [`string`](https://github.com/angular-package/sass/tree/main/string) module by removing `split` function from `@forward`. [fffcc7d]

[99647c2]: https://github.com/angular-package/sass/commit/99647c2531b13f58f20d96c021fe4958f8a80103
[439305e]: https://github.com/angular-package/sass/commit/439305e74d3a31bdf3e31e7336da35738dcb0bd0
[a4b9f63]: https://github.com/angular-package/sass/commit/a4b9f636ea20e2014f55c41a1619aff01e498ac0
[ed33bb0]: https://github.com/angular-package/sass/commit/ed33bb0a189d54225aa8c29a4925ca291a69f53f
[0c35160]: https://github.com/angular-package/sass/commit/0c351602825c019fde91cce471da24bbf8329449
[fffcc7d]: https://github.com/angular-package/sass/commit/fffcc7dc59109bffd0ab14d13d4e5e8c4507a89a

### v0.8.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.8.0-beta)

- Add [`object.destroy()`](https://github.com/angular-package/sass/blob/main/object/_object.destroy.function.scss) to remove object. [127c5e4]
- Update [`translator/dictionary`](https://github.com/angular-package/sass/tree/main/translator/v1.0.0/dictionary) module to use `object` module. [ae50b2a]
- Update [`object.set()`](https://github.com/angular-package/sass/blob/main/object/_object.set.function.scss) function to return `$name` on `$name` equal to `object.$name`. [3e2f9b8]
- Add [`object.has-key()`](https://github.com/angular-package/sass/blob/main/object/_object.has-key.function.scss) function to check the key in any object. [25b7bff]
- Add [`object.get-key()`](https://github.com/angular-package/sass/blob/main/object/_object.get-key.function.scss) function to get key object of `$name` and `$key`. [c05d520] [112747d]

[3e2f9b8]: https://github.com/angular-package/sass/pull/18/commits/3e2f9b8569d98d9f9baa5b1319f62a0ccad58d8a
[127c5e4]: https://github.com/angular-package/sass/commit/127c5e4235ca08608a7889cc67c6872eea03509f
[ae50b2a]: https://github.com/angular-package/sass/commit/ae50b2a9cdf76d8791aeebe93ef4c5def16b11c8
[25b7bff]: https://github.com/angular-package/sass/commit/25b7bff9bfdce8b1399ced485aa015b74f72671f
[112747d]: https://github.com/angular-package/sass/commit/112747d3b4baeac610f08e7fc0ec22cc7c40d5af
[c05d520]: https://github.com/angular-package/sass/commit/c05d52067755dfdaf368e16164bb1ba9570592ed

### v0.7.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.7.0-beta)

- Fix `map.set()` - add checking whether `$key` is comma-separated list to have ability to add space separated keys. [1d46564]
- Add `query` module to search in `list` by using query. [3e2c20c]
- Add experimental `object` module to handle multiple multiple `keys` in `map` variable as objects. [5274590] [6e16608]
- Add `map.is()` function to check whether the `$value` is `map` of optionally `$length`. [1a3c52c]

[6e16608]: https://github.com/angular-package/sass/commit/6e166083a52cdafc4c338d3a0e65a2467f7915c8
[1d46564]: https://github.com/angular-package/sass/commit/1d46564fce0eb819a331f74b691e62320b6d001a
[3e2c20c]: https://github.com/angular-package/sass/commit/3e2c20c300f1daa4317a4ec6861bf2982cd9f245
[5274590]: https://github.com/angular-package/sass/commit/52745909997a1c514b348183a07cbb3203acd169
[1a3c52c]: https://github.com/angular-package/sass/commit/1a3c52cf6fe2b24119cca6325e6c5fc59242b3fd

### v0.6.1-beta [#](https://github.com/angular-package/sass/releases/tag/v0.6.1-beta)

- Fix `color.hsla-color()` and `color.retrieve()` by removing `values.map` import and change `values.map` to `list.to-map()`. [e8fe993]

[e8fe993]: https://github.com/angular-package/sass/commit/e8fe99345d70f82bd18d1f12c1a0f50c6ba0b8a1

### v0.6.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.6.0-beta)

- Fix `property.variant()` passing `$dictionary` argument by adding map `(dictionary: $dictionary)`. [df48216]
- Update `selector.class()` functionality to retrieve dictionary from `$dictionary` if key `class` is found. [ae518d4]
- Update `var.name()` functionality to retrieve dictionary from `$dictionary` if `var` is found. [f3e5c83]

[f3e5c83]: https://github.com/angular-package/sass/commit/f3e5c8387fc476bc33525bcb7c0fd88e116f0736
[ae518d4]: https://github.com/angular-package/sass/commit/ae518d4f0119f72c89f418fb70e275d86b183307
[df48216]: https://github.com/angular-package/sass/commit/df48216ed068549775da62dd1ba3a0f63d3841d4

### v0.5.1-beta [#](https://github.com/angular-package/sass/releases/tag/v0.5.1-beta)

- Fix `function.call-arglist()` by adding `$arguments` to the `$arglist` by using only `list.append()` function and checking if `$arglist` is space-separated list. [fd90100]

[fd90100]: https://github.com/angular-package/sass/commit/fd90100e2bca35904c8710c78189fd95aa7fcd0b

### v0.5.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.5.0-beta)

- Update `property` module to handle arguments to use `var.get()` function dictionary. [d28f797]
- Fix `dictionary/v1.0.0` purge `$dictionary` map variable. [5acab9f]
- Update `function/call` module to handle map type arguments with additional `$arguments` parameter and add spec. [dc6d444] [dc6926b]

[d28f797]: https://github.com/angular-package/sass/commit/d28f7979b4ee261919b254a3ddbfd05fa5f2f9be
[dc6926b]: https://github.com/angular-package/sass/commit/dc6926bd63b367123f1c51fc75b0d8183b202368
[5acab9f]: https://github.com/angular-package/sass/commit/5acab9f9b6d2d1cbb92a63dc10f16218fb3038b8
[dc6d444]: https://github.com/angular-package/sass/commit/dc6d444285b0f52f569d60126c7bacae30aa7b7a

### v0.4.1-beta [#](https://github.com/angular-package/sass/releases/tag/v0.4.1-beta)

- Add `property.variant()` to the `index`. [8c16e87]
- Fix `class.variant()` by checking `$attribute` against empty `list`. [9280a21]
- Fix `property.variant()` function by adding arguments to properly call retrieved functions. [96bcb0a]
- Fix unnecessary imports, and use `property.property()` in `property.variant()`. [213d174]

[9280a21]: https://github.com/angular-package/sass/commit/9280a21be5d222ba5b850ba6a8ec5a3f79920e3a
[213d174]: https://github.com/angular-package/sass/commit/213d17417cbf7fe94ff522a45221e734751fd228
[96bcb0a]: https://github.com/angular-package/sass/commit/96bcb0a2f38c4ea0199ed30d694f204b7fd7797c
[8c16e87]: https://github.com/angular-package/sass/commit/8c16e877f2c1d9bc5161db5b75158b4c7c899368

### v0.4.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.4.0-beta)

- Add **class** module to handle CSS class selectors(variants). [9a7fed7] [b51b22a] [01c830a] [a2ed250] [c88c00a]
- Add **color** module which extends `sass:color` module with functions to set `hsla()` color and `scheme` sub module to check `color-scheme`. [d596d48]
- Add **function** module to handle calling functions in `list` as `string`, `map` or `list` type. [5dbd420]
- Add **property** module to set CSS properties with functions. [79dccba]
- Add **selector** module sets selectors split into words(optionally translated). [a165ed8]

- Add `functions` with [`name()`](https://github.com/angular-package/sass/blob/develop/functions/_name.function.scss) function to create name from words that can be translated with `$dictionary` and `important` to add `!important` flag. [16bdb40]
- Add [`list.extract-map()`](https://github.com/angular-package/sass/blob/develop/list/_list.extract-map.function.scss),
  [`list.replace-string()`](https://github.com/angular-package/sass/blob/develop/list/_list.replace-string.function.scss),
  [`list.replace()`](https://github.com/angular-package/sass/blob/develop/list/_list.replace.function.scss),
  [`list.swap()`](https://github.com/angular-package/sass/blob/develop/list/_list.swap.function.scss),
  and [`list.to-map()`](https://github.com/angular-package/sass/blob/develop/list/_list.to-map.function.scss) functions. [66fdaef] [22f37e6] [1b37c23] [8c27019]
- Add [`map.merge-allowed()`](https://github.com/angular-package/sass/blob/develop/map/_map.merge-allowed.function.scss) function to merge allowed keys. [07e2904]
- Add [`math.sort()`](https://github.com/angular-package/sass/blob/develop/math/_math.sort.function.scss) function to sort numbers. [99484a6]
- Add [`meta.call-arglist()`](https://github.com/angular-package/sass/blob/develop/meta/_meta.call-arglist.function.scss) function to call functions with comma-separated list as arguments and space-separated as argument. [0c0b0a0]
- Add [`string.to-map()`](https://github.com/angular-package/sass/blob/develop/string/_string.to-map.function.scss) to transform `string` to `map` and [`string.unquote()`](https://github.com/angular-package/sass/blob/develop/string/_string.unquote.function.scss) to unquote on `$execute`.

- Add different(easier) **translator(1.0.0)** with global dictionary, not exported by default. [35b3663]
- Add **var** module with
  [`var.adjust()`](https://github.com/angular-package/sass/blob/develop/var/functions/_var.adjust.function.scss)
  [`var.css()`](https://github.com/angular-package/sass/blob/develop/var/functions/_var.css.function.scss)
  [`var.get()`](https://github.com/angular-package/sass/blob/develop/var/functions/_var.get.function.scss)
  [`var.is()`](https://github.com/angular-package/sass/blob/develop/var/functions/_var.is.function.scss)
  [`var.name()`](https://github.com/angular-package/sass/blob/develop/var/functions/_var.name.function.scss)
  [`var.negative()`](https://github.com/angular-package/sass/blob/develop/var/functions/_var.negative.function.scss) and
  [`var.unit()`](https://github.com/angular-package/sass/blob/develop/var/functions/_var.unit.function.scss) functions, and [`var.set()`](https://github.com/angular-package/sass/blob/develop/var/mixins/_var.set.mixin.scss) mixin. [16bdb40] [51f7f17] [d3ace9f]

- Update [`comparison.compare()`](https://github.com/angular-package/sass/blob/develop/comparison/_comparison.compare.function.scss) to indicate map length as deprecated. [3969b97]
- Update [`meta.of-type()`](https://github.com/angular-package/sass/blob/develop/meta/_meta.of-type.function.scss) function to handle multiple types. [cf31bb2]
- Update [`string.split()`](https://github.com/angular-package/sass/blob/develop/string/_string.split.function.scss) to have ability to unquote returned string, and separator as multiple words instead of only one character. [62c693c] [b8feda9] [d0f372d]
- Update [`values.combine()`](https://github.com/angular-package/sass/blob/develop/values/_values.combine.function.scss) by changing the way of providing parameters. [ab77370]

- Fix [`list.append()`](https://github.com/angular-package/sass/blob/develop/list/_list.append.function.scss) fix not proper adding `$val` space separated. [99c618b]
- Fix [`list.join()`](https://github.com/angular-package/sass/blob/develop/list/_list.join.function.scss) function to properly add bracketed. [928914a]
- Fix [`list.remove-list()`](https://github.com/angular-package/sass/blob/develop/list/remove/_remove.list.function.scss) change function name from not existing `has-type()` to `has.type()`. [b3b5d55]
- Fix [`map.pick-pattern()`](https://github.com/angular-package/sass/blob/develop/map/pick/_pick.pattern.function.scss) by updating use `string.replace()` function. [ab8263a]

[3969b97]: https://github.com/angular-package/sass/commit/3969b973927b1619fab342aa3246df7d58e65842
[ab77370]: https://github.com/angular-package/sass/commit/ab7737052ede08a4129d88f9a7f1cd1993331359
[99c618b]: https://github.com/angular-package/sass/commit/99c618b179a74e403bb40ad01330604ddbbd5272
[ab8263a]: https://github.com/angular-package/sass/commit/ab8263a58f612f809a1e77723a8302d6f4d81e47
[d3ace9f]: https://github.com/angular-package/sass/commit/d3ace9fc5e26ebd1fc2ce37486b32c6e0ec08374
[51f7f17]: https://github.com/angular-package/sass/commit/51f7f1789102ec09b9f80708467cc3e32e9b2f27
[35b3663]: https://github.com/angular-package/sass/commit/35b366323d20588896132f0f4e54a55d7847d1f5
[16bdb40]: https://github.com/angular-package/sass/commit/16bdb4044ab5e667a8f3802f490bf6775a25ec4a
[07e2904]: https://github.com/angular-package/sass/commit/07e2904edf8c26c282af8408e474db1e868bef26
[0c0b0a0]: https://github.com/angular-package/sass/commit/0c0b0a0bff083cc640cf2ff8bade3b4c222a1394
[8c27019]: https://github.com/angular-package/sass/commit/8c270193c210f2c8e7a8fa5173f992403c1ef43e
[1b37c23]: https://github.com/angular-package/sass/commit/1b37c23d13cd2f9c3ed60ecc508c13cadffa8f8d
[22f37e6]: https://github.com/angular-package/sass/commit/22f37e6689992048eb01e6befaea1fbfe0e5302f
[a165ed8]: https://github.com/angular-package/sass/commit/a165ed8203e5e052a22c4540a3eed121df80179e
[79dccba]: https://github.com/angular-package/sass/commit/79dccba17e90103c60271a1ce3996b4cf869df57
[d596d48]: https://github.com/angular-package/sass/commit/d596d482f1a6e712e8cef8dc2bb808986b2f7aa1
[c88c00a]: https://github.com/angular-package/sass/commit/c88c00a9cd686ef1046bf467b80c48155b0e1f1c
[a2ed250]: https://github.com/angular-package/sass/commit/a2ed2506a088bff09e43da8bbeef376fef270469
[01c830a]: https://github.com/angular-package/sass/commit/01c830a3a4b442111c5d1d91493747a740fb6f4d
[b51b22a]: https://github.com/angular-package/sass/commit/b51b22a5a5e38da0d54462355852c133f9b041da
[9a7fed7]: https://github.com/angular-package/sass/commit/9a7fed704ab33270413c0cb04c2e57b3c0e76ddd
[66fdaef]: https://github.com/angular-package/sass/commit/66fdaef21c69365c5d7fdfd8ea56d6adb1fc2e09
[928914a]: https://github.com/angular-package/sass/commit/928914a0ec051dcb5727d546230150a1b1767b56
[cf31bb2]: https://github.com/angular-package/sass/commit/cf31bb25ce0e3326cf11028bce30fca51bbd3019
[d0f372d]: https://github.com/angular-package/sass/commit/d0f372def4c1a22c58c4b6c8c07a78967d3e99d0
[b8feda9]: https://github.com/angular-package/sass/commit/b8feda9e994d35798dbd1197fae27df63d1ddcb9
[62c693c]: https://github.com/angular-package/sass/commit/62c693c88b44951a53f77a4c505f960b1b8c66ec
[99484a6]: https://github.com/angular-package/sass/commit/99484a63ae7ed23d8afde689a91e940ee10aad2c
[b3b5d55]: https://github.com/angular-package/sass/commit/b3b5d550234f4ed3d8d09d532874b22b070259fa
[5dbd420]: https://github.com/angular-package/sass/commit/5dbd4207fef1f05b84d29d56c20c17bd047e5871

### v0.3.0-beta [#](https://github.com/angular-package/sass/releases/tag/v0.3.0-beta)

- Add values module with a `combine()` function. [985370f]
- Add `map.retrieve()` function to unify get and pick. [2e72bd0]
- Add translate module and translator functions. [0ca2128] [8031d0d]
- Fix `dictionary.pick()` merging key with null of `$dictionary. [5735653]

Related commits: [5735653] [8031d0d]

[985370f]: https://github.com/angular-package/sass/commit/985370fd4cb323f4695a67c4ac2d77d84ed79afe
[2e72bd0]: https://github.com/angular-package/sass/commit/2e72bd0a1976941e7a51b1152199e0a0bb8d0aea
[8031d0d]: https://github.com/angular-package/sass/commit/8031d0de3e38135966b2a30b76761afffb31de24
[0ca2128]: https://github.com/angular-package/sass/commit/0ca2128f81f3ad8cf4d43d354105c2b2a150d6ac
[5735653]: https://github.com/angular-package/sass/commit/573565369a786b8272acc20a27218490ec72d30e
