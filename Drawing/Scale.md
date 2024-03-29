## Drawing.Scale класс


```lua
class Drawing.Scale
{
    // Member Fields

    x; // float
    y; // float


    // Functions

    constructor( x   // integer|float|string
               , y   // integer|float|string
               )

    function _add( c   // Drawing.Scale
                 )
    // returns: Drawing.Scale

    function _sub( c   // Drawing.Scale
                 )
    // returns: Drawing.Scale

    function _unm( c   // Drawing.Scale
                 )
    // returns: Drawing.Scale

    function _mul( c   // Drawing.Scale
                 )
    // returns: Drawing.Scale

    function _div( c   // Drawing.Scale
                 )
    // returns: Drawing.Scale

    function tostring()
    // returns: string

    function _tostring()
    // returns: string


} // class Drawing.Scale
```



### Поля класса

**x** (**float**) - ![x]

**y** (**float**) - ![y]


### Методы


[constructor](../Drawing/Scale/constructor.md) - ![__BRIEF]


**_add** - Поддержка оператора 'plus' ('+'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#add) для получения подробностей.


**_sub** - Поддержка оператора 'minus' ('-'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#sub) для получения подробностей.


**_unm** - Поддержка оператора 'unary minus' ('-'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#unm) для получения подробностей.


**_mul** - Поддержка оператора 'multiply' ('*'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#mul) для получения подробностей.


**_div** - Поддержка оператора 'divide' ('/'). См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#div) для получения подробностей.


**tostring** - Преобразует значение в string и возвращает его, см. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/builtin_functions.html#string) для получения подробностей. Реализован для совместимости со встроенными типами. Метод toString() также реализован для соответствия соглашениям об именовании camelCase.


**_tostring** - Поддержка преобразования в строку. См. [squirrel manual](http://squirrel-lang.org/squirreldoc/reference/language/metamethods.html#tostring) для получения подробностей.


