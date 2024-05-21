![IMG_1692](https://github.com/naulan-chrzaszcz/naulan-chrzaszcz/assets/67024770/525246c0-d178-4984-a260-d235e857df9a)
<h1>Welcome to my Github profile</h1>
<p align="center">
<a href="mailto:contact@naulan-chrzaszcz.fr"><img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
<a href=""><img alt="PayPal" src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white"></a>
<a href="https://www.linkedin.com/in/naulan-chrzaszcz/"><img alt="Linkedin" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="https://www.instagram.com/naulan.chrzaszcz/"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
</p>

🌐 __[Portefolio](https://www.chrz-development.fr)__

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=naulan-chrzaszcz&layout=compact&count_private=true&theme=gruvbox)](https://github.com/NaulaN/github-readme-stats">
</p>

😊 **About me:**
```java
public class Naulan extends Human
{
  private final Country origin = Country.POLISH;
  private final Country live = Country.FRANCE;
  private final IUT study = IUT.MONTREUIL(Diploma.BUT.INFO);

  public Naulan() 
  {
    while (!this.notDead()) {
      try {
        this.wakeUp(new Coffee(), new Breakfast());
      } catch(Exception cantWakeUp) {
	  	this.forceWakeUp();
	  }

      this.work();
      this.learn();
      this.eat();
      if (Time.haveEnoughTime())
	  	this.play(Game.BEAM_NG);
      this.sleep();
    }
  }

  public void wakeUp(Coffee coffee, Breakfast breakfast) throws CantWakeUp
  {
    if (((int) (1 + Math.random * 2)) == 1)
      coffee.drink();
    else new Tea().drink();

    breakfast.eat((this.wallet.getMoney() < 0) ? "cereals" : "chocolate bread");
  }
}
```
