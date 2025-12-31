# Hi there, I'm Rudra! 👋

<p align="left">
<img src="https://github.com/egonelbre/gophers/raw/master/.thumb/vector/adventure/hiking.png" width="150" align="right" />
Software Engineer from Odisha, India, specializing in building high-performance distributed systems with Go. 
</p>

```go
package main

import "fmt"

type Developer struct {
    Name     string
    Role     string
    Location string
    Skills     []string
}

func main() {
    me := Developer{
        Name:     "Rudra Narayan Panda",
        Role:     "Software Engineer",
        Location: "Odisha, India",
        Skills: []string{
            "Golang", "Microservices", "AWS",
            "Elasticsearch", "Kafka", "Redis",
            "Dart", "Flutter", "MongoDB", "RabbitMQ"
        },
    }

    fmt.Printf("Building scalable systems as %s", me.Role)
}
```
