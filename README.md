<h1 align="center">Hey there 👋</h1>

```php
class SoftwareEngineer {

    private static array $info = [
            'Name' => 'Olafs',
            'Surname' => 'Ozolins',
            'Age' => 19,
            'From' => 'Riga, Latvia',
            'Skills' => ['PHP', 'MYSQL', 'HTML5', 'CSS3', 'LARAVEL', 'COMPOSER', 'GIT'],
            'Willingness to learn' => 'Through the roof!'
        ];
    
    public static function getInfo(): array {
        return self::$info;
    }
}

foreach (SoftwareEngineer::getInfo() as $title => $value) {
    if ($title === 'Skills') {
        echo $title . ' - ';
        echo implode(', ', $value) . PHP_EOL;
    } else {
        echo $title . ' - ' . $value . PHP_EOL;
    }
}
```
<!-- <p align="center">My name is Olafs Ozolins, a 19 year old software engineer from Riga, Latvia. </p>
<p align="center">Currently I am learning everything there is to know about PHP and the things surrounding it.</p>
<h2 align="center">Toolbox 🧰</h2>
<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="PHP" width="50" height="50"/>
  &ensp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" alt="MYSQL" width="50" height="50"/>
  &ensp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-plain.svg" alt="Laravel" width="50" height="50"/>
  &ensp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" width="50" height="50" />
  &ensp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" width="50" height="50" />
  &ensp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" width="50" height="50" />
  &ensp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/composer/composer-original.svg" alt="Composer" width="50" height="50" />
</div> -->
<h2 align="center">My top 3 projects 🔧</h2>
<div align="center">
  <p>First project - <a href="https://github.com/olafsoz/StocksHW">Stocks</a>, where it displays some stocks by default and one can search for whatever stock is on the market!</p>
  <p>Second project - <a href="https://github.com/olafsoz/LoginDB">RegisterNLogin</a>, here one can register and login/logout. This was the first time I did such a thing!</p>
  <p>Third project - <a href="https://github.com/olafsoz/personRegister">PersonRegistry</a>, here one can add a person to a list, see the list, and then delete from the list!</p>
</div>
<h2 align="center">Ways You can contact me! 📤</h2>
<div align="center">
  <p>DM me on <a href="https://www.linkedin.com/in/olafs-ozolins-77342a233/">LinkedIn</a></p>
  <p>Call me at +37120200926</p>
  <p>Email me at olafso18@gmail.com</p>
</div>  
