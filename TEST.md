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
    <td>Maven (command-line)</td>
    <td><pre lang="shell">mvn clean verify</pre></td>
  </tr>
  <tr>
    <td>Maven (command-line & setting jvmserver)</td>
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
