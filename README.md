# beans-polish-translation
Polish language translations for Beans (http://www.getbeans.io/) Wordpress theme.

It isn't completed yet, just one text translated to see if it works :).
I will continue work, but any contribution or comments are welcome.

Installation example :
1. Download file pl_PL.po
2. Compile it to .mo file. I.e.: msgfmt -o pl_PL.mo pl_PL.po
   or use GUI tools like PoEdit : https://github.com/vslavik/poedit
3. Be sure to have this line in functions.php on your Beans child-theme :
   load_child_theme_textdomain( 'tm-beans', get_stylesheet_directory() . '/languages/' );
4. Copy pl_PL.mo and pl_PL.po files into your Beans child-theme languages directory ( if
   directory dosen't exists - create it).
   I.e. wp-content/themes/tm-beans-child/languages

