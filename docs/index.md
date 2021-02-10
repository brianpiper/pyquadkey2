# 🌍 Introduction
This is a feature-rich Python implementation of [QuadKeys](https://docs.microsoft.com/en-us/bingmaps/articles/bing-maps-tile-system), an approach to **geographical tiling**, popularized by Microsoft to be used for Bing Maps.

![](https://docs.microsoft.com/en-us/bingmaps/articles/media/5cff54de-5133-4369-8680-52d2723eb756.jpg)

In essence, the concept is to **recursively** divide the flat, two-dimensional world map into squares. Each square contains **four squares** as children, which again contain four squares and so on, up **centimeter-level precision**. Each of these squares is **uniquely identifiable with a string** like `021030032`.

For more details on the concept, please refer to the [original article](https://docs.microsoft.com/en-us/bingmaps/articles/bing-maps-tile-system).

[muety/pyquadkey2](https://github.com/muety/pyquadkey2) originates from a **fork** of [buckhx/QuadKey](https://github.com/buckhx/QuadKey), which is not maintained anymore. It build on top of that project and adds:

* ✅ Several (critical) [bug fixes](https://github.com/buckhx/QuadKey/pull/15)
* ✅ Python 3 support
* ✅ [Type hints](https://docs.python.org/3.6/library/typing.html) for all methods
* ✅ Higher test coverage
* ✅ Cython backend for improved performance
* ✅ 64-bit integer representation of QuadKeys
* ✅ Additional features and convenience methods

[![Buy me a coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoff.ee/n1try)