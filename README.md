## Hey! I'm DatCodeMania!

```java
import java.util.ArrayList;

public class DatCodeMania {
    private String name;
    private int age;
    private String occupation;
    private ArrayList<String> programming_langs;
    private ArrayList<String> human_langs;

    public DatCodeMania() {
        this.name = "Full name redacted as I'm worried about a few nasty" +
                    " things such as doxing/swatting.";
        this.age = 15;
        this.occupation = "High school student, pursuing Computer Science.";

        this.programming_langs = new ArrayList<String>();
        programming_langs.add("Python - Intermediate");
        programming_langs.add("Java - Beginner-Intermediate");
        programming_langs.add("C++ - Beginner");

        this.human_langs = new ArrayList<String>();
        human_langs.add("English - fluent");
        human_langs.add("Russian - fluent");
        human_langs.add("German - fluent");
        human_langs.add("Spanish - studying - intermediate");
        human_langs.add("Mandarin - studying - beginner");
    }
}
```
