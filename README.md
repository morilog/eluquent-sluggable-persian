eluquent-sluggable-persian
==========================

Laravel Eloquent sluggable for persian &amp; arabic labguages

##installation

1. install [eloquent sluggable](https://github.com/cviebrock/eloquent-sluggable)
2. replace cviebrock/eloquent-sluggable/src/config/config.php with [config.php](https://github.com/morilog/eluquent-sluggable-persian/blob/master/config.php)
3. enjoy it!


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
