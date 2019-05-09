<h1>terracottamc</h1> <br><br>
<hr>
<h2>terracotta management console helm chart</h2><br>
first git clone repository<br>
be sure you configured secret to connect to docker hub to be able to download TMC docker image<br>
install using HELM:<br>
<code>
  $ helm install --name tmctest terracottamc --set imagePullSecrets.name=[yourSecret]
</code>
