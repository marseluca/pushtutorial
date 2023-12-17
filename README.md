<h1>Local repo push tutorial</h1>
<ul><li>Local folder name: <i>my_local_folder</i></li><li>Folder to push: <i>my_local_folder/my_repo</i></li><li>Remote repo name: <i>my_repo</i></li></ul><br>


<code>$ cd my_local_repo<br>
$ git init<br>
$ git remote add my_repo http://github.com/marseluca/my_repo<br>
$ git push -u my_repo main<br>
$ git add my_folder<br>
$ git commit -m "commit message"<br>
$ git remote add origin -M main<br>
$ git push -u origin main</code>
