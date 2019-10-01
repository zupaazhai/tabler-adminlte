# Tabler + Admin LTE

Tabler [https://tabler.io/](https://tabler.io/) and Admin LTE [https://adminlte.io/](https://adminlte.io/) are my favorite css ui that I always used in several projects. the main idea of this project is combine admin dashboard style base on Admin LTE with clean UI of Tabler

![Tabler + Admin LTE Screenshot](https://raw.githubusercontent.com/zupaazhai/tabler-adminlte/master/screenshot.png)

## How to use

assets files in directory `css` and `js` are base that you need to add to your page.

```html
<head>
    <link rel="stylesheet"
            href="https://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400,600,700,300italic,400italic,600italic">
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css">
        <link rel="stylesheet" href="css/dashboard.css">
        <link rel="stylesheet" href="css/tabler-adminlte.css">

    <script src="js/require.min.js"></script>
	<script src="js/dashboard.js"></script>
	<script>
		requirejs.config({
			baseUrl: '.'
		});
	</script>
</head>
```

initial your layout like this

```html
<body class="sidebar-mini fixed">
	<div class="wrapper">

		<header class="main-header">
			<a href="#" class="logo">
				<span class="logo-mini uppercase">TBL</span>
				<span class="logo-lg">Tabler LTE</span>
			</a>
			<nav class="navbar-top">
				<a href="#" class="sidebar-toggle fa5" data-toggle="push-menu" role="button">
				</a>
			</nav>
        </header>

        <aside class="main-sidebar">
			<section class="sidebar">
                ... menu here
            </section>
        </aside>

        <div class="content-wrapper">
			<div class="content-header">
				<h1 class="page-title">Dashboard</h1>
			</div>

			<div class="content">
                ... content here
            </div>
        </div>

    </div>
</body>
```

see document and demo
- Tabler [Demo & Documentation](https://preview.tabler.io/)
- Admin LTE [Demo & Documentation](https://adminlte.io/themes/AdminLTE/index2.html)