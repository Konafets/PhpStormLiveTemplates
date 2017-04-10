# PhpStormLiveTemplates

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
