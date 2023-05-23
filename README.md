<!-- **garbalau-github/garbalau-github** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile. -->
```rust
struct Developer {
    name: String,
    hobbies: Vec<String>
}

impl Developer {
    fn greet(&self) {
        println!("Hi, my name is {}!", self.name);
        println!("I am interesed in: ");
        for hobby in &self.hobbies {
            println!("- {}", hobby);
        }
    } 
}

fn main() {
    let nick = Developer {
        name: String::from("Nick"),
        hobbies: vec![
            String::from("Computer Science"), 
            String::from("Electrification"), 
            String::from("Clean Energy"), 
            String::from("Astronomy")
        ]
    };
    nick.greet();
}
```
![Profile views](https://komarev.com/ghpvc/?username=garbalau-github&color=green)
