![image](https://user-images.githubusercontent.com/83016880/146683920-320073f5-d9ea-4a92-9b94-62e0a48dbca5.jpg)
### Hi there 👋
Alien funs navigation code eco
<!--
**kenyahewitt/kenyahewitt** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
- name: Setup Java JDK
  uses: actions/setup-java@v2.4.0
  with:
    # The Java version to set up. Takes a whole or semver Java version. See examples of supported syntax in README file
    java-version: 
    # Java distribution. See the list of supported distributions in README file
    distribution: 
    # The package type (jdk, jre, jdk+fx, jre+fx)
    java-package: # optional, default is jdk
    # The architecture of the package
    architecture: # optional, default is x64
    # Path to where the compressed JDK is located
    jdkFile: # optional
    # Set this option if you want the action to check for the latest available version that satisfies the version spec
    check-latest: # optional
    # ID of the distributionManagement repository in the pom.xml file. Default is `github`
    server-id: # optional, default is github
    # Environment variable name for the username for authentication to the Apache Maven repository. Default is $GITHUB_ACTOR
    server-username: # optional, default is GITHUB_ACTOR
    # Environment variable name for password or token for authentication to the Apache Maven repository. Default is $GITHUB_TOKEN
    server-password: # optional, default is GITHUB_TOKEN
    # Path to where the settings.xml file will be written. Default is ~/.m2.
    settings-path: # optional
    # Overwrite the settings.xml file if it exists. Default is "true".
    overwrite-settings: # optional, default is true
    # GPG private key to import. Default is empty string.
    gpg-private-key: # optional
    # Environment variable name for the GPG private key passphrase. Default is $GPG_PASSPHRASE.
    gpg-passphrase: # optional
    # Name of the build platform to cache dependencies. It can be "maven" or "gradle".
    cache: # optional
    # Workaround to pass job status to post job step. This variable is not intended for manual setting
    job-status: # optional, default is ${{ job.status }}
    - name: Cache
  uses: actions/cache@v2.1.7
  with:
    # A list of files, directories, and wildcard patterns to cache and restore
    path: 
    # An explicit key for restoring and saving the cache
    key: 
    # An ordered list of keys to use for restoring the cache if no cache hit occurred for key
    restore-keys: # optional
    # The chunk size used to split up large files during upload, in bytes
    upload-chunk-size: # optional
