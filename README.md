<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) පළමුව ස්ථාපනය කිරීම රෙකමදාරු කරනු ලැබේ, ඩිරෙක්ටරියට ඇතුළු වූ පසු `direnv allow` ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) ඩිරෙක්ටරියට ඇතුළු වූ පසු ස්වයංක්‍රීයව ක්‍රියාත්මක වේ).

තේරුම: ජපන්, කොරියානු, ඉංග්‍රීසි, ඉංග්‍රීසි භාෂාවට චීන පරිවර්තනය, අනෙකුත් සියලුම භාෂාවලට පරිවර්තනය. ඔබට චීන සහ ඉංග්‍රීසි සහය දැක්වීමට පමණක් අවශ්‍ය නම්, ඔබට ලිවිය හැක්කේ `zh: en` .

තේරුම: ජපන්, කොරියානු, ඉංග්‍රීසි, ඉංග්‍රීසි භාෂාවට චීන පරිවර්තනය, අනෙකුත් සියලුම භාෂාවලට පරිවර්තනය. ඔබට චීන සහ ඉංග්‍රීසි සහය දැක්වීමට පමණක් අවශ්‍ය නම්, ඔබට ලිවිය හැක්කේ `zh: en` .

* [ඉදිරිපස කේතය](https://github.com/xxai-art/web)
* [සමස්තයක් ලෙස වෙබ් අඩවිය සඳහා භාෂා ඇසුරුම්](https://github.com/xxai-art/web/tree/main/i18n)
* [පිවිසුම් මොඩියුල සඳහා භාෂා ඇසුරුම්](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [වෙබ් අඩවිය බහුභාෂා ලේඛනගත කිරීම](https://github.com/xxai-doc)

ඉදිරිපස ක්‍රමලේඛන භාෂාව [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) වේ, එය කෝපි ස්ක්‍රිප්ට් වාක්‍ය ඛණ්ඩය මත පදනම්ව සමහර විශේෂාංග එකතු කරයි, බලන්න [./coffee_plus.md](./coffee_plus.md) .

## වෙබ් අඩවි සහ ලේඛන ජාත්‍යන්තරකරණය

පහත ව්‍යාපෘති 3 මත ගොඩනඟන්න

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  උපසර්ගය `.mdt` වේ, ඔබට බාහිර ගොනු වෙත යොමු කිරීමට `<+ ./coffee_plus/import.js>` ට සමාන වාක්‍ය ඛණ්ඩය භාවිතා කළ හැක, සහ `.md` උපසර්ගය සමඟ සලකුණු ජනනය කළ හැක.

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  Markdown පරිවර්තනය කේත සහ සබැඳි පරිවර්තනය නොකරන අතර පරිවර්තන වාක්‍ය හැඹිලි කරනු ඇත. පරිවර්තනය වෙනස් කර ඇති නමුත් මුල් පිටපත වෙනස් කර නොමැති නම්, එය නැවත ක්‍රියාත්මක කිරීමෙන් පරිවර්තනය වෙනස් කිරීම උඩින් ලියැවෙන්නේ නැත.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  `yaml` ජනනය කරන ලද වෙබ් අඩවි පරිවර්තනය කිරීම සඳහා භාෂා ගොනු.

### ලේඛන පරිවර්තන ස්වයංක්‍රීයකරණ උපදෙස්

කේත ගබඩාව [xxai-art/doc](https://github.com/xxai-art/doc) බලන්න

nodejs, [direnv](https://direnv.net) , [bun](https://github.com/oven-sh/bun) පළමුව ස්ථාපනය කිරීම රෙකමදාරු කරනු ලැබේ, ඩිරෙක්ටරියට ඇතුළු වූ පසු `direnv allow` ( [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) ඩිරෙක්ටරියට ඇතුළු වූ පසු ස්වයංක්‍රීයව ක්‍රියාත්මක වේ).

භාෂා සිය ගණනකට පරිවර්තනය කර ඇති විශාල කේත පදනම වළක්වා ගැනීම සඳහා, මම එක් එක් භාෂාව සඳහා වෙනම කේත පදනමක් නිර්මාණය කර කේත පදනම ගබඩා කිරීම සඳහා සංවිධානයක් නිර්මාණය කළෙමි.

`GITHUB_ACCESS_TOKEN` පරිසර විචල්‍යය සැකසීමෙන් අනතුරුව [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) ධාවනය කිරීම ස්වයංක්‍රීයව කේත ගබඩාව සාදනු ඇත.

ඇත්ත වශයෙන්ම, ඔබට එය කේත පදනමක තැබිය හැකිය.

පරිවර්තන ස්ක්‍රිප්ට් යොමුව [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

ස්ක්‍රිප්ට් කේතය පහත පරිදි අර්ථ දැක්වේ:

[bunx](https://bun.sh/docs/cli/bunx) යනු npx සඳහා ආදේශකයකි, එය වේගවත් වේ. ඇත්ත වශයෙන්ම, ඔබ ස්ථාපනය කර නොමැති නම්, ඔබට ඒ වෙනුවට `npx` භාවිතා කළ හැකිය.

`bunx mdt zh` විදැහුම්කරණය `.mdt` ලෙස zh නාමාවලියෙහි `.md` ලෙස, පහත සබැඳි ගොනු 2 බලන්න

* [කෝපි_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [කෝපි_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` යනු පරිවර්තනය සඳහා මූලික කේතය වේ (ඔබ ස්ථාපනය කර ඇත්තේ `nodejs` පමණක් නම්, නමුත් `bun` සහ `direnv` ස්ථාපනය කර නොමැති නම්, ඔබට පරිවර්තනය කිරීමට `npx i18n` ධාවනය කළ හැක).

එය [i18n.yml](https://github.com/xxai-art/doc/blob/main/i18n.yml) විග්‍රහ කරනු ඇත, මෙම ලේඛනයේ `i18n.yml` හි වින්‍යාසය පහත පරිදි වේ:

```
en:
zh: ja ko en
```

තේරුම: ජපන්, කොරියානු, ඉංග්‍රීසි, ඉංග්‍රීසි භාෂාවට චීන පරිවර්තනය, අනෙකුත් සියලුම භාෂාවලට පරිවර්තනය. ඔබට චීන සහ ඉංග්‍රීසි සහය දැක්වීමට පමණක් අවශ්‍ය නම්, ඔබට ලිවිය හැක්කේ `zh: en` .

අවසාන එක [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) , එය එක් `README.md` `README.md` ජනනය කිරීම සඳහා ප්‍රධාන මාතෘකාව සහ පළමු උපසිරැසි අතර අන්තර්ගතය උපුටා ගනී. කේතය ඉතා සරලයි, ඔබට එය ඔබම බැලිය හැකිය.

Google API නොමිලේ පරිවර්තනය සඳහා භාවිතා වේ. ඔබට Google වෙත ප්‍රවේශ විය නොහැකි නම්, කරුණාකර ප්‍රොක්සියක් වින්‍යාස කර සකසන්න, වැනි:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

පරිවර්තන ස්ක්‍රිප්ටය `.i18n` බහලුම තුළ පරිවර්තිත හැඹිලියක් ජනනය කරනු ඇත, කරුණාකර එය `git status` සමඟ පරීක්ෂා කර නැවත නැවත පරිවර්තන වැළැක්වීම සඳහා එය කේත ගබඩාවට එක් කරන්න.

ඔබ හැඹිලිය යාවත්කාලීන කිරීමට පරිවර්තනය වෙනස් කරන සෑම අවස්ථාවකම කරුණාකර `bunx i18n` ධාවනය කරන්න.

මුල් පිටපත සහ පරිවර්තනය එකවර වෙනස් කළහොත්, හැඹිලිය ව්‍යාකූල වනු ඇත, එබැවින් ඔබට වෙනස් කිරීමට අවශ්‍ය නම්, ඔබට එකක් පමණක් වෙනස් කළ හැකිය, පසුව හැඹිලිය යාවත්කාලීන කිරීමට `bunx i18n` ධාවනය කරන්න.
