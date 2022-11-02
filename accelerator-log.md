# Accelerator Log

## Options
```json
{
  "bsGitBranch" : "main",
  "bsGitRepository" : "github.com?owner=billglover&repo=tanzu-wld-java-web-app",
  "projectName" : "tanzu-wld-java-web-app",
  "repositoryPrefix" : "harbor.tap.tanzu.xyz/tap"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ ┃ engine.transformations[0].validated.merge (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/*]
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/FETCH_HEAD matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/HEAD matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/config matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/description matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/hooks/README.sample matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/index matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/info/exclude matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/HEAD matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/refs/heads/main matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/refs/remotes/origin/main matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/03/ce5d083673a7b724decd088e34d6e9c5d048d6 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/07/7feeedb6563a944bde8d466cc48644bee49e6d matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/0a/6012f8c0b7cf55dd7f28b648fafc0facc5d55d matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/11/8237944a6ff852c57fcecf3ecd0724df0a917e matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/1a/ea20f0903114f5e5947ffb18091cfaf83961b6 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/1f/eb4df0e5dc9afb8643034de3a22ed261ac4d3e matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/20/e4bd85661f5fbc86e0a8aac3934ddabe776160 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/21/0e4c58a3eb7e84b66578915ee612c97e26c100 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/23/10b43e879e683e39a7020e6de19dd717d529fd matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/34/c32ad871bdb4ee343b43e53edefc3406c30374 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/3d/14d7704f923405fb4c836d527a832e1e59bf6b matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/3e/d127c721d0f37a5fef01214c061b9c719adf0e matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/42/7417b60d598d0099a7d786078c983f9dd6bd02 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/44/a9c899f7a28e32dc32f21678ef69fcf199a216 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/4d/72d9d9ae2cf4c2547065d13b1806aefbc2f799 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/62/987a562be9ac4567b2f6d7a77fb6b98fff4787 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/69/b1a938c78152c6a1a0fbf252a52303b417685f matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/6e/4717d06bfec86f6bab092909e2738ef411ad66 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/88/ced25d2ab3cfb123d1d83caadbcb6b0ee466fa matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/97/f8728d666b2fff48ddf6fb400a28dbf90761d9 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9d/ba70950d24a881aa918f09d7f56294cdba0bab matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9e/26dfeeb6e641a33dae4961196235bdb965b21b matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9e/9ebbb478bfe5915506dbbb7bc5a3d92fbcd62b matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9f/ee8078672d1058f640d20d0a1cd7fa878b3e0d matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a1/6b5431b4c3cab50323a3f558003fd0abd87dad matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a1/c2a238a965f004ff76978ac1086aa6fe95caea matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a6/2f7ed457a1f67d7ceb21f40e282769621d1f27 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ac/9e6a421dace18aeb74fc5d40cea34cd28df0cd matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ba/31425e100a2dab12f5e342d7c2c1b5dc405b85 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/bd/649ae6f48ee8d111359b436d0c4f7c1a5e5c58 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c0/ef0537300c19554ff639375d3d39d742ad2ef6 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c3/d9c89e1d9e49051251a1084d2459ca6f74c407 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c8/d43372c986d97911cdc21bd87e0cbe3d83bdda matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c9/bf7d9ba1c467d3615c667763af1101294a5b11 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ca/a4de9445e8bc3ded61f27f2328a79375f43a33 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/d1/ac0e72a0ef0ce8beec8551dea8b6d46a8fd8cb matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/da/3ff4d7e7d79e81202ca73f62a564d7249718e2 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e0/8148388878b43dde7de71c3cbae5abee25c393 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e1/3543436767a499ec2759a18293d19c52fc613a matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e2/0bee9e53f14ad26b2680f346d59056b4862d63 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/fc/5080baa920289cecda85544966aac11b1ab119 matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/refs/heads/main matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/refs/remotes/origin/main matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug grype.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/META-INF/build-info.properties matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/example/springboot/Application.class matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/example/springboot/HelloController.class matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┗ Debug target/test-classes/com/example/springboot/HelloControllerTest.class matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo>.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/FETCH_HEAD matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/HEAD matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/config matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/description matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/hooks/README.sample matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/index matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/info/exclude matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/HEAD matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/refs/heads/main matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/refs/remotes/origin/main matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/03/ce5d083673a7b724decd088e34d6e9c5d048d6 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/07/7feeedb6563a944bde8d466cc48644bee49e6d matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/0a/6012f8c0b7cf55dd7f28b648fafc0facc5d55d matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/11/8237944a6ff852c57fcecf3ecd0724df0a917e matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/1a/ea20f0903114f5e5947ffb18091cfaf83961b6 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/1f/eb4df0e5dc9afb8643034de3a22ed261ac4d3e matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/20/e4bd85661f5fbc86e0a8aac3934ddabe776160 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/21/0e4c58a3eb7e84b66578915ee612c97e26c100 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/23/10b43e879e683e39a7020e6de19dd717d529fd matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/34/c32ad871bdb4ee343b43e53edefc3406c30374 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/3d/14d7704f923405fb4c836d527a832e1e59bf6b matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/3e/d127c721d0f37a5fef01214c061b9c719adf0e matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/42/7417b60d598d0099a7d786078c983f9dd6bd02 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/44/a9c899f7a28e32dc32f21678ef69fcf199a216 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/4d/72d9d9ae2cf4c2547065d13b1806aefbc2f799 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/62/987a562be9ac4567b2f6d7a77fb6b98fff4787 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/69/b1a938c78152c6a1a0fbf252a52303b417685f matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/6e/4717d06bfec86f6bab092909e2738ef411ad66 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/88/ced25d2ab3cfb123d1d83caadbcb6b0ee466fa matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/97/f8728d666b2fff48ddf6fb400a28dbf90761d9 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9d/ba70950d24a881aa918f09d7f56294cdba0bab matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9e/26dfeeb6e641a33dae4961196235bdb965b21b matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9e/9ebbb478bfe5915506dbbb7bc5a3d92fbcd62b matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9f/ee8078672d1058f640d20d0a1cd7fa878b3e0d matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a1/6b5431b4c3cab50323a3f558003fd0abd87dad matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a1/c2a238a965f004ff76978ac1086aa6fe95caea matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a6/2f7ed457a1f67d7ceb21f40e282769621d1f27 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ac/9e6a421dace18aeb74fc5d40cea34cd28df0cd matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ba/31425e100a2dab12f5e342d7c2c1b5dc405b85 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/bd/649ae6f48ee8d111359b436d0c4f7c1a5e5c58 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c0/ef0537300c19554ff639375d3d39d742ad2ef6 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c3/d9c89e1d9e49051251a1084d2459ca6f74c407 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c8/d43372c986d97911cdc21bd87e0cbe3d83bdda matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c9/bf7d9ba1c467d3615c667763af1101294a5b11 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ca/a4de9445e8bc3ded61f27f2328a79375f43a33 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/d1/ac0e72a0ef0ce8beec8551dea8b6d46a8fd8cb matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/da/3ff4d7e7d79e81202ca73f62a564d7249718e2 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e0/8148388878b43dde7de71c3cbae5abee25c393 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e1/3543436767a499ec2759a18293d19c52fc613a matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e2/0bee9e53f14ad26b2680f346d59056b4862d63 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/fc/5080baa920289cecda85544966aac11b1ab119 matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/refs/heads/main matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/refs/remotes/origin/main matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE.md didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug grype.yaml matched [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/META-INF/build-info.properties didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/example/springboot/Application.class didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/example/springboot/HelloController.class didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┗ ┗ Debug target/test-classes/com/example/springboot/HelloControllerTest.class didn't match [config/*.yaml, Tiltfile, README.md, grype.yaml, catalog/*.yaml, .github/**, .git/**, accelerator.yaml] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [Tiltfile]
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/FETCH_HEAD didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/HEAD didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/config didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/description didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/hooks/README.sample didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/index didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/info/exclude didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/HEAD didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/refs/heads/main didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/refs/remotes/origin/main didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/03/ce5d083673a7b724decd088e34d6e9c5d048d6 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/07/7feeedb6563a944bde8d466cc48644bee49e6d didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/0a/6012f8c0b7cf55dd7f28b648fafc0facc5d55d didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/11/8237944a6ff852c57fcecf3ecd0724df0a917e didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/1a/ea20f0903114f5e5947ffb18091cfaf83961b6 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/1f/eb4df0e5dc9afb8643034de3a22ed261ac4d3e didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/20/e4bd85661f5fbc86e0a8aac3934ddabe776160 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/21/0e4c58a3eb7e84b66578915ee612c97e26c100 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/23/10b43e879e683e39a7020e6de19dd717d529fd didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/34/c32ad871bdb4ee343b43e53edefc3406c30374 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/3d/14d7704f923405fb4c836d527a832e1e59bf6b didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/3e/d127c721d0f37a5fef01214c061b9c719adf0e didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/42/7417b60d598d0099a7d786078c983f9dd6bd02 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/44/a9c899f7a28e32dc32f21678ef69fcf199a216 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/4d/72d9d9ae2cf4c2547065d13b1806aefbc2f799 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/62/987a562be9ac4567b2f6d7a77fb6b98fff4787 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/69/b1a938c78152c6a1a0fbf252a52303b417685f didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/6e/4717d06bfec86f6bab092909e2738ef411ad66 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/88/ced25d2ab3cfb123d1d83caadbcb6b0ee466fa didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/97/f8728d666b2fff48ddf6fb400a28dbf90761d9 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9d/ba70950d24a881aa918f09d7f56294cdba0bab didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9e/26dfeeb6e641a33dae4961196235bdb965b21b didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9e/9ebbb478bfe5915506dbbb7bc5a3d92fbcd62b didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9f/ee8078672d1058f640d20d0a1cd7fa878b3e0d didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a1/6b5431b4c3cab50323a3f558003fd0abd87dad didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a1/c2a238a965f004ff76978ac1086aa6fe95caea didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a6/2f7ed457a1f67d7ceb21f40e282769621d1f27 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ac/9e6a421dace18aeb74fc5d40cea34cd28df0cd didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ba/31425e100a2dab12f5e342d7c2c1b5dc405b85 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/bd/649ae6f48ee8d111359b436d0c4f7c1a5e5c58 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c0/ef0537300c19554ff639375d3d39d742ad2ef6 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c3/d9c89e1d9e49051251a1084d2459ca6f74c407 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c8/d43372c986d97911cdc21bd87e0cbe3d83bdda didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c9/bf7d9ba1c467d3615c667763af1101294a5b11 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ca/a4de9445e8bc3ded61f27f2328a79375f43a33 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/d1/ac0e72a0ef0ce8beec8551dea8b6d46a8fd8cb didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/da/3ff4d7e7d79e81202ca73f62a564d7249718e2 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e0/8148388878b43dde7de71c3cbae5abee25c393 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e1/3543436767a499ec2759a18293d19c52fc613a didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e2/0bee9e53f14ad26b2680f346d59056b4862d63 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/fc/5080baa920289cecda85544966aac11b1ab119 didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/refs/heads/main didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/refs/remotes/origin/main didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE.md didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug grype.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/META-INF/build-info.properties didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/example/springboot/Application.class didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/example/springboot/HelloController.class didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug target/test-classes/com/example/springboot/HelloControllerTest.class didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [tanzu-java-web-app->tanzu-wld-java-web-a...(truncated)]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [your-registry.io/project->harbor.tap.tanzu.xyz...(truncated)]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, Combo)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/*.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/FETCH_HEAD didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/HEAD didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/config didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/description didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/hooks/README.sample didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/index didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/info/exclude didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/HEAD didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/refs/heads/main didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/refs/remotes/origin/main didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/03/ce5d083673a7b724decd088e34d6e9c5d048d6 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/07/7feeedb6563a944bde8d466cc48644bee49e6d didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/0a/6012f8c0b7cf55dd7f28b648fafc0facc5d55d didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/11/8237944a6ff852c57fcecf3ecd0724df0a917e didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/1a/ea20f0903114f5e5947ffb18091cfaf83961b6 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/1f/eb4df0e5dc9afb8643034de3a22ed261ac4d3e didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/20/e4bd85661f5fbc86e0a8aac3934ddabe776160 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/21/0e4c58a3eb7e84b66578915ee612c97e26c100 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/23/10b43e879e683e39a7020e6de19dd717d529fd didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/34/c32ad871bdb4ee343b43e53edefc3406c30374 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/3d/14d7704f923405fb4c836d527a832e1e59bf6b didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/3e/d127c721d0f37a5fef01214c061b9c719adf0e didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/42/7417b60d598d0099a7d786078c983f9dd6bd02 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/44/a9c899f7a28e32dc32f21678ef69fcf199a216 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/4d/72d9d9ae2cf4c2547065d13b1806aefbc2f799 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/62/987a562be9ac4567b2f6d7a77fb6b98fff4787 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/69/b1a938c78152c6a1a0fbf252a52303b417685f didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/6e/4717d06bfec86f6bab092909e2738ef411ad66 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/88/ced25d2ab3cfb123d1d83caadbcb6b0ee466fa didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/97/f8728d666b2fff48ddf6fb400a28dbf90761d9 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9d/ba70950d24a881aa918f09d7f56294cdba0bab didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9e/26dfeeb6e641a33dae4961196235bdb965b21b didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9e/9ebbb478bfe5915506dbbb7bc5a3d92fbcd62b didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9f/ee8078672d1058f640d20d0a1cd7fa878b3e0d didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a1/6b5431b4c3cab50323a3f558003fd0abd87dad didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a1/c2a238a965f004ff76978ac1086aa6fe95caea didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a6/2f7ed457a1f67d7ceb21f40e282769621d1f27 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ac/9e6a421dace18aeb74fc5d40cea34cd28df0cd didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ba/31425e100a2dab12f5e342d7c2c1b5dc405b85 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/bd/649ae6f48ee8d111359b436d0c4f7c1a5e5c58 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c0/ef0537300c19554ff639375d3d39d742ad2ef6 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c3/d9c89e1d9e49051251a1084d2459ca6f74c407 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c8/d43372c986d97911cdc21bd87e0cbe3d83bdda didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c9/bf7d9ba1c467d3615c667763af1101294a5b11 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ca/a4de9445e8bc3ded61f27f2328a79375f43a33 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/d1/ac0e72a0ef0ce8beec8551dea8b6d46a8fd8cb didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/da/3ff4d7e7d79e81202ca73f62a564d7249718e2 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e0/8148388878b43dde7de71c3cbae5abee25c393 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e1/3543436767a499ec2759a18293d19c52fc613a didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e2/0bee9e53f14ad26b2680f346d59056b4862d63 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/fc/5080baa920289cecda85544966aac11b1ab119 didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/refs/heads/main didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/refs/remotes/origin/main didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE.md didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug grype.yaml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/META-INF/build-info.properties didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/example/springboot/Application.class didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/example/springboot/HelloController.class didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug target/test-classes/com/example/springboot/HelloControllerTest.class didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [: tanzu-java-web-app->: tanzu-wld-java-web...(truncated)]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseFirst))
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[0].validated.chain (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Combo, Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[0].validated.chain.transformations[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository != null) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[0].validated.chain.transformations[0].chain (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository != null) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[0].validated.chain.transformations[0].chain.transformations[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Let(symbols, in: Chain(Include, chain...))
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[0].validated.chain.transformations[0].chain.transformations[0].<combo> (Let)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Adding symbol repoUrl with value 'https://github.com?owner=billglover&repo=tanzu-wld-java-web-app'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[0].validated.chain.transformations[0].chain.transformations[0].<combo>.in (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, OpenRewriteRecipe, ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[0].validated.chain.transformations[0].chain.transformations[0].<combo>.in.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/workload.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [**/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ╺ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[0].validated.chain.transformations[0].chain.transformations[0].<combo>.in.transformations[1] (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[0].validated.chain.transformations[0].chain.transformations[0].<combo>.in.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex '(?<beforeBranch>[\s\S]+)(?<branch>branch: [\S]+)(?<rest>[\S\s]*)' with '${beforeBranch}branc...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[0].validated.chain.transformations[0].chain.transformations[0].<combo>.in.transformations[3] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ ┗  Info Will replace regex '(?<beforeSubPath>[\s\S]+)(?<subPath>subPath: [\S]+)(?<rest>[\S\s]*)' with '${beforeSubPath}${re...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[0].validated.chain.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository == null) evaluated to false
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ null ()
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[0].sources[1].include (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2].merge.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┗ ┗ ┗ Debug Multiple representations for path 'config/workload.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/FETCH_HEAD didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/HEAD didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/config didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/description didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/hooks/README.sample didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/index didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/info/exclude didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/HEAD didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/refs/heads/main didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/refs/remotes/origin/main didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/03/ce5d083673a7b724decd088e34d6e9c5d048d6 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/07/7feeedb6563a944bde8d466cc48644bee49e6d didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/0a/6012f8c0b7cf55dd7f28b648fafc0facc5d55d didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/11/8237944a6ff852c57fcecf3ecd0724df0a917e didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/1a/ea20f0903114f5e5947ffb18091cfaf83961b6 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/1f/eb4df0e5dc9afb8643034de3a22ed261ac4d3e didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/20/e4bd85661f5fbc86e0a8aac3934ddabe776160 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/21/0e4c58a3eb7e84b66578915ee612c97e26c100 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/23/10b43e879e683e39a7020e6de19dd717d529fd didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/34/c32ad871bdb4ee343b43e53edefc3406c30374 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/3d/14d7704f923405fb4c836d527a832e1e59bf6b didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/3e/d127c721d0f37a5fef01214c061b9c719adf0e didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/42/7417b60d598d0099a7d786078c983f9dd6bd02 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/44/a9c899f7a28e32dc32f21678ef69fcf199a216 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/4d/72d9d9ae2cf4c2547065d13b1806aefbc2f799 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/62/987a562be9ac4567b2f6d7a77fb6b98fff4787 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/69/b1a938c78152c6a1a0fbf252a52303b417685f didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/6e/4717d06bfec86f6bab092909e2738ef411ad66 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/88/ced25d2ab3cfb123d1d83caadbcb6b0ee466fa didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/97/f8728d666b2fff48ddf6fb400a28dbf90761d9 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9d/ba70950d24a881aa918f09d7f56294cdba0bab didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9e/26dfeeb6e641a33dae4961196235bdb965b21b didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9e/9ebbb478bfe5915506dbbb7bc5a3d92fbcd62b didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9f/ee8078672d1058f640d20d0a1cd7fa878b3e0d didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a1/6b5431b4c3cab50323a3f558003fd0abd87dad didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a1/c2a238a965f004ff76978ac1086aa6fe95caea didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a6/2f7ed457a1f67d7ceb21f40e282769621d1f27 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ac/9e6a421dace18aeb74fc5d40cea34cd28df0cd didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ba/31425e100a2dab12f5e342d7c2c1b5dc405b85 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/bd/649ae6f48ee8d111359b436d0c4f7c1a5e5c58 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c0/ef0537300c19554ff639375d3d39d742ad2ef6 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c3/d9c89e1d9e49051251a1084d2459ca6f74c407 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c8/d43372c986d97911cdc21bd87e0cbe3d83bdda didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c9/bf7d9ba1c467d3615c667763af1101294a5b11 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ca/a4de9445e8bc3ded61f27f2328a79375f43a33 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/d1/ac0e72a0ef0ce8beec8551dea8b6d46a8fd8cb didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/da/3ff4d7e7d79e81202ca73f62a564d7249718e2 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e0/8148388878b43dde7de71c3cbae5abee25c393 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e1/3543436767a499ec2759a18293d19c52fc613a didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e2/0bee9e53f14ad26b2680f346d59056b4862d63 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/fc/5080baa920289cecda85544966aac11b1ab119 didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/refs/heads/main didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/refs/remotes/origin/main didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug grype.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/META-INF/build-info.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/example/springboot/Application.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/example/springboot/HelloController.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug target/test-classes/com/example/springboot/HelloControllerTest.class didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo>.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [tanzu-java-web-app->tanzu-wld-java-web-a...(truncated)]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [catalog/*.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/FETCH_HEAD didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/HEAD didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/config didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/description didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/hooks/README.sample didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/index didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/info/exclude didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/HEAD didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/refs/heads/main didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/logs/refs/remotes/origin/main didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/03/ce5d083673a7b724decd088e34d6e9c5d048d6 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/07/7feeedb6563a944bde8d466cc48644bee49e6d didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/0a/6012f8c0b7cf55dd7f28b648fafc0facc5d55d didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/11/8237944a6ff852c57fcecf3ecd0724df0a917e didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/1a/ea20f0903114f5e5947ffb18091cfaf83961b6 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/1f/eb4df0e5dc9afb8643034de3a22ed261ac4d3e didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/20/e4bd85661f5fbc86e0a8aac3934ddabe776160 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/21/0e4c58a3eb7e84b66578915ee612c97e26c100 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/23/10b43e879e683e39a7020e6de19dd717d529fd didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/34/c32ad871bdb4ee343b43e53edefc3406c30374 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/3d/14d7704f923405fb4c836d527a832e1e59bf6b didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/3e/d127c721d0f37a5fef01214c061b9c719adf0e didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/42/7417b60d598d0099a7d786078c983f9dd6bd02 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/44/a9c899f7a28e32dc32f21678ef69fcf199a216 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/4d/72d9d9ae2cf4c2547065d13b1806aefbc2f799 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/62/987a562be9ac4567b2f6d7a77fb6b98fff4787 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/69/b1a938c78152c6a1a0fbf252a52303b417685f didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/6e/4717d06bfec86f6bab092909e2738ef411ad66 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/88/ced25d2ab3cfb123d1d83caadbcb6b0ee466fa didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/97/f8728d666b2fff48ddf6fb400a28dbf90761d9 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9d/ba70950d24a881aa918f09d7f56294cdba0bab didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9e/26dfeeb6e641a33dae4961196235bdb965b21b didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9e/9ebbb478bfe5915506dbbb7bc5a3d92fbcd62b didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/9f/ee8078672d1058f640d20d0a1cd7fa878b3e0d didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a1/6b5431b4c3cab50323a3f558003fd0abd87dad didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a1/c2a238a965f004ff76978ac1086aa6fe95caea didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/a6/2f7ed457a1f67d7ceb21f40e282769621d1f27 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ac/9e6a421dace18aeb74fc5d40cea34cd28df0cd didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ba/31425e100a2dab12f5e342d7c2c1b5dc405b85 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/bd/649ae6f48ee8d111359b436d0c4f7c1a5e5c58 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c0/ef0537300c19554ff639375d3d39d742ad2ef6 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c3/d9c89e1d9e49051251a1084d2459ca6f74c407 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c8/d43372c986d97911cdc21bd87e0cbe3d83bdda didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/c9/bf7d9ba1c467d3615c667763af1101294a5b11 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/ca/a4de9445e8bc3ded61f27f2328a79375f43a33 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/d1/ac0e72a0ef0ce8beec8551dea8b6d46a8fd8cb didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/da/3ff4d7e7d79e81202ca73f62a564d7249718e2 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e0/8148388878b43dde7de71c3cbae5abee25c393 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e1/3543436767a499ec2759a18293d19c52fc613a didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/e2/0bee9e53f14ad26b2680f346d59056b4862d63 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/objects/fc/5080baa920289cecda85544966aac11b1ab119 didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/refs/heads/main didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .git/refs/remotes/origin/main didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug grype.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/META-INF/build-info.properties didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/application.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/example/springboot/Application.class didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug target/classes/com/example/springboot/HelloController.class didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug target/test-classes/com/example/springboot/HelloControllerTest.class didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[1] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [tanzu-java-web-app->tanzu-wld-java-web-a...(truncated)]
┃ ┗ ┗ ╺ engine.transformations[0].validated.merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
