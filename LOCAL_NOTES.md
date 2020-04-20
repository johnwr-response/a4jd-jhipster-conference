# Notes
```
cd gateway
jhipster import-jdl ./src/main/resources/jdl/conference-jdl.jh
./mvnw
cd conference
jhipster import-jdl ../gateway/src/main/resources/jdl/conference-jdl.jh
./mvnw
```



# Git
```
cd gateway
git add .
git remote add origin https://github.com/johnwr-response/a4jd-jhipster-gateway.git
git push origin master
cd conference
git add .
git remote add origin https://github.com/johnwr-response/a4jd-jhipster-conference.git
git push origin master
```

# JHipster Conference Application
```
mkdir conference
cd conference
jhipster
./mvnw
```

# JHipster Registry
```
git clone https://github.com/jhipster/jhipster-registry registry
cd registry
yarn
./mvnw
```

# JHipster Gateway
```
mkdir gateway
cd gateway
jhipster
./mvnw
yarn start

```
