![Banner Profile](https://eapi.pcloud.com/getpubthumb?code=XZmubJZO3RLKrQ4bwSiOupYtRg78SzGx3N7&linkpassword=undefined&size=1918x378&crop=0&type=auto)

[![DiscordBadge](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/yEvBg8CPaM)
[![InstagramBadge](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/naulan.chrzaszcz/)
[![TwitchBadge](https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white)](https://www.twitch.tv/NaulaN_CHRZdev)
[![YouTubeBadge](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCbl4AHVket_DNhBzQG56f7w) 

<img src="https://c.tenor.com/nebZyl8oN7IAAAAj/wave-hello.gif" width="40" height="40"> [![Welcome Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Bienvenue+sur+mon+Github+!)](https://git.io/typing-svg)

😊 **A propos de moi:**
````java
package fr.naulanchrzaszcz.aboutme;

import fr.naulanchrzaszcz.aboutme.Me;

import fr.naulanchrzaszcz.other.Coffee;
import fr.naulanchrzaszcz.other.Breakfast;
import fr.naulanchrzaszcz.other.Tea;


/**
 * @see fr.naulanchrzaszcz.other.Coffee
 * @see fr.naulanchrzaszcz.other.Breakfast
 */
public class Naulan extends Human implements Humours, Connerie
{
  private String familyName = "CHRZASZCZ";
  private String name = "Naulan";
  private String origin = "🇵🇱";
  private String live = "🇫🇷";
  
  private String study = "BUT INFO à l'IUT de Montreuil."
  private String[] musicsStyle = new String[] {"HardBass musics", "Chill musics"};
  
  
  /**
   * @param age Determines the age of the person who owns the Github
   * @param heights Define the height of a person in meters
   */
  public Naulan(int age, double heights) 
  {
    super(18, 1.96);
    
    while(!this.isNotDead()) {
      // In my house
      try {
        this.wakeUp(new Coffee(), new Breakfast());
      catch(CantWakeUp cantWakeUp) { cantWakeUp.forceWakeUp(); }
      
      // In a entreprise or in my university
      this.work();
      this.learn();
      
      // In my house
      this.eat();
      this.sleep();
    }
  }
  
  public String toString() 
  {
    StringBuilder aboutme = new StringBuilder();
    aboutme.append("🏷️ Je m'appelle " + this.familyName + " " + this.name);
    aboutme.append("\n💼 Actuellement en étude en " + this.study);
    aboutme.append("\n📍 Je suis d'origine " + this.origin);
    aboutme.append("\n🏡 Je vie en " + this.live);
    aboutme.append("\n🎵 J'écoute régulierement de la " + this.musicsStyle[0] + " et de la " + this.musicsStyle[1])
    
    return aboutme;
  }
  
  public void wakeUp(Coffee coffee, Breakfast breakfast) 
  {
    if (((int) (1+Math.random*2)) == 1)
      coffee.drink();
    else new Tea().drink();
    
    breakfast.eat((this.wallet.getMoney() < 0) ? "cereals" : "chocolate bread");
  }
}
````
- <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" width="17" height="17"> Membre sur Github depuis: ![badge](https://badges.pufler.dev/years/NaulaN)
- 🌐 __[Mon site web](https://www.chrz-development.fr)__

<p align="center">⬇️ <b>Les languages de programmation que j'utilise régulierement</b> ⬇️</p>

<p align="center"><code><img src="https://developer.asustor.com/uploadIcons/0020_999_1596443479_JAVA.png" width="25" height="25"></code>
<code><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/1200px-Python-logo-notext.svg.png" width="25" height="25"></code>
<code><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/512px-HTML5_logo_and_wordmark.svg.png" width="25" height="25"></code>
<code><img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg" width="25" height="25"></code>
<code><img src="https://upload.wikimedia.org/wikipedia/commons/9/99/Unofficial_JavaScript_logo_2.svg" width="25" height="25"></code>
<code><img src="https://upload.wikimedia.org/wikipedia/commons/2/29/Postgresql_elephant.svg" width="25" height="25"></code>
</p>

<p align="center"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NaulaN&layout=compact&count_private=true&theme=gruvbox)](https://github.com/anuraghazra/github-readme-stats"></p>

<p align="center">⬇️ <b>PC Spec</b> ⬇️</p>

<p align="center">
<img src="https://img.shields.io/badge/AMD%20Ryzen_3_2200G-ED1C24?style=for-the-badge&logo=amd&logoColor=white">
<img src="https://img.shields.io/badge/AMD%20Radeon_Vega_8-ED1C24?style=for-the-badge&logo=amd&logoColor=white">
</p>
