# Linux Installation #
<pre class="code">
sudo mkdir /usr/local/share/texmf
cd /usr/local/share/texmf
sudo rm -rf dvips/KULIFE tex/latex/beamer/KULIFE
sudo rm -rf dvips/Frederiksberg tex/latex/beamer/Frederiksberg texmf
sudo tar xzf /path-to-the-file/Frederiksberg-2-2.tgz
# Install a unit package, if available:
# sudo tar xzf /path-to-the-file/myunit.tgz
sudo texhash
</pre>
