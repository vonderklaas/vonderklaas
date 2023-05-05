<!-- **garbalau-github/garbalau-github** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile. -->
```rust
struct Developer {
    age: u8,
    name: String,
    hobbies: Vec<String>
}

impl Developer {
    fn greet(&self) {
        println!("Hi, my name is {} and I'm {} years old.", self.name, self.age);
        println!("I am interesed in: ");
        for hobby in &self.hobbies {
            println!("- {}", hobby);
        }
    } 
}

fn main() {
    let nick = Developer {
        age: 25,
        name: String::from("Nick"),
        hobbies: vec![
            String::from("Computers"), 
            String::from("Physics"), 
            String::from("Astronomy")
        ]
    };
    nick.greet();
}
```
![Profile views](https://komarev.com/ghpvc/?username=garbalau-github&color=green)
