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
			"Golang", "Microservices", "AWS",
			"Elasticsearch", "Kafka", "Redis",
			"Dart", "Flutter", "MongoDB", "RabbitMQ",
		},
	}

	fmt.Println("Building scalable systems & optimizing existing core systems...")
	fmt.Printf("%#v\n", me)
}

```
<img src="https://cdn.dribbble.com/userupload/29993010/file/original-1c72d566914d606774a9a5b40e4d95df.jpg?resize=2048x1456&vertical=center" width="100%" align="center"/>

