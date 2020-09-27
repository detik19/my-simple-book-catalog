# Environment Requirement 
1. OS : Windows 10, MacOS, Linux Any Distro
2. Java -> OpenJDK 11 LTS https://developers.redhat.com/products/openjdk/download https://adoptopenjdk.net/
3. Build Tools -> Maven https://maven.apache.org/download.cgi
4. IDE -> Intelij IDEA, Netbeans, eclipse, VSCode, Spring Tool Suite https://spring.io/tools
5. Database -> PostgreSQL 12 https://www.postgresql.org/download/
6. SCM (Source Code Management / Versioning Control Management) -> Git https://git-scm.com/downloads
 

# Episode 01 
- [x] Setup Environment 
- [x] Create Remote Repository at Github
- [x] Create a new issue at Github
## Video
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/NtsXXVQXwZU/0.jpg)](http://www.youtube.com/watch?v=NtsXXVQXwZU)

# Episode 02
- [x] Create new spring boot project
  - [x] Spring Initializr 
    - You can [click this link to generate!](https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.3.4.RELEASE&packaging=jar&jvmVersion=11&groupId=com.subrutin&artifactId=book-catalog&name=book-catalog&description=My%20Simple%20Book%20Catalog&packageName=com.subrutin.bookcatalog&dependencies=lombok,devtools,web)
- [ ] Commit to git
- [ ] push to github

### Brief Introduction about Git
- Git is distributed Versioning Control Management
  - [x] Local Repository : Repository on Local Computer
    - create empty repository : <code>git init</code>. default use <code>master</code> branch
    - create new branch : <code>git checkout -b branchname</code>
    - add to staging (select files which plan to commit): <code>git add file</code>
    - commit staging to local repository : <code>git commit -m "message to commit"</code>
  - [x] Remote Repository : Repository on Git Server 
    - remote repository : Github https://github.com/detik19/my-simple-book-catalog
    - define remote repository : <code>git remote add remotename remoteurl</code>
    - push to remote repository: <code>git push -u repositoryname branchname</code>