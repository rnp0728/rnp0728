```go

package main

import "fmt"

type Developer struct {
	Name     string
	Role     string
	Location string
	Skills   []string
}

func main() {
	me := Developer{
		Name:     "Rudra Narayan Panda 👋",
		Role:     "Software Engineer",
		Location: "Odisha, India",
		Skills: []string{
			"Java", "Spring", "SpringBoot", "Hibernate",
			"Golang", "Microservices", "AWS",
			"Elasticsearch", "Kafka", "Redis",
			"Dart", "Flutter", "MongoDB", "RabbitMQ"
		},
	}

	fmt.Println("Building scalable systems & optimizing existing core systems...")
	fmt.Printf("%#v\n", me)
}

```

