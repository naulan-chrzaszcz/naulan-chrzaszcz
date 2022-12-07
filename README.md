![Banner Profile](https://eapi.pcloud.com/getpubthumb?code=XZmubJZO3RLKrQ4bwSiOupYtRg78SzGx3N7&linkpassword=undefined&size=1918x378&crop=0&type=auto)

<p align="center">
<a href="https://discord.gg/yEvBg8CPaM"><img alt="Discord" src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white"></a>
<a href="https://www.instagram.com/naulan.chrzaszcz/"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
<a href="https://www.twitch.tv/NaulaN_CHRZdev"><img alt="Twitch" src="https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white"></a>
<a href="https://www.youtube.com/channel/UCbl4AHVket_DNhBzQG56f7w"><img alt="Youtube" src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"></a>
</p>
  
<h1>Bienvenue sur mon Github</h1>

- <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" width="17" height="17"> Membre sur Github depuis: ![badge](https://badges.pufler.dev/years/NaulaN)
- 🌐 __[Mon site web](https://www.chrz-development.fr)__

<p align="center"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NaulaN&layout=compact&count_private=true&theme=gruvbox)](https://github.com/anuraghazra/github-readme-stats"></p>

<p align="center">⬇️ <b>Les languages de programmation que j'utilise régulierement</b> ⬇️</p>

<p align="center"><code><img src="https://developer.asustor.com/uploadIcons/0020_999_1596443479_JAVA.png" width="25" height="25"></code>
<code><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/1200px-Python-logo-notext.svg.png" width="25" height="25"></code>
<code><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/512px-HTML5_logo_and_wordmark.svg.png" width="25" height="25"></code>
<code><img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg" width="25" height="25"></code>
<code><img src="https://upload.wikimedia.org/wikipedia/commons/9/99/Unofficial_JavaScript_logo_2.svg" width="25" height="25"></code>
<code><img src="https://upload.wikimedia.org/wikipedia/commons/2/29/Postgresql_elephant.svg" width="25" height="25"></code>
</p>

😊 **A propos de moi:**
```java
package fr.naulanchrzaszcz.aboutme;

import fr.naulanchrzaszcz.aboutme.Me;

import fr.naulanchrzaszcz.other.Coffee;
import fr.naulanchrzaszcz.other.Breakfast;
import fr.naulanchrzaszcz.other.Tea;


public class Naulan extends Human implements Humours, Connerie
{
  private final String familyName = "CHRZASZCZ";
  private final String name = "Naulan";
  private final String origin = "🇵🇱";
  private final String live = "🇫🇷";
  private final String study = "BUT INFO à l'IUT de Montreuil."
  
  public @Override String toString() 
  {
    final StringBuilder aboutme = new StringBuilder();
    aboutme.append("🏷️ Je m'appelle " + this.familyName + " " + this.name);
    aboutme.append("\n💼 Actuellement en étude en " + this.study);
    aboutme.append("\n📍 Je suis d'origine " + this.origin);
    aboutme.append("\n🏡 Je vie en " + this.live);
    
    return aboutme;
  }
  
  /**
   * @param age Determines the age of the person who owns the Github
   * @param heights Define the height of a person in meters
   */
  public Naulan(int age, double heights) 
  {
    super(19, 1.98);
    
    while(!this.isNotDead()) {
      try {
        this.wakeUp(new Coffee(), new Breakfast());
      catch(CantWakeUp cantWakeUp) { cantWakeUp.forceWakeUp(); }
      
      this.work();
      this.learn();
      this.eat();
      this.sleep();
    }
  }
  
  public void wakeUp(Coffee coffee, Breakfast breakfast) throws CantWakeUp
  {
    if (((int) (1+Math.random*2)) == 1)
      coffee.drink();
    else new Tea().drink();
    
    breakfast.eat((this.wallet.getMoney() < 0) ? "cereals" : "chocolate bread");
  }
}
```
