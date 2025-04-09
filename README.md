```go
func main() {
	me := struct {
		Name            string
		Website         string
		Occupation      string
		ProgrammingLang map[string]string
		HumanLang       map[string]string
		Affiliations    []string
		TechStuff       []string
		OtherStuff      []string
		PastProjects    []string
	}{
		Name:     "DatCodeMania",
		Website:  "https://codemania.dev",
		Occupation: "High school student, aspiring software engineer 👨‍💻",

		ProgrammingLang: map[string]string{
			"Python": "Intermediate",
			"Java":   "Beginner–Intermediate",
			"Go":     "Beginner",
		},

		HumanLang: map[string]string{
			"English 🇺🇸": "Fluent",
			"Russian 🇷🇺": "Fluent",
			"German 🇩🇪":  "Fluent",
			"Spanish 🇪🇸": "Intermediate (learning)",
		},

		Affiliations: []string{
			"Hack Club (https://hackclub.com) Leader 🚀",
		},

		TechStuff: []string{
			"I use Arch btw 🐧",
			"Daily driving a ThinkPad",
		},

		OtherStuff: []string{
			"🎷🏀🎾🏋️",
		},

		PastProjects: []string{
			"Built and ran large-scale online game servers.",
			"Built stealthy mod loaders using JNI and deep JVM internals.",
			"Developed mods and plugins for Minecraft,"
			"... both personal and commissioned.",
		}
	}
}
```
