# Arthur Danielian

<h2 align="center">About me</h2>

```golang
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:":                    "A kind of traveler-foodLover-gamer-coder-programmer",
		"- 🔭 I’m currently working on":      "WWW as a Web Developer",
		"- 🌱 I’m currently learning":        "System Design",
		"- 👯 I’m looking to collaborate on": "PHP, Python, Golang and Docker related projects",
		"- 💬 Ask me about":                  "Python, PHP, Laravel, SQL, Software Design & Architecture, Web-Dev",
		"- 📫 How to reach me:":              "https://github.com/quansho#you-can-reach-me-at-alien",
	}
}
```
