This Moodle local plugin attempts to introduce SEF URLs in Moodle.
At this stage it only consists of a set of rules to be used in combination
with Apache and mod_rewrite, to allow the usage of SEF landing URLs.

1. Copy the "htaccess" file into your Moodle webroot
2. Edit the "htaccess" file to change it according to
   your Moodle base path (see RewriteBase)
3. Rename the "htaccess" file into ".htaccess"

If you get HTTP 500 errors, mod_rewrite could be not configured or
you've made mistakes at point (2).
