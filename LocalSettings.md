# Code to "LocalSettings.php" for using the Stragula flavour to the MediaWiki Chameleon skin

```php
# Chameleon
// Composer
$egChameleonLayoutFile = __DIR__ . '/skins/Stragula/stragula.xml';
$egChameleonExternalStyleModules = [
	__DIR__ . '/skins/Stragula/bootswatch.less' => $wgScriptPath,
	__DIR__ . '/skins/Stragula/variables.less' => $wgScriptPath,
	__DIR__ . '/skins/Stragula/stragula.less' => $wgScriptPath
	];
$egChameleonExternalLessVariables = [
	'font-size-base' => '16px',
	'font-size-large' => '18px',
	'font-size-small' => '14px',
	'font-size-h1' => '28px',
	'font-size-h2' => '24px',
	'font-size-h3' => '20px',
	'line-height-base' => '1.5', /* 24 : 16 = */
	'navbar-height' => '80px',
	'navbar-margin-bottom' => '10px',
	'navbar-default-bg' => 'rgba( 94, 157, 200, 1 )',
	'navbar-default-border' => 'rgba( 94, 157, 200, 1 )',
	'nav-tabs-active-link-hover-color' => 'rgba( 255, 255, 255, 1 )',
	];

## Default skin (optional)
$wgDefaultSkin = 'chameleon';
```
