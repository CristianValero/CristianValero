​<a href="https://twitter.com/titianvalero/" target="blank"><img src="https://img.shields.io/twitter/follow/titianvalero?logo=twitter&style=for-the-badge" alt="titianvalero" /></a> 

- 📫 How to contact me: pauitopauito03@gmail.com

```java
public class CristianValero extends GitHubUser {

  public CristianValero() {
    super("CristianValero", "Spain");

    this.addLanguage("Java", "Python", "Javascript", "CSS", "PHP", "Arduino");
    this.addExperience("UJI", "CFGS DAM");
  }
}

public abstract class GitHubUser {

  @Getter private final String username;
  @Getter private final String country;

  private Set<String> languages = new HashSet<>();
  private Set<String> experiences = new HashSet<>();

  public GitHubUser(String username, String country) {
      this.name = username;
      this.country = country;
  }

  public void addLanguage(String... language) {
      this.languages.addAll(language);
  }
  
  public void addExperience(String... experience) {
      this.experiences.addAll(experience);
  }
}
```
​<a href="https://twitter.com/titianvalero/" target="blank"><img src="https://github-readme-stats.vercel.app/api?username=CristianValero&show_icons=true&theme=radical"></a> 
