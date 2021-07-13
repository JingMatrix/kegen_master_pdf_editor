# Keygen for [Master PDF Editor](https://code-industry.net/masterpdfeditor/) 5.x

The Pascal code is written by [RadiXX11](https://radixx11rce2.blogspot.com/p/source-code.html). I test `bin\Keygen.exe` on Linux using `Wine`, it works perfectly.

To reduce security concern, I am going to rewrite this keygen in Javascript and publish it on web.

As pointed out [here](https://aur.archlinux.org/packages/masterpdfeditor-libs-included/):

> I discovered that version **5.6.80** is the very last which can be registered with keygen.

All available verisons can be downloaded from internet archive:

1. [For Windows](https://web.archive.org/web/20200919162559if_/https://code-industry.net/public/MasterPDFEditor-setup.exe)
2. [For Ubuntu](https://web.archive.org/web/20210203220337/https://code-industry.net/public/master-pdf-editor-5.6.80-qt5.x86_64.deb)
3. [For MacOs](https://web.archive.org/web/20200919165215/https://code-industry.net/public/MasterPDFEditor.dmg)

For other versions, just try to find it out [here](https://web.archive.org/web/*/https://code-industry.net/public/*).

## demo

Now I finish my original goal, see [demo](https://jingmatrix.github.io/articles/writings/2019-12-21-Workflow/#writing-documents) here.

Please **be offline when you press `activate`**, or block the host reg.code-industry.net to disable online verification completely.

# FreePascal Support

Code in `src_fpc` can be compiled (and test) using FreePascal with command
```
cd src_fpc
fpc -Mobjfpc Keygen.pas
./Keygen
```
