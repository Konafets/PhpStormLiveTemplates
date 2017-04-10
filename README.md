# PhpStormLiveTemplates

## PHP

### Private Function

* Scope: PHP
* Abbreviation: prif

```php
private function $NAME$($PARAMETERS$){
    $END$
}
```

### Private Static Function

* Scope: PHP
* Abbreviation: prifs

```php
private static function $NAME$($PARAMETERS$){
    $END$
}
```

### Protected Function

* Scope: PHP
* Abbreviation: prof

```php
protected function $NAME$($PARAMETERS$){
    $END$
}
```

### Protected Static Function

* Scope: PHP
* Abbreviation: profs

```php
protected static function $NAME$($PARAMETERS$){
    $END$
}
```

### Public Function

* Scope: PHP
* Abbreviation: pubf

```php
public function $NAME$($PARAMETERS$){
    $END$
}
```

### Public Static Function

* Scope: PHP
* Abbreviation: pupfs

```php
public static function $NAME$($PARAMETERS$){
    $END$
}
```

### Throw New Exception

* Scope: PHP
* Abbreviation: thr

```php
throw new $END$
```

### Todo

* Scope: PHP
* Abbreviation: todo

```php
// TODO: $END$
```


## Exbase

### Action

* Scope: PHP
* Abbreviation: action

```php
/**
 * $ACTIONNAME$ action
 *
 * @return void
 */
public function $NAME$Action($PARAM$) {
	$END$
}
```

### Injection Method

* Scope: PHP
* Abbreviation: inj

```php
/**
 * @param $NAMESPACE$ $$$VARIABLE$
 * @return void
 */
public function inject$NAME$($NAMESPACE$ $$$VARIABLE$) {
	$this->$VARIABLE$ = $$$VARIABLE$;
}
```

### Inject the ObjectManager

* Scope: PHP
* Abbreviation: injo

```php
/**
 * @var ObjectManager
 */
protected $objectManager;

/**
 * Injects the ObjectManager
 *
 * @var \TYPO3\CMS\Extbase\Object\ObjectManager $objectManager
 * @return void
 */
public function injectObjectManager(ObjectManager $objectManager) {
	$this->objectManager = $objectManager;
}
```


## VueJS

### VueJS Component 

* Scope: JavaScript
* Abbreviation: v-comp

```js
Vue.component('$NAME$', {
    $END$
});
```

### VueJS Inline Template 

* Scope: HTML
* Abbreviation: v-it

```html
<$NAME$ inline-template>
    $END$
</$NAME$>
```
