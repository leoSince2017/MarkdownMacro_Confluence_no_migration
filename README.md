Confluence Markdown Macro - no dependence of migration
========================

[中文readme](README-Chinese.md)

I cloned this from Atlas-Authority/MarkdownMacro, then deleted the dependence of 'com.atlassian.migration', because this dependence will cause some bug.

If you got the same problem with me, just use it. You can:

(1) use this source-code and build by yourself

or

(2) download [.jar file](https://github.com/leoSince2017/MarkdownMacro_Confluence_no_migration/releases) and install

## how to build from source-code

(1) go to https://developer.atlassian.com/server/framework/atlassian-sdk/install-the-atlassian-sdk-on-a-linux-or-mac-system/ to install java and atlassian sdk

(2) download this repo

(3) run 'atlas-run' in terminal(bash/powershell/ or whatever)  (in the first run it will spend a lot of time downloading and installing something, don't warry :)

(4) if it has succeeded, you will be able to open http://localhost:1990/confluence . username and password are both 'admin'.

(5) take target/confluence-markdown-macro-*.jar 

(6) install this .jar file to your confluence

## how to install .jar plugin to your confluence

(1) open your confluence

(2) login as administrator

(3) install plugin by "manage apps", if you don't know, check https://support.atlassian.com/confluence-cloud/docs/manage-your-apps/#Manage-apps

(4) upload and install .jar file.

