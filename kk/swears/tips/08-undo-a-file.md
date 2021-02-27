---
tags: tip
title: Білә, маған файлдағы өзгерісті болдырмау керек!
id: өзгерісті-болдырмау
order: 8
---

```git
# қайтару керек коммиттің хешін табыңыз
git log
# скролл қолдану арқылы коммиттерді көре аласыз
# керек коммиттің хешін сақтаңыз
git checkout [сақталған хеш] -- файлға/апарар/жол
# файлдың соңғы версиясы сіздің индексіңізде пайда болады
git commit -m "Еееее, енді өзгерістерді болдырмау үшін маған копи паст жасаудың керегі жоқ!"
```

Осыған басым жеткен кезде ХУЕТЬ етіп қалдым. Ебать охуенный осы фича. Бірақ шыны керек, өзгерістерді болдырмайтын `checkout --` командасы сәл ыңғайсыздау. :линус-торвальдсқа-қолы-қышып-тұр: