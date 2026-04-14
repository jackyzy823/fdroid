1. Use Github Action + fdroidserver/fdroid to build and sign with my own certificate and publish it?

2. https://github.com/5ec1cff/FuseFixer/
    * no license
    * unknown maven repo 'https://api.xposed.info/' at settings.gradle.kts
        - https://github.com/XiaoTong6666/FuseFixer/blob/main/app/build.gradle.kts#L95 This variant use `:xposed-stubs` and its files in repo

        - and Proguard rules to avoid obfuscation on these code https://github.com/XiaoTong6666/FuseFixer/blob/68f70b11cdd723111bd8aab433d5ad33d414ac23/app/proguard-rules.pro#L23-L27

----
* https://f-droid.org/zh_Hans/docs/Submitting_to_F-Droid_Quick_Start_Guide/ The metadata template part should not be translated.
* How to write comment in metadata yml file ? rewritemeta will drop all comments
