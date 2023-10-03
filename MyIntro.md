program Introduction {
    name: "Shubham Sarangi";
    age: 18;
    location: "Bhubaneswar,Odisha India";
    occupation: "Student";
    
    interests: [
        "Programming",
        "Artificial Intelligence",
        "Skating",
        "CODM",
        "Cycling"
    ];

    print("Hello, I'm " + name + "!");
    print("I'm  " + age + "-year-old " + occupation + " from " + location + ".");
    print("Some of my interests include:");

    for interest in interests {
        print("- " + interest);
    }

    print("I'm excited to be here and looking forward to engaging with you all!");
}

