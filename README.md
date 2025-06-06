<h1>List of Github Commands</h1>

<h2>Working with Git</h2>
<p>When installing Git, we choose to work with the command prompt rather than using additional software.</p>

<h2>Git Commands</h2>

<p>Commands to configure the account:</p>

<p>Set a new username:(may have your github username)</p>
<pre><code>git config --global user.name "username"</code></pre>
<p>Set a new email address:</p>
<pre><code>git config --global user.email "email@mail.com"</code></pre>

<p>To see the configuration:</p>
<pre><code>git config --list</code></pre>

<p><code>~</code> indicates that we are in the root directory when using Git Bash.</p>

<p>The term <code>local</code> refers to your machine, while <code>remote</code> refers to <code>github.com</code>.</p>

<p>To clone a Git repository into your local machine:</p>
<pre><code>git clone https://repo-link</code></pre>

<p>To list files in Git Bash or the VS Code terminal, use <code>ls</code>. To see hidden files, use <code>ls -a</code>.</p>

<p><code>git status</code> provides information about the current branch and file states such as committed, modified, or untracked.</p>

<p><strong>Git terminology:</strong></p>
<ul>
  <li><code>Untracked</code>: A new file not yet tracked by Git.</li>
  <li><code>Modified</code>: A file that has been changed.</li>
  <li><code>Staged</code>: A file that is ready to be committed.</li>
  <li><code>Unmodified</code>: A file that hasn’t changed.</li>
</ul>

<p>To add a specific file:</p>
<pre><code>git add filename</code></pre>

<p>To add all files:</p>
<pre><code>git add .</code></pre>

<p>To commit changes:</p>
<pre><code>git commit -m "some message"</code></pre>

<p>To push to the remote repository:</p>
<pre><code>git push origin main</code></pre>
