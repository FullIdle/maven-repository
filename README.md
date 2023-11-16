# maven-repository
私人仓库

```groovy
repositories {
    maven {url 'https://raw.github.com/FullIdle/maven-repository/main/'}
    mavenCentral()
}
/*
我怕忘记
mvn deploy:deploy-file -DgroupId=com.exp.exp -DartifactId=ID -Dversion=1.0 -Dpackaging=jar -Dfile=文件path -Durl=file:///D:\MyProject\maven-repository -DrepositoryId=releases
*/
```
