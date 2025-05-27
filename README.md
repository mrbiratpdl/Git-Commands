<h1>Welcome to My Repository</h1>
<h2>Working with git</h2>
<p>When installing git, we select work as command prompt not with software.</p>
<h2>Git Commands</h2>
<p>Commands to configure the account:</p>
<p>Create a new user id:</p>
<pre><code>$ git config --global user.name "mrbiratpdl"</code></pre> 
<p>Create a new email:</p>
<pre><code>git config --global user.email "mr.biratpdl@gmail.com"
</code></pre>
To see the configuration:
<pre><code>$ git config --list</code></pre>
<p>
<code>~</code> indicates in git bash command that we are in root directory. </p>
<p>Term: <code>Local</code> means local machine and term: <code>remote</code> means <code>github.com</code>.</p>
<p>Cloning git into local machine:
<pre><code>git clone https://repo-link</code></pre>
<p>To list files, we write <code>ls</code> in git bash or in VS Code terminal. To see hidden files, we write <code>ls -a</code>.</p>
<p><code>git status</code> returns branch etc about current git detail like branch etc. It also gives informations like committed or not, file modified or not etc.</p>
<p>Untracked means a new new file git does not yet tracked. <code>Modified</code> means changed
, <code>staged</code> means file is read to be commited. <code> Unmodified means unchanged.</p>
<p>How to add specific file:<pre><code>git add filename</code></pre></p>
<p>To add all files:<pre><code>git add .</code></pre></p>
<p>Comitting changes:<pre><code>git commit -m "some message"</code></pre></p>
<p> Pushing to server: <pre><code>git push original main</code></pre></p>
adding..
 <p> Testing again</p>