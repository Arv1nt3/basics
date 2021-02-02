<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="GIT_0"></a>GIT</h1>
<p class="has-line-data" data-line-start="2" data-line-end="3">Tema pentru trainingul de GIT.</p>
<h2 class="code-line" data-line-start=4 data-line-end=5 ><a id="Comenzi_4"></a>Comenzi</h2>
<pre><code class="has-line-data" data-line-start="7" data-line-end="28">git clone git@github.com:Arv1nt3/basics.git
cd basics/
mkdir bash
mkdir python
cd bash
vim basic.sh
cd ..
cd python/
vim basic.py
vim modul.py
cd ..
git add ./bash/basic.sh
git add ./python/basic.py
git add ./python/modul.py
git commit -m &quot;First commit&quot;
vim README.md
git add README.md
git commit -m &quot;Second commit&quot;
git log
git push origin master
</code></pre>
