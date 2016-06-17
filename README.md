# GITHUB-PAGES

 Guia para subir seu site para o gh-pages.
 
 > DICA: Este texto é uma referência da documentação do GitHub, você pode acessá-lo neste <a href="">link</a>


### Clone seu repositório
Entre no local onde deseja clonar seu repositório e adicione a seguinte linda de comando no GitBash.

<pre>
git clone https://github.com/user/repository.git
</pre>

### Entre no repositório e crie a branch gh-pages.
<pre>
cd user
git checkout --orphan gh-pages
</pre>

### Remova arquivos desnecessários
<pre>
git rm -rf .
</pre>

### Adicione conteúdos ao repositório
<pre>
echo "My Page" > index.html
git add index.html
git commit -a -m "First pages commit"
git push origin gh-pages
</pre>

### Acesse a página no endereço
<pre>
http(s)://username.github.io/projectname
</pre>

