# Swiper xQuery
Swiper xQuery is a custom of Swiper that allow using 3rd DOM manipulation library like jQuery, Zepto,...etc

# When you will use Swiper xQuery
- You are NOT using Dom7 and using another DOM manipulation library like jQuery, Zepto,...

# When you will NOT use Swiper xQuery
- You are using Dom7 for DOM manipulation

# How to use
```
import $ from 'jquery';
import Swiper from 'swiper';

Swiper.$ = $; // attach DOM manipulation library to Swiper

// everything below will be the same as before
```

For further information, please take a look at the [Official Documentation](https://swiperjs.com/swiper-api)
