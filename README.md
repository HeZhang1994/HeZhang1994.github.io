# Personal Website Development

[![image](https://img.shields.io/badge/license-MIT-lightgrey.svg)]()
[![image](https://img.shields.io/badge/lagrange-html%20%7C%20css-blue.svg)]()
[![image](https://img.shields.io/badge/status-stable-brightgreen.svg)]()
[![image](https://img.shields.io/badge/build-passing-brightgreen.svg)]()

This is an **HTML-CSS** implementation of developing personal website with **GitHub.io**.

Many thanks to [TEMPLATED](http://templated.co) for providing the source template in `SourceTemplate_privy/`.

## Contents

- `audio/` - The folder that contains the audio used in website.

- `images/` - The folder that contains the images used in website.

- `default.css` - The CSS file that defines the characteristics of website.

- `index.html` - The HTML source file of home page.

- `hz***.html` - The HTML source file of child web page.

- `google***.html` - The verification file of Google search engine.

<!--- `baidu***.html` - The verification file of Baidu search engine.-->

## Website Configuration and Establishment

The following procedures for setting up a website with GitHub.io are partly recapitulated from [here](https://pages.github.com/). For detailed information of how to use `git`, see this [online tutorial](https://chryswoods.com/beginning_git/) provided by [Christopher Woods](https://github.com/chryswoods).

1. Configure your GitHub client on local computer.
```bash
$ git config --global user.email "xxx@xxx.xxx"
# Replace 'xxx@xxx.xxx' with your GitHub registered email.
# E.g., $ git config --global user.email "hz@gmail.com".

$ git config --global user.name "aaa"
# Replace 'aaa' with your GitHub user name.
# E.g., $ git config --global user.name "hz".
```

2. Create a public repository called `aaa.github.io` on GitHub, where `aaa` should be your GitHub user name. You can now use the website templates provided by GitHub (see [here](https://blog.csdn.net/renfufei/article/details/37725057)), or continue the configuration and use other templates later.

3. Clone `aaa.github.io` repository to local computer in Terminal.
```bash
$ git clone https://github.com/aaa/aaa.github.io
```

4. Add some contents to the website (this will create `index.html`) in Terminal.
```bash
$ cd aaa.github.io
~$ echo "Hello World" > index.html
~$ git add --all
~$ git commit -m "Initial commit"
~$ git push -u origin master
```

5. After a few minutes, open __https://aaa.github.io/__ on browser and you will see "Hello World" on the website.

6. Now you can develop the website by editing/creating `default.css`, `index.html`, and other HTML files.

## Website Verification on Google Search Engine

Verifying the website on search engines provides your ownership to this website. The following procedures show how to verify the website __https://aaa.github.io/__ on Google search engine.

<img src="https://github.com/HeZhang1994/HeZhang1994.github.io/blob/master/images/Website_GoogleVerification.gif" height="350">

1. Open [Google Search Console](https://search.google.com/search-console/about) and log in with your Google account.

2. Click top-left drop-down arrow and then click "+ Add property".

3. Type `https://aaa.github.io/` in the input box of "URL prefix" tag and then click "CONTINUE".

4. Download the verification file `google***.html` and upload it to `aaa.github.io` repository.

5. Go back to the verification page. Wait a few minutes and click "VERIFY".

6. Verification on Google search engine is accomplished.

<!--
### Baidu Search Engine
1. Open [Baidu Resource Platform](https://ziyuan.baidu.com/) and log in with Baidu account.
2. Click "Add Website" and complete user information (if required).
3. Type __https://aaa.github.io__ in the input box and click "NEXT".
4. Select website attribute (e.g., Information Technology).
5. Select verification method - document verification.
6. Download the verification file `baidu_verify***.html` and upload it to your GitHub.io repository.
7. Go back to the verification page. Wait a few minutes and click "COMPLETE VERIFICATION".
8. Complete verification on Baidu search engine!
-->

## Useful Links

* Online HTML and CSS editor - [CodePen](https://codepen.io/)

* Online picture resizer - [Picresize](http://www.picresize.com/)

* Online picture format converter - [Online-Converter](https://www.online-convert.com/)

<br>

<i>Please star this repository if you found its content useful. Thank you very much. ^_^</i>

<i>如果该程序对您有帮助，请为该程序加星支持哈，非常感谢。^_^</i>

<i>Last updated: 20/03/2019</i>
