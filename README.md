```java
public class GilvanPedro {

    /*
     * ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
     *  ABOUT ME
     * ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
     */

    private final String name     = "Gilvan Pedro";
    private final int age         = 19;
    private final String country  = "Brazil";

    private final String role     = "Back-end Developer";
    private final String college  = "Software Engineering @ SENAI Goiás";

    private final boolean availableForWork = true;

    /*
     * ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
     *  TECH STACK
     * ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
     */

    private final String[] languages = {
            "Java",
            "Python",
            "JavaScript",
            "SQL"
    };

    private final String[] backend = {
            "Spring Boot",
            "Hibernate",
            "REST APIs"
    };

    private final String[] database = {
            "MySQL",
            "PostgreSQL"
    };

    private final String[] tools = {
            "Git",
            "Docker",
            "IntelliJ IDEA",
            "VS Code",
            "Linux"
    };

    private final String[] currentlyLearning = {
            "AWS",
            "Microservices",
            "Clean Architecture",
            "Kotlin"
    };

    /*
     * ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
     *  SOCIALS
     * ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
     */

    private final String github   = "github.com/GilvanPedro";
    private final String linkedin = "linkedin.com/in/gilvannp";
    private final String instagram = "instagram.com/gilvan_.pedro";

    /*
     * ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
     *  METHODS
     * ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
     */

    public String aboutMe() {
        return """
                Passionate about technology, programming and problem solving.
                Focused on back-end development and always improving my skills.
                """;
    }

    public String currentGoal() {
        return "Building scalable and efficient applications.";
    }

    public String[] hobbies() {
        return new String[] {
                "Programming",
                "Gaming",
                "Reading",
                "Music"
        };
    }

    public String status() {
        return availableForWork
                ? "🟢 Open to opportunities"
                : "🔴 Currently busy";
    }

    public void printStack() {

        System.out.println("💻 Languages:");
        for (String language : languages) {
            System.out.println(" - " + language);
        }

        System.out.println("\n⚙️ Backend:");
        for (String tech : backend) {
            System.out.println(" - " + tech);
        }
    }

    /*
     * ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
     *  MAIN
     * ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
     */

    public static void main(String[] args) {

        GilvanPedro dev = new GilvanPedro();

        System.out.println("""
                 ██████╗ ██╗██╗     ██╗   ██╗ █████╗ ███╗   ██╗
                ██╔════╝ ██║██║     ██║   ██║██╔══██╗████╗  ██║
                ██║  ███╗██║██║     ██║   ██║███████║██╔██╗ ██║
                ██║   ██║██║██║     ╚██╗ ██╔╝██╔══██║██║╚██╗██║
                ╚██████╔╝██║███████╗ ╚████╔╝ ██║  ██║██║ ╚████║
                 ╚═════╝ ╚═╝╚══════╝  ╚═══╝  ╚═╝  ╚═╝╚═╝  ╚═══╝
                """);

        System.out.println("Hey there! I'm " + dev.name + " 👋\n");

        System.out.println("🎯 Role: " + dev.role);
        System.out.println("📚 College: " + dev.college);
        System.out.println("🌎 Country: " + dev.country);

        System.out.println("\n" + dev.status());

        System.out.println("\n🚀 Goal:");
        System.out.println(dev.currentGoal());

        System.out.println("\n📌 About Me:");
        System.out.println(dev.aboutMe());

        System.out.println("\n🔗 GitHub:");
        System.out.println(dev.github);

        System.out.println();
        dev.printStack();
    }
}
```

---

<h3 align="center">📊 Contribuições</h3>

<br>

<br>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=GilvanPedro&locale=en&mode=daily&theme=dracula&hide_border=false&border_radius=5" height="150" alt="streak" />
</div>

<div align="center" padding=10px>
  <img src="https://ghstats.dev/api/langs?username=GilvanPedro&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>

<br>

---

<h3 align="center">🎵 Tocadas Recentemente</h3>

<br>

<div align="center">
  <a href="https://open.spotify.com/user/Gilvannp">
    <img src="https://spotify-recently-played-readme.vercel.app/api?user=pvoexpixbv1o1ro0htt4qt9sb&count=10" alt="Spotify recently played" />
  </a>
</div>

<br>

---

<h3 align="center">📬 Sociais</h3>

<br>

<div align="center">
  <a href="https://www.instagram.com/gilvan_.pedro/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="instagram" />
  </a>
  <img width="6" />
  <a href="https://www.twitch.tv/gilvannp" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Twitch&logo=twitch&label=&color=9146FF&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="twitch" />
  </a>
  <img width="6" />
  <a href="mailto:gilvanpedro2006@exemplo.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail" />
  </a>
  <img width="6" />
  <a href="https://www.linkedin.com/in/gilvannp/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin" />
  </a>
  <img width="6" />
  <a href="https://x.com/gilvannp" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Twitter&logo=twitter&label=&color=1DA1F2&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="twitter" />
  </a>
</div>

<br>
