SASS Mixins
===========

A collection of [SASS](http://sass-lang.com/ "SASS") mixins for your project.

* [Animation](#animation)
   * [Keyframes](#keyframes)
* [Background size](#background-size)
* [Box shadow](#box-shadow)
* [Opacity](#opacity)
* [Clearfix](#clearfix)
* [Border radius](#border-radius)
* [Box-sizing](#box-sizing)
* [Transition](#transition)
* [Columns](#columns)
* [Transform](#transform)
    * [Default](#default)
    * [Translate](#translate)
    * [Skew](#skew)
    * [Scale](#scale)
    * [Rotate](#rotate)
    * [Transform-origin](#transform-origin)
* [Gradients](#gradients)
    * [Linear Horizontal](#linear-horizontal)
    * [Linear Vertical](#linear-vertical)

## Animation

```scss
.class { @include animation(animationName 1s); }
```

### Keyframes

```scss
@include keyframes(animationOne) {
    from { background-color: red; }
    to { background-color: black; }
}
```

## Background size

```scss
.class { @include background-size(auto 100%); }
```

## Box shadow

```scss
.class { @include box-shadow(1px 1px 10px 10px #666, 2px 2px 5px 5px #ddd inset); }
```

## Opacity

```scss
.class { @include opacity(0.5); }
```

## Clearfix

```scss
.class { @include clearfix(); }
```

## Border-radius

```scss
.class { @include border-radius(10px); }
```

## Box-sizing

```scss
.class { @include box-sizing(); }
```

## Transition

```scss
.class { @include transition(color 1s .5s ease-out); }
```

## Columns

```scss
.class { @include columns(3, 150px, solid 1px red); }
```

## Transform

### Default

```scss
.class { @include transform(rotate(45deg); }
```

### Translate

```scss
.class { @include translate(100px, 100px); }
```

### Skew

```scss
.class { @include skew(10px, 10px); }
```

### Scale

```scss
.class { @include scale(0.75); }
```

### Rotate

```scss
.class { @include rotate(45deg); }
```

### Transform-origin

```scss
.class { @include transform-origin(left, top); }
```

## Gradients

### Linear horizontal

```scss
.class { @include horizontal-gradient(#666, #000); }
```

### Linear vertical

```scss
.class { @include vertical-gradient(#666, #000); }
```

