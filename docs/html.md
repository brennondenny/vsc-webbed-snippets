## Documentation

|  Trigger  | Describe                   |
| --------: | ---------------------------|
| `hbs →`   | `html.base.struct`         |
| `hbr →`   | `html.base.react`          |
| `hmsf →`   | `html.meta.social.fb`    |
| `hmsx →`   | `html.meta.social.x`     |


## Snippets

### `html.base.struct` | hbs

```html
<!DOCTYPE html>
<html lang='en'>
	<head>
		<meta charset='utf-8' />
		<meta name='viewport' content='width=device-width' />
		<link rel='icon' href='public/favicon.svg' type='image/svg+xml' />
		<link rel='stylesheet' href='styles.css' />
		<title>Title</title>
	</head>
	<body>
		$1
	</body>
</html>
```

### `html.base.react` | hbr

```html
<!DOCTYPE html>
<html lang='en'>
	<head>
		<meta charset='utf-8' />
		<meta name='viewport' content='width=device-width' />
		<link rel='icon' href='public/favicon.svg' type='image/svg+xml' />
		<title>Title</title>
	</head>
	<body>
		<div id='root'></div>

		<script type='module' src='/src/main.jsx'></script>
	</body>
</html>
```

### `html.meta.social.fb` | hmsf

```html
        <meta property='og:url' content='' />
        <meta property='og:type' content='website' />
        <meta property='og:title' content='' />
        <meta property='og:description' content='' />
        <meta property='og:image' content='' />
```

### `html.meta.social.x` | hmsx

```html
        <meta property='twitter:url' content='' />
        <meta property='twitter:card' content='summary_large_image' />
        <meta property='twitter:title' content='' />
        <meta property='twitter:description' content='' />
        <meta property='twitter:image' content='' />
```