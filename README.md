# Qicz Hugo Theme (based on Kiera Theme)

### using img

* full image ![](url#full), append `#ful`l to url.
* mid image ![](url#mid), append `#mid` to url.
* avatar image ![](url#avatar), append `#avatar` to url.

### Update footer copyright logic

- setting the copyright in config.toml file like this 

> copyright = "Copyright &copy; 2012 - "#copyright prefix , html copyright = copyright + footer.html.copyright; footer.html.copyright= "Date.year" + author'

### Add .sh script

- `gen_deploy.sh` script will auto generate and deploy the site.

### fixed seo features

- update meta.html layout
- update header_include.html layout

### update style

- update style and awesome font
- update `table` and `img` style

### add PV and UV

- update footer.html layout
- update hedaer_include.html layout
