# Motta's Workflow

Gulp - SASS - Bootstrap

1. npm install gulp-cli -g (installs globally on computer)

2. npm install sass bootstrap @babel/core @babel/preset-env postcss autoprefixer browser-sync cssnano gulp gulp-babel gulp-postcss gulp-sass gulp-terser

 - Sass - Is an extension of CSS that enables you to use things like variables, nested rules, inline imports and more.
 - @babel/core @babel/preset-env - Autoprefixer for older web browser.
 - browser-sync - Watch all files for changes and auto refresh the website.
 - cssnano - Minify the css.

3. npm audit fix (Fix packages vulnerabilities)


## File Architecture

sass/<br/>
|<br/>
|– base/<br/>
| |– \_reset.scss # Reset/normalize<br/>
| |– \_typography.scss # Typography rules<br/>
| ... # Etc…<br/>
|<br/>
|– components/<br/>
| |– \_buttons.scss # Buttons<br/>
| |– \_carousel.scss # Carousel<br/>
| |– \_cover.scss # Cover<br/>
| |– \_dropdown.scss # Dropdown<br/>
| ... # Etc…<br/>
|<br/>
|– layout/<br/>
| |– \_navigation.scss # Navigation<br/>
| |– \_grid.scss # Grid system<br/>
| |– \_header.scss # Header<br/>
| |– \_footer.scss # Footer<br/>
| |– \_sidebar.scss # Sidebar<br/>
| |– \_forms.scss # Forms<br/>
| ... # Etc…<br/>
|<br/>
|– pages/<br/>
| |– \_home.scss # Home specific styles<br/>
| |– \_contact.scss # Contact specific styles<br/>
| ... # Etc…<br/>
|<br/>
|– themes/<br/>
| |– \_theme.scss # Default theme<br/>
| |– \_admin.scss # Admin theme<br/>
| ... # Etc…<br/>
|<br/>
|– utils/<br/>
| |– \_variables.scss # Sass Variables<br/>
| |– \_functions.scss # Sass Functions<br/>
| |– \_mixins.scss # Sass Mixins<br/>
| |– \_helpers.scss # Class & placeholders helpers<br/>
|<br/>
|– vendors/<br/>
| |– \_bootstrap.scss # Bootstrap<br/>
| |– \_jquery-ui.scss # jQuery UI<br/>
| ... # Etc…<br/>
|<br/>
|<br/>
`– main.scss # Main Sass file
