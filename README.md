# PHP Dot Array - Access array using dot notation in PHP
*PHP Dot Array* is a lightweight library that has few **Helper** methods for array and also provides an easy way of accessing arrays using **Dot notation**.

This is a standalone version of Laravel's *Illuminate\Support\Arr*.

## Installation
The installation is simple using [Composer](https://getcomposer.org)
```
composer require raziul/php-dot-array
```

## How to use?
An example using regular syntax: 
```PHP
$data = [
    'author' => [
        'name' => 'Raziul Islam'
    ]
];

$data['author']['country']['name'] = 'Bangladesh';

echo $data['author']['country']['name']; // Bangladesh
```

Same example in dot array:
```PHP
Arr::set($data, 'author.name', 'Raziul Islam');

Arr::set($data, 'author.country.name', 'Bangladesh');

echo Arr::get($data, 'author.country.name');
```

## Available Methods
Other than dot notation, this library also has some helper methods.
These are the available methods:

- [accessible()](#accessible)
- [add()](#add)
- [collapse()](#collapse)
- [crossJoin()](#crossJoin)
- [divide()](#divide)
- [dot()](#dot)
- [except()](#except)
- [exists()](#exists)
- [first()](#first)
- [last()](#last)
- [flatten()](#flatten)
- [remove()](#remove)
- [get()](#get)
- [has()](#has)
- [hasAny()](#hasAny)
- [isAssoc()](#isAssoc)
- [only()](#only)
- [prepend()](#prepend)
- [pull()](#pull)
- [random()](#random)
- [set()](#set)
- [shuffle()](#shuffle)
- [sortRecursive()](#sortRecursive)
- [query()](#query)
- [where()](#where)
- [wrap()](#wrap)

## Usage Example

<a name="accessible"></a>
### accessible()

<a name="add"></a>
### add()

<a name="collapse"></a>
### collapse()

<a name="crossJoin"></a>
### crossJoin()

<a name="divide"></a>
### divide()

<a name="dot"></a>
### dot()

<a name="except"></a>
### except()

<a name="exists"></a>
### exists()

<a name="first"></a>
### first()

<a name="last"></a>
### last()

<a name="flatten"></a>
### flatten()

<a name="remove"></a>
### remove()

<a name="get"></a>
### get()

<a name="has"></a>
### has()

<a name="hasAny"></a>
### hasAny()

<a name="isAssoc"></a>
### isAssoc()

<a name="only"></a>
### only()

<a name="prepend"></a>
### prepend()

<a name="pull"></a>
### pull()

<a name="random"></a>
### random()

<a name="set"></a>
### set()

<a name="shuffle"></a>
### shuffle()

<a name="sortRecursive"></a>
### sortRecursive()

<a name="query"></a>
### query()

<a name="where"></a>
### where()

<a name="wrap"></a>
### wrap()


## Suggestion/Issues
If you found any issues or have any suggestion then please create an [issue](https://github.com/iRaziul/php-dot-array/issues).

You can also submit PR regarding any issues.

## License
The MIT License (MIT). Please see [License File](LICENSE) for more information.