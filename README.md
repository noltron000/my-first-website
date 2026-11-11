# My First Website
*View the project live at **[https://projects.nebuloid.dev/my-first-website/](https://projects.nebuloid.dev/my-first-website/)**.*

> I originally made this website back in 2017, when I was still studying at Kent State University.
> A lot has changed in my life since then, but I appreciate the idea of keeping this website live as a sort of archival unit.
>
> *Thanks for visiting!*

![Kent State University Campus](themes/prologue/static/img/banner.jpg)

## Running Locally
You can get this website running locally with a few commands in your terminal:
1. Download the code using `git clone`.
1. Enter the project directory via `cd`.
1. Run `hugo server` in your terminal.
	- Ensure Hugo is installed locally on your machine.
1. To view the site in your browser, open the URL printed by Hugo
	(usually [http://localhost:1313](http://localhost:1313)).

### Build Files Locally
To build locally, run:
```sh
hugo --minify --destination public
```

The generated site is written to the ignored `public/` directory.

## Deploy using GitHub Pages
The site is hosted with GitHub Pages from the `main` branch at the repository root.
Whenever `main` receives new commits, gh pages should update automatically.
