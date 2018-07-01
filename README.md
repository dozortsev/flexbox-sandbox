# FlexBox


### tl;dr about flexbox approach

1. We strucutre / build our web page using _flex conteiners_ and _flex items_.
2. Every _flex conteiner_ contains and positon multiple _flex itmes_.
3. Any _flex item_ can contains multiple other _flex items_ being a _flex container_ for them.
4. Do define a _flex conteiner_ use `display: flex;` it tells browser to render everthing in side the tag as _flexbox_ instead default _box_ way.
5. In flexbox _flex conteiner_ (parent) defines how to position _flex items_ (child) and it only cares about his own _flex items_ without touching _flex item_ which inside _flex item_ which are inside him.
6. `align-items` to align _flex items_ vertically and `justify-content` to align _flex items_ horizontally.

### Learnings

1. new CSS propery for me `box-sizing`


### Sources

- https://internetingishard.com/html-and-css/flexbox/

- https://getbootstrap.com/docs/4.0/utilities/flex/