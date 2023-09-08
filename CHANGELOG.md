# @angular-package/sass changelog

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
