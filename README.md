# simplify-cloud-dependencies-parent
Simplify Cloud Build Dependencies

## Deploy

```bash
heyuqiang@heyuqiangdeMBP simplify-cloud-dependencies-parent % mvn clean deploy -P central
[INFO] Scanning for projects...
[INFO] 
[INFO] ---------< com.ieooc.cloud:simplify-cloud-dependencies-parent >---------
[INFO] Building simplify-cloud-dependencies-parent 1.0.0.RELEASE
[INFO] --------------------------------[ pom ]---------------------------------
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ simplify-cloud-dependencies-parent ---
[INFO] 
[INFO] --- flatten-maven-plugin:1.2.2:clean (flatten-clean) @ simplify-cloud-dependencies-parent ---
[INFO] 
[INFO] --- flatten-maven-plugin:1.2.2:flatten (flatten) @ simplify-cloud-dependencies-parent ---
[INFO] Generating flattened POM of project com.ieooc.cloud:simplify-cloud-dependencies-parent:pom:1.0.0.RELEASE...
[INFO] 
[INFO] --- maven-gpg-plugin:1.6:sign (sign-artifacts) @ simplify-cloud-dependencies-parent ---
[INFO] 
[INFO] --- maven-install-plugin:2.4:install (default-install) @ simplify-cloud-dependencies-parent ---
[INFO] Installing /Users/heyuqiang/IdeaProjects/simplify-cloud-dependencies-parent/.flattened-pom.xml to /Users/heyuqiang/.m2/repository/com/ieooc/cloud/simplify-cloud-dependencies-parent/1.0.0.RELEASE/simplify-cloud-dependencies-parent-1.0.0.RELEASE.pom
[INFO] Installing /Users/heyuqiang/IdeaProjects/simplify-cloud-dependencies-parent/target/simplify-cloud-dependencies-parent-1.0.0.RELEASE.pom.asc to /Users/heyuqiang/.m2/repository/com/ieooc/cloud/simplify-cloud-dependencies-parent/1.0.0.RELEASE/simplify-cloud-dependencies-parent-1.0.0.RELEASE.pom.asc
[INFO] 
[INFO] --- maven-deploy-plugin:2.7:deploy (default-deploy) @ simplify-cloud-dependencies-parent ---
Uploading to sonatype-nexus-staging: https://oss.sonatype.org/service/local/staging/deploy/maven2/com/ieooc/cloud/simplify-cloud-dependencies-parent/1.0.0.RELEASE/simplify-cloud-dependencies-parent-1.0.0.RELEASE.pom
Uploaded to sonatype-nexus-staging: https://oss.sonatype.org/service/local/staging/deploy/maven2/com/ieooc/cloud/simplify-cloud-dependencies-parent/1.0.0.RELEASE/simplify-cloud-dependencies-parent-1.0.0.RELEASE.pom (5.3 kB at 51 B/s)
Downloading from sonatype-nexus-staging: https://oss.sonatype.org/service/local/staging/deploy/maven2/com/ieooc/cloud/simplify-cloud-dependencies-parent/maven-metadata.xml
Uploading to sonatype-nexus-staging: https://oss.sonatype.org/service/local/staging/deploy/maven2/com/ieooc/cloud/simplify-cloud-dependencies-parent/maven-metadata.xml
Uploaded to sonatype-nexus-staging: https://oss.sonatype.org/service/local/staging/deploy/maven2/com/ieooc/cloud/simplify-cloud-dependencies-parent/maven-metadata.xml (345 B at 1 B/s)
Uploading to sonatype-nexus-staging: https://oss.sonatype.org/service/local/staging/deploy/maven2/com/ieooc/cloud/simplify-cloud-dependencies-parent/1.0.0.RELEASE/simplify-cloud-dependencies-parent-1.0.0.RELEASE.pom.asc
Uploaded to sonatype-nexus-staging: https://oss.sonatype.org/service/local/staging/deploy/maven2/com/ieooc/cloud/simplify-cloud-dependencies-parent/1.0.0.RELEASE/simplify-cloud-dependencies-parent-1.0.0.RELEASE.pom.asc (488 B at 601 B/s)
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  06:04 min
[INFO] Finished at: 2020-08-04T00:49:47+08:00
[INFO] ------------------------------------------------------------------------
heyuqiang@heyuqiangdeMBP simplify-cloud-dependencies-parent % 
```
