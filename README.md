
 to add from CLI
php artisan tinker
$product = new App\models\product;
$product->name="BMW";
$Product->description="une bonne voiture";
$product->price=123222;
$product->category=2;
$product->save();

To delete

$product =App\models\product::findorfail(1);
$product->delete();
