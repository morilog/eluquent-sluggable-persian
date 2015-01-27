eluquent-sluggable-persian
==========================

Laravel Eloquent sluggable for persian &amp; arabic labguages

##installation

1. install [eloquent sluggable](https://github.com/cviebrock/eloquent-sluggable)
2. run `php artisan config:publish cviebrock/eloquent-sluggable` in command-line
3. replace `app/config/packages/cviebrock/eluqnt-sluggable/config.php` with [config.php](https://github.com/morilog/eluquent-sluggable-persian/blob/master/config.php) 



##usage

```php
  for($i=0;$i<3;$i++)
  {
    $post = new Post(array('title'=>'عنوان پست آزمایشی'));
    $post->save();
  }
  
  
    
```
####output

      http://example.com/post/عنوان-پست-آزمایشی
      http://example.com/post/عنوان-پست-آزمایشی-1
      http://example.com/post/عنوان-پست-آزمایشی-2
