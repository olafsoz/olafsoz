<h1 align="center">Hey there 👋</h1>

```php
class SoftwareEngineer {

    private static array $info = [
            'Name' => 'Olafs',
            'Surname' => 'Ozolins',
            'Age' => 19,
            'From' => 'Riga, Latvia',
            'Skills' => ['PHP', 'MYSQL', 'HTML5', 'CSS3', 'JavaScript', 'LARAVEL', 'COMPOSER', 'GIT'],
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
<h2 align="center">My 3 favourite projects 🔧</h2>
<div align="center">
  <p>First project - <a href="https://github.com/olafsoz/StocksHW">Stocks</a>, where it displays some stocks by default and one can search for whatever stock is on the market!</p>
  <p>Second project - <a href="https://github.com/olafsoz/BookingApp">BookingApp</a>, here one can register and login/logout, then either list or book an apartment. This was the first time I did such a thing and it was a blast!</p>
  <p>Third project - <a href="https://github.com/olafsoz/Services-Repositories-DI">Services-Repositories-DI</a>, here I made a simple page for a store using DDD - services, repositories, dependency injection. Understanding this really made it easier to start learning Laravel!</p>
</div>
<h2 align="center">Ways You can contact me! 📤</h2>
<div align="center">
  <p>DM me on <a href="https://www.linkedin.com/in/olafs-ozolins-77342a233/">LinkedIn</a></p>
  <p>Call me at +37120200926</p>
  <p>Email me at olafso18@gmail.com</p>
</div>  
