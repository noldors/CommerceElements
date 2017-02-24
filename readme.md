## Commerce Collections

Commerce Collections provide a clean way to save save collections of products, such as 'cart', 'viewed' etc in Session, Cookies or Database (work in progress).

### Usage Instructions

```PHP
use Noldors\CommerceElements\Factory;

$cart = Factory::create(Factory::SESSION, 'cart');

$cart->add(12, ['quantity' => 11, 'price' => 900]);
$cart->update(12, ['quantity' => 3, 'price' => 600]);
```

## License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).