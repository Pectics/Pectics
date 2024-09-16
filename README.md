### Hi there, I'm Pectics! 👋

```java
package com.peckot.pectics;

class Pectics {
  List<String> personalities = new ArrayList<>();
  List<Object> interests = new ArrayList<>();
  static {
    for (String lang : new String[] {
      "Java",       "JavaScript",
      "TypeScript", "Vue3",
    }) {
      interests.add(new Language(lang));
    }

    for (String game : new String[] {
      "Minecraft", "Phigros", "Arcaea",
      "Cytus II",  "Malody",  "Rizline",
      "UNDERTALE", "Counter-Strike: Global Offensive"
    }) {
      interests.add(new Game(game));
    }

    personalities.add("🕊️🕊️🕊️🕊️🕊️");
  }

}
```

### 我的 Github 数据

![Pectics' Github Stats](https://github-readme-stats.vercel.app/api?username=Pectics&include_all_commits=true&locale=cn&hide=stars&theme=tokyonight)
