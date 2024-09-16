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
