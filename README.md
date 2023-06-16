<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

# xxAI.art

ਵੈੱਬਸਾਈਟ ਕੋਡ ਦਾ ਹਿੱਸਾ ਓਪਨ ਸੋਰਸ ਹੈ, ਅਨੁਵਾਦ ਨੂੰ ਅਨੁਕੂਲ ਬਣਾਉਣ ਵਿੱਚ ਮਦਦ ਕਰਨ ਲਈ ਤੁਹਾਡਾ ਸੁਆਗਤ ਹੈ।

## ਫਰੰਟ-ਐਂਡ ਕੋਡ

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
