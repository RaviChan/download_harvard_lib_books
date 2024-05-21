# download_harvard_lib_books

### Repository Description
Harvard Library possesses numerous facsimile editions of ancient books. This program automates the bulk downloading process by locating the link to the first image and subsequently downloading the rest.
Certainly! Here is the detailed description for your GitHub repository in English:

---
#### Example Book
The example used in this repository is *Daiweiji Shiji*, Xianfeng Yiwei [1859] edition. 

- Book link: [https://curiosity.lib.harvard.edu/chinese-rare-books/catalog/49-990081640940203941](https://curiosity.lib.harvard.edu/chinese-rare-books/catalog/49-990081640940203941)
- First image link: [https://iiif.lib.harvard.edu/manifests/view/drs:430970820$1i](https://iiif.lib.harvard.edu/manifests/view/drs:430970820$1i)

To download the images, locate the link for the first image from the right side download option, as shown in the screenshot below:

![[demo.png]]

The image link obtained is: [https://ids.lib.harvard.edu/ids/iiif/430970822/full/1200,/0/default.jpg?download&caption](https://ids.lib.harvard.edu/ids/iiif/430970822/full/1200,/0/default.jpg?download&caption)

Then, replace the numeric part of the link in the code. This book has 252 pages, so the download number can be set to 252.

---
