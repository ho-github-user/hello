hello world
=====

test

```
// サンプル１
// test problamming
foreach(var language in GetLanguages()) {
  Console.WriteLine(language + " is programming langage.");
}

function IEnumerable<string> GetLanguages() {
  return new {"Java", "php", "c sharp"};
}
```

```
/// プログラム言語の情報を保持する
class ProgramLanguage {
  public string Name { get; set; };
  public bool IsScript { get; set; };
}
```
