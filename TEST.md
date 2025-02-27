Just testing some layout issues!

<table>
  <tr>
    <th>Tool</th>
    <th>Command</th>
  </tr>
  <tr>
    <td>Maven Wrapper (Linux/Mac)</td>
    <td>&nbsp;<br /><pre lang="shell">./mvnw clean verify</pre></td>
  </tr>
  <tr>
    <td>Maven Wrapper (Windows)</td>
    <td>&nbsp;<br /><pre lang="shell">mvnw.cmd clean verify</pre></td>
  </tr>
  <tr>
    <td><div class="highlight highlight-source-shell notranslate position-relative overflow-auto">Maven (command-line)</div></td>
    <td><pre lang="shell">mvn clean verify</pre></td>
  </tr>
  <tr>
    <td><div class="highlight highlight-source-shell notranslate position-relative overflow-auto">Maven (command-line & setting jvmserver)</div></td>
    <td><pre lang="shell">mvn clean verify -Dcics.jvmserver=MYJVM</pre></td>
  </tr>
</table>

Maybe a dl is better?

<dl>
  <dt>Maven Wrapper (Linux/Mac)</dt>
  <dd><pre lang="shell">./mvnw clean verify</pre></dd>
  <dt>Maven Wrapper (Windows)</dt>
  <dd><pre lang="shell">mvnw.cmd clean verify</pre></dd>
  <dt>Maven (command-line)</dt>
  <dd><pre lang="shell">mvn clean verify</pre></dd>
  <dt>Maven (command-line & setting jvmserver)</dt>
  <dd><pre lang="shell">mvn clean verify -Dcics.jvmserver=MYJVM</pre></dd>
</dl>

Plain markdown ftw!!!


Maven Wrapper (Linux/Mac):
```shell
./mvnw clean verify
```

Maven Wrapper (Windows):
```shell
mvnw.cmd clean verify
```

Maven (command-line):
```shell
mvn clean verify
```

Maven (command-line & setting jvmserver):
```shell
mvn clean verify -Dcics.jvmserver=MYJVM
```

