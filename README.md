# WPanel4-Authenticated-RCE

https://latestpcsolution.wordpress.com/2021/06/05/wpanel4-cms-authenticated-rce/

<!-- wp:paragraph -->
<p><strong>Admin Panel RCE Multiple Vulnerable Endpoints</strong></p>
<!-- /wp:paragraph -->

<!-- wp:syntaxhighlighter/code -->
<pre class="wp-block-syntaxhighlighter-code">Dashboard -> Manage my profile -> Avatar image 
(Browser and add PHP Reverse shell)

Posts -> New Record -> Folder image 
(Browse and add PHP Reverse shell)

Pages -> New Record -> Folder image 
(Browse and add PHP Reverse shell)

Gallery -> New Record -> Folder 
(Browse and add PHP Reverse shell)</pre>
<!-- /wp:syntaxhighlighter/code -->
