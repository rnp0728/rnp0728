```rust

#[derive(Debug)]
struct Developer {
    name: &'static str,
    role: &'static str,
    location: &'static str,
    core_stack: Vec<&'static str>,
    exploring: Vec<&'static str>,
    interests: Vec<&'static str>,
}

fn main() {
    let me = Developer {
        name: "Rudra Narayan Panda 👋",
        role: "Software Engineer — curious about what happens under the hood",
        location: "Odisha, India",

        core_stack: vec![
            "Java",
            "Spring Boot",
            "Hibernate",
            "Microservices",
            "AWS",
            "PostgreSQL",
            "MongoDB",
            "Redis",
            "Kafka",
            "RabbitMQ",
            "Elasticsearch",
            "Datadog",
        ],

        exploring: vec![
            "Rust",
            "Database Internals",
            "Apache Cassandra",
            "Surreal DB",
            "Distributed Systems",
        ],

        interests: vec![
            "Scalable Systems",
            "System Design",
            "Performance Engineering",
            "Backend Engineering",
        ],
    };

    println!(
        "Building scalable systems, understanding how they work, \
         and making existing systems better."
    );

    println!("{:#?}", me);
}

```

