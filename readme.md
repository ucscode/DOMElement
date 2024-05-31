# DOMElement

This file may contain other classes and functionalities in future, but for now, it's only a list of valid HTML name that you can use consistently in your project

```php
interface DOMElementNameInterface
{
    public const NODE_A = 'A';
    public const NODE_BLOCKQUOTE = 'BLOCKQUOTE';
    public const NODE_BODY = 'BODY';
    public const NODE_BR = 'BR';
    public const NODE_BUTTON = 'BUTTON';
    public const NODE_FIELDSET = 'FIELDSET';
    public const NODE_H1 = 'H1';
    public const NODE_H2 = 'H2';
    // and so on...
}
```

## Installation

You can install with composer:

```bash
composer require ucscode/dom-element
```

or you can download an include the script manuall using `require` or `include` keyword

```php
require '/path/to/DOMElementNameInterface.php';
```

## Usage

```php
use Ucscode\DOMElement\DOMElementNameInterface;

$document = new DOMDocument();

$divElement = $document->createElement(DOMElementNameInterface::NODE_DIV);

$spanElement = new DOMElement(DOMElementNameInterface::NODE_SPAN);

// ...
```

## Author

Create by Ucscode - Uchenna Ajah