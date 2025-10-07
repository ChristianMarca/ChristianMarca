## 👋 Hi, I'm Christian Marca  

> “I am an enthusiast of software engineering, and I flow with coding and software craft.”

🎓 Degree in Electrical Engineering from [Universidad Politécnica Salesiana](https://www.ups.edu.ec/)  

---

### 🧠 About me  

🇪🇨 Ecuadorian to the last fiber of my being — currently living in one of the smallest and prettiest places in the world.  

One of my strongest beliefs is that everything can be learned through practice.  
I consider myself an autodidact who enjoys exploring new technologies, languages, and creative disciplines.  

🪚 Lately, I’ve been diving into **carpentry**, balancing physical craft with digital creation — software engineering remains my lifelong passion.  

---

### 🌐 Connect with me  

<p align="left">
  <a href="mailto:cmarcag@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-c14438?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  <a href="mailto:cmarcag@hotmail.com">
    <img src="https://img.shields.io/badge/Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="Outlook"/>
  </a>
  <a href="https://www.linkedin.com/in/christianmarcag/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

---

### ⚙️ Software Engineering Mindset  

> I see technology as a medium of expression — tools evolve, principles endure.  

My focus is on **building reliable systems**, **clean architectures**, and **meaningful user experiences**.  
Whether it’s cloud infrastructure, web performance, or creative coding, I enjoy connecting technical depth with design clarity.  

---

### 🖤 A hint of code & craft  

```rust
fn optimize<T: AsRef<str>>(tasks: &[T]) -> Vec<String> {
    tasks
        .iter()
        .map(|t| format!("{} ✅", t.as_ref()))
        .collect()
}

fn main() {
    let backlog = ["sleep", "code", "debug", "repeat"];
    let done = optimize(&backlog);

    println!("Life optimized: {:?}", done);
}

#[cfg(test)]
mod tests {
    use super::*;

    #[test]
    fn test_life_is_stable() {
        let tasks = ["eat", "code", "sleep"];
        let result = optimize(&tasks);
        assert!(result.contains(&"code ✅".to_string()), "💡 life failed to optimize 'code'");
    }
}
