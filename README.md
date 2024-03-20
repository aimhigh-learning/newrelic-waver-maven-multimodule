# newrelic-waver-maven-multimodule

### How i can build 

```
mvn clean install
```

### How to deploy in nexus 
```
mvn clean package

cd /make-assembly

mvn deploy -gs nexus-maven-settings.xml -DaltReleaseDeploymentRepository=nexus::default::https://nexus.prospecta.com/repository/local-release/ -DaltSnapshotDeploymentRepository=nexus::default::https://nexus.prospecta.com/repository/local-snapshot/
```



