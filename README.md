<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

ਡਾਇਰੈਕਟਰੀ ਵਿੱਚ ਦਾਖਲ ਹੋਣ ਤੋਂ ਬਾਅਦ ਪਹਿਲਾਂ nodejs, [direnv](https://direnv.net) , [bun ਨੂੰ](https://github.com/oven-sh/bun) ਇੰਸਟਾਲ ਕਰਨ ਅਤੇ ਫਿਰ `direnv allow` ਦੀ ਸਿਫ਼ਾਰਸ਼ ਕੀਤੀ ਜਾਂਦੀ ਹੈ (ਡਾਇਰੈਕਟਰੀ ਵਿੱਚ ਦਾਖਲ ਹੋਣ ਤੋਂ ਬਾਅਦ [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) ਆਪਣੇ ਆਪ ਚਲਾਇਆ ਜਾਵੇਗਾ)।

ਅਰਥ ਹੈ: ਚੀਨੀ ਅਨੁਵਾਦ ਜਪਾਨੀ, ਕੋਰੀਅਨ, ਅੰਗਰੇਜ਼ੀ, ਹੋਰ ਸਾਰੀਆਂ ਭਾਸ਼ਾਵਾਂ ਵਿੱਚ ਅੰਗਰੇਜ਼ੀ ਅਨੁਵਾਦ। ਜੇਕਰ ਤੁਸੀਂ ਸਿਰਫ਼ ਚੀਨੀ ਅਤੇ ਅੰਗਰੇਜ਼ੀ ਦਾ ਸਮਰਥਨ ਕਰਨਾ ਚਾਹੁੰਦੇ ਹੋ, ਤਾਂ ਤੁਸੀਂ ਸਿਰਫ਼ `zh: en` ਲਿਖ ਸਕਦੇ ਹੋ।

ਅਰਥ ਹੈ: ਚੀਨੀ ਅਨੁਵਾਦ ਜਪਾਨੀ, ਕੋਰੀਅਨ, ਅੰਗਰੇਜ਼ੀ, ਹੋਰ ਸਾਰੀਆਂ ਭਾਸ਼ਾਵਾਂ ਵਿੱਚ ਅੰਗਰੇਜ਼ੀ ਅਨੁਵਾਦ। ਜੇਕਰ ਤੁਸੀਂ ਸਿਰਫ਼ ਚੀਨੀ ਅਤੇ ਅੰਗਰੇਜ਼ੀ ਦਾ ਸਮਰਥਨ ਕਰਨਾ ਚਾਹੁੰਦੇ ਹੋ, ਤਾਂ ਤੁਸੀਂ ਸਿਰਫ਼ `zh: en` ਲਿਖ ਸਕਦੇ ਹੋ।

* [ਫਰੰਟ-ਐਂਡ ਕੋਡ](https://github.com/xxai-art/web)
* [ਸਮੁੱਚੇ ਤੌਰ 'ਤੇ ਸਾਈਟ ਲਈ ਭਾਸ਼ਾ ਪੈਕ](https://github.com/xxai-art/web/tree/main/i18n)
* [ਲੌਗਇਨ ਮੋਡੀਊਲ ਲਈ ਭਾਸ਼ਾ ਪੈਕ](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [ਵੈੱਬਸਾਈਟ ਬਹੁ-ਭਾਸ਼ਾਈ ਦਸਤਾਵੇਜ਼](https://github.com/xxai-doc)

ਫਰੰਟ-ਐਂਡ ਪ੍ਰੋਗਰਾਮਿੰਗ ਭਾਸ਼ਾ [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) ਹੈ, ਜੋ ਕਿ ਕੌਫੀ ਸਕ੍ਰਿਪਟ ਸੰਟੈਕਸ ਦੇ ਆਧਾਰ 'ਤੇ ਕੁਝ ਵਿਸ਼ੇਸ਼ਤਾਵਾਂ ਜੋੜਦੀ ਹੈ, ਦੇਖੋ [./coffee_plus.md](./coffee_plus.md) ।

## ਵੈੱਬਸਾਈਟਾਂ ਅਤੇ ਦਸਤਾਵੇਜ਼ਾਂ ਦਾ ਅੰਤਰਰਾਸ਼ਟਰੀਕਰਨ

ਹੇਠਾਂ ਦਿੱਤੇ 3 ਪ੍ਰੋਜੈਕਟਾਂ 'ਤੇ ਬਣਾਓ

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  ਪਿਛੇਤਰ `.mdt` ਹੈ, ਤੁਸੀਂ ਬਾਹਰੀ ਫਾਈਲਾਂ ਦਾ ਹਵਾਲਾ ਦੇਣ ਲਈ `<+ ./coffee_plus/import.js>` ਦੇ ਸਮਾਨ ਸੰਟੈਕਸ ਦੀ ਵਰਤੋਂ ਕਰ ਸਕਦੇ ਹੋ, ਅਤੇ ਪਿਛੇਤਰ ਨਾਲ ਮਾਰਕਡਾਊਨ ਤਿਆਰ ਕਰ ਸਕਦੇ ਹੋ `.md` .

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  ਮਾਰਕਡਾਊਨ ਅਨੁਵਾਦ ਕੋਡਾਂ ਅਤੇ ਲਿੰਕਾਂ ਦਾ ਅਨੁਵਾਦ ਨਹੀਂ ਕਰੇਗਾ, ਅਤੇ ਅਨੁਵਾਦਿਤ ਵਾਕਾਂ ਨੂੰ ਕੈਸ਼ ਕਰੇਗਾ। ਜੇਕਰ ਅਨੁਵਾਦ ਸੰਸ਼ੋਧਿਤ ਕੀਤਾ ਗਿਆ ਹੈ ਪਰ ਮੂਲ ਪਾਠ ਨੂੰ ਸੋਧਿਆ ਨਹੀਂ ਗਿਆ ਹੈ, ਤਾਂ ਇਸਨੂੰ ਦੁਬਾਰਾ ਚਲਾਉਣ ਨਾਲ ਅਨੁਵਾਦ ਦੀ ਸੋਧ ਨੂੰ ਓਵਰਰਾਈਟ ਨਹੀਂ ਕੀਤਾ ਜਾਵੇਗਾ।

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  `yaml` ਦੁਆਰਾ ਤਿਆਰ ਕੀਤੀਆਂ ਵੈੱਬਸਾਈਟਾਂ ਦਾ ਅਨੁਵਾਦ ਕਰਨ ਲਈ ਭਾਸ਼ਾ ਫਾਈਲਾਂ।

### ਦਸਤਾਵੇਜ਼ ਅਨੁਵਾਦ ਆਟੋਮੇਸ਼ਨ ਨਿਰਦੇਸ਼

ਕੋਡ ਰਿਪੋਜ਼ਟਰੀ [xxai-art/doc](https://github.com/xxai-art/doc) ਵੇਖੋ

ਡਾਇਰੈਕਟਰੀ ਵਿੱਚ ਦਾਖਲ ਹੋਣ ਤੋਂ ਬਾਅਦ ਪਹਿਲਾਂ nodejs, [direnv](https://direnv.net) , [bun ਨੂੰ](https://github.com/oven-sh/bun) ਇੰਸਟਾਲ ਕਰਨ ਅਤੇ ਫਿਰ `direnv allow` ਦੀ ਸਿਫ਼ਾਰਸ਼ ਕੀਤੀ ਜਾਂਦੀ ਹੈ (ਡਾਇਰੈਕਟਰੀ ਵਿੱਚ ਦਾਖਲ ਹੋਣ ਤੋਂ ਬਾਅਦ [.envrc](https://github.com/xxai-art/doc/blob/main/.envrc) ਆਪਣੇ ਆਪ ਚਲਾਇਆ ਜਾਵੇਗਾ)।

ਸੈਂਕੜੇ ਭਾਸ਼ਾਵਾਂ ਵਿੱਚ ਅਨੁਵਾਦ ਕੀਤੇ ਗਏ ਵੱਡੇ ਕੋਡ ਬੇਸ ਤੋਂ ਬਚਣ ਲਈ, ਮੈਂ ਹਰੇਕ ਭਾਸ਼ਾ ਲਈ ਇੱਕ ਵੱਖਰਾ ਕੋਡ ਅਧਾਰ ਬਣਾਇਆ ਅਤੇ ਕੋਡ ਅਧਾਰ ਨੂੰ ਸਟੋਰ ਕਰਨ ਲਈ ਇੱਕ ਸੰਗਠਨ ਬਣਾਇਆ।

ਵਾਤਾਵਰਣ ਵੇਰੀਏਬਲ `GITHUB_ACCESS_TOKEN` ਸੈੱਟ ਕਰਨਾ ਅਤੇ ਫਿਰ [create.github.coffee](https://github.com/xxai-art/doc/blob/main/create.github.coffee) ਚਲਾਉਣਾ ਆਪਣੇ ਆਪ ਕੋਡ ਰਿਪੋਜ਼ਟਰੀ ਬਣਾ ਦੇਵੇਗਾ।

ਬੇਸ਼ੱਕ, ਤੁਸੀਂ ਇਸਨੂੰ ਕੋਡ ਬੇਸ ਵਿੱਚ ਵੀ ਪਾ ਸਕਦੇ ਹੋ.

ਅਨੁਵਾਦ ਸਕ੍ਰਿਪਟ ਹਵਾਲਾ [run.sh](https://github.com/xxai-art/doc/blob/main/run.sh)

ਸਕ੍ਰਿਪਟ ਕੋਡ ਦੀ ਵਿਆਖਿਆ ਇਸ ਤਰ੍ਹਾਂ ਕੀਤੀ ਗਈ ਹੈ:

[bunx](https://bun.sh/docs/cli/bunx) npx ਦਾ ਬਦਲ ਹੈ, ਜੋ ਕਿ ਤੇਜ਼ ਹੈ। ਬੇਸ਼ੱਕ, ਜੇਕਰ ਤੁਹਾਡੇ ਕੋਲ ਬਨ ਸਥਾਪਤ ਨਹੀਂ ਹੈ, ਤਾਂ ਤੁਸੀਂ ਇਸਦੀ ਬਜਾਏ `npx` ਦੀ ਵਰਤੋਂ ਕਰ ਸਕਦੇ ਹੋ।

`bunx mdt zh` `.mdt` ਨੂੰ zh ਡਾਇਰੈਕਟਰੀ ਵਿੱਚ `.md` ਦੇ ਰੂਪ ਵਿੱਚ ਰੈਂਡਰ ਕਰਦਾ ਹੈ, ਹੇਠਾਂ 2 ਲਿੰਕ ਕੀਤੀਆਂ ਫਾਈਲਾਂ ਵੇਖੋ

* [coffee_plus.mdt](https://github.com/xxai-doc/zh/blob/main/coffee_plus.mdt)
* [coffee_plus.md](https://github.com/xxai-doc/zh/blob/main/coffee_plus.md)

`bunx i18n` ਅਨੁਵਾਦ ਲਈ ਕੋਰ ਕੋਡ ਹੈ (ਜੇਕਰ ਤੁਹਾਡੇ ਕੋਲ ਸਿਰਫ `nodejs` ਸਥਾਪਿਤ ਹਨ, ਪਰ `bun` ਅਤੇ `direnv` ਇੰਸਟਾਲ ਨਹੀਂ ਹਨ, ਤਾਂ ਤੁਸੀਂ ਅਨੁਵਾਦ ਕਰਨ ਲਈ `npx i18n` ਵੀ ਚਲਾ ਸਕਦੇ ਹੋ)।

ਇਹ [i18n.yml ਨੂੰ](https://github.com/xxai-art/doc/blob/main/i18n.yml) ਪਾਰਸ ਕਰੇਗਾ, ਇਸ ਦਸਤਾਵੇਜ਼ ਵਿੱਚ `i18n.yml` ਦੀ ਸੰਰਚਨਾ ਇਸ ਤਰ੍ਹਾਂ ਹੈ:

```
en:
zh: ja ko en
```

ਅਰਥ ਹੈ: ਚੀਨੀ ਅਨੁਵਾਦ ਜਪਾਨੀ, ਕੋਰੀਅਨ, ਅੰਗਰੇਜ਼ੀ, ਹੋਰ ਸਾਰੀਆਂ ਭਾਸ਼ਾਵਾਂ ਵਿੱਚ ਅੰਗਰੇਜ਼ੀ ਅਨੁਵਾਦ। ਜੇਕਰ ਤੁਸੀਂ ਸਿਰਫ਼ ਚੀਨੀ ਅਤੇ ਅੰਗਰੇਜ਼ੀ ਦਾ ਸਮਰਥਨ ਕਰਨਾ ਚਾਹੁੰਦੇ ਹੋ, ਤਾਂ ਤੁਸੀਂ ਸਿਰਫ਼ `zh: en` ਲਿਖ ਸਕਦੇ ਹੋ।

ਆਖਰੀ [gen.README.coffee](https://github.com/xxai-art/doc/blob/main/gen.README.coffee) ਹੈ, ਜੋ ਕਿ ਇੱਕ ਐਂਟਰੀ `README.md` ਬਣਾਉਣ ਲਈ ਮੁੱਖ ਸਿਰਲੇਖ ਅਤੇ ਹਰੇਕ ਭਾਸ਼ਾ ਦੇ `README.md` ਦੇ ਪਹਿਲੇ ਉਪਸਿਰਲੇਖ ਦੇ ਵਿਚਕਾਰ ਸਮੱਗਰੀ ਨੂੰ ਐਕਸਟਰੈਕਟ ਕਰਦਾ ਹੈ। ਕੋਡ ਬਹੁਤ ਸਧਾਰਨ ਹੈ, ਤੁਸੀਂ ਇਸਨੂੰ ਆਪਣੇ ਆਪ ਦੇਖ ਸਕਦੇ ਹੋ.

Google API ਦੀ ਵਰਤੋਂ ਮੁਫ਼ਤ ਅਨੁਵਾਦ ਲਈ ਕੀਤੀ ਜਾਂਦੀ ਹੈ। ਜੇਕਰ ਤੁਸੀਂ Google ਤੱਕ ਨਹੀਂ ਪਹੁੰਚ ਸਕਦੇ ਹੋ, ਤਾਂ ਕਿਰਪਾ ਕਰਕੇ ਇੱਕ ਪ੍ਰੌਕਸੀ ਕੌਂਫਿਗਰ ਕਰੋ ਅਤੇ ਸੈਟ ਕਰੋ, ਜਿਵੇਂ ਕਿ:

```
export https_proxy=http://127.0.0.1:7890 http_proxy=http://127.0.0.1:7890 all_proxy=socks5://127.0.0.1:7890
```

ਅਨੁਵਾਦ ਸਕ੍ਰਿਪਟ `.i18n` ਡਾਇਰੈਕਟਰੀ ਵਿੱਚ ਇੱਕ ਅਨੁਵਾਦਿਤ ਕੈਸ਼ ਤਿਆਰ ਕਰੇਗੀ, ਕਿਰਪਾ ਕਰਕੇ ਇਸਨੂੰ `git status` ਨਾਲ ਚੈੱਕ ਕਰੋ ਅਤੇ ਦੁਹਰਾਉਣ ਵਾਲੇ ਅਨੁਵਾਦਾਂ ਤੋਂ ਬਚਣ ਲਈ ਇਸਨੂੰ ਕੋਡ ਰਿਪੋਜ਼ਟਰੀ ਵਿੱਚ ਸ਼ਾਮਲ ਕਰੋ।

ਕਿਰਪਾ ਕਰਕੇ ਹਰ ਵਾਰ ਜਦੋਂ ਤੁਸੀਂ ਕੈਸ਼ ਨੂੰ ਅਪਡੇਟ ਕਰਨ ਲਈ ਅਨੁਵਾਦ ਨੂੰ ਸੋਧਦੇ ਹੋ ਤਾਂ `bunx i18n` ਚਲਾਓ।

ਜੇਕਰ ਮੂਲ ਪਾਠ ਅਤੇ ਅਨੁਵਾਦ ਇੱਕੋ ਸਮੇਂ ਵਿੱਚ ਸੋਧਿਆ ਜਾਂਦਾ ਹੈ, ਤਾਂ ਕੈਸ਼ ਉਲਝਣ ਵਿੱਚ ਪੈ ਜਾਵੇਗਾ, ਇਸ ਲਈ ਜੇਕਰ ਤੁਸੀਂ ਸੋਧਣਾ ਚਾਹੁੰਦੇ ਹੋ, ਤਾਂ ਤੁਸੀਂ ਸਿਰਫ਼ ਇੱਕ ਨੂੰ ਸੋਧ ਸਕਦੇ ਹੋ, ਅਤੇ ਫਿਰ ਕੈਸ਼ ਨੂੰ ਅੱਪਡੇਟ ਕਰਨ ਲਈ `bunx i18n` ਚਲਾ ਸਕਦੇ ਹੋ।
