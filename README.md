### Hi there, I'm Pectics! 👋

```
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

### My GitHub Stat 🤩

![Pectics' github stat](https://github-readme-stats.vercel.app/api?username=Pectics&hide_border=true&hide=prs&show_icons=true&include_all_commits=true&text_color=B9D2F6&bg_color=DEG,461F49,323A90&theme=prussian&locale=cn)
