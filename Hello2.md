﻿NonBanking System-ийн гарын авлага
===================

Системд нэвтрэх
---------------

Та http://192.168.1.125:8001/login хаягаар хандаж системд нэвтэрнэ.

----------


![enter image description here](https://lh3.googleusercontent.com/-FjfIJF9CUxs/WhPEPfseNCI/AAAAAAAAAHY/Igg7AxDtwMg_oZAYbVtKvaT2gufaSoFcQCLcBGAs/s0/login.png "login.png")

----------

> **Тайлбар:**

> - Имэйл талбарт нэвтрэх нэр, нууц үг талбарт системд нэвтрэх нууц үгээ оруулан нэвтрэх товчыг даран системд нэвтэрнэ.


Удирдлагын хэсэг
-------------

Энэ цонхонд өөрсдийн үйл ажиллагааны ерөнхий статик судалгааг диаграм болон хүснэгтээр харах боломжтой байна. Тухайлбал активын өсөлт бууралт, нийт хэдэн харилцагч байгаагаас хэдэн хувь нь ямар ямар үйлчилгээ авч буй талаар гэх мэт.

![enter image description here](https://lh3.googleusercontent.com/-JfWY0RFl_nE/WhPIT_pCoTI/AAAAAAAAAHo/pz0MPBzxbfMcnDRtsBuDRtf3k4cy9xHsACLcBGAs/s0/home.png "home.png")


Харилцагчийн хэсэг
-------------
Энэ цонхонд харилцагч бүртгэх, засварлах, устгах, лавлах үйлдлүүдийг хийнэ.

![enter image description here](https://lh3.googleusercontent.com/-InWXjxN9XkY/WhPL7WbDcAI/AAAAAAAAAH8/YhasqcDFTzUl4TIMSL-YREZX55kZ1OtuwCLcBGAs/s0/customer.png "customer.png")

#### <i class="icon-file"></i> Харилцагч бүртгэх

Харилцагч бүртгэх товчин дээр дарж харилцагч бүртгэх цонх уруу орно.

![enter image description here](https://lh3.googleusercontent.com/-eFbwN7VoWUk/WhPNYtaBfxI/AAAAAAAAAIQ/i3gRCfHLwVArW_w76QYCmkX90Snhutk-QCLcBGAs/s0/createCustomer.png "createCustomer.png")

> **Тайлбар:**

> - **Төрөл** - Тухайн харилцагчийн төрлийг сонгоно. Сонгох утгыг  хуудсанд тохируулна.
> - **Дугаар** - Харилцагчийн дугаарыг систем автоматаар олгоно.
> - **Регистерийн дугаар** - Харилцагчийн регистерийн дугаарыг бүртгэнэ.
> - **Овог** - Харилцагчийн овгийг бүртгэнэ.
> - **Нэр** - Харилцагчийн нэрийг бүртгэнэ.
> - **Цахим шуудан** - Харилцагчийн имэйл хаягийг бүртгэнэ.
> - **Утас** - Харилцагчийн утсыг бүртгэнэ.
> - **Хаяг** - Харилцагчийн хаягийг бүртгэнэ.

#### <i class="icon-pencil"></i>Харилцагч засварлах
Энэ хуудсанд харилцагчийн мэдээллийг засварлана.

![enter image description here](https://lh3.googleusercontent.com/-0ulsk8BdjVA/WhVGlpWk49I/AAAAAAAAAI8/kedDHYe3HKU4pySe-nYiFE2wrnWfiSEHACLcBGAs/s0/editCustomer.png "editCustomer.png")

> **Тайлбар:** Харилцагчийн мэдээллийн өөрчлөлтийн түүхийг холбоосоор харна.

----------

#### <i class="fa fa-tripadvisor"></i> Харилцагч устгах

Synchronization
-------------------

StackEdit can be combined with <i class="icon-provider-gdrive"></i> **Google Drive** and <i class="icon-provider-dropbox"></i> **Dropbox** to have your documents saved in the *Cloud*. The synchronization mechanism takes care of uploading your modifications or downloading the latest version of your documents.

> **Note:**

> - Full access to **Google Drive** or **Dropbox** is required to be able to import any document in StackEdit. Permission restrictions can be configured in the settings.
> - Imported documents are downloaded in your browser and are not transmitted to a server.
> - If you experience problems saving your documents on Google Drive, check and optionally disable browser extensions, such as Disconnect.

#### <i class="icon-refresh"></i> Open a document

You can open a document from <i class="icon-provider-gdrive"></i> **Google Drive** or the <i class="icon-provider-dropbox"></i> **Dropbox** by opening the <i class="icon-refresh"></i> **Synchronize** sub-menu and by clicking **Open from...**. Once opened, any modification in your document will be automatically synchronized with the file in your **Google Drive** / **Dropbox** account.

#### <i class="icon-refresh"></i> Save a document

You can save any document by opening the <i class="icon-refresh"></i> **Synchronize** sub-menu and by clicking **Save on...**. Even if your document is already synchronized with **Google Drive** or **Dropbox**, you can export it to a another location. StackEdit can synchronize one document with multiple locations and accounts.

#### <i class="icon-refresh"></i> Synchronize a document

Once your document is linked to a <i class="icon-provider-gdrive"></i> **Google Drive** or a <i class="icon-provider-dropbox"></i> **Dropbox** file, StackEdit will periodically (every 3 minutes) synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be detected.

If you just have modified your document and you want to force the synchronization, click the <i class="icon-refresh"></i> button in the navigation bar.

> **Note:** The <i class="icon-refresh"></i> button is disabled when you have no document to synchronize.

#### <i class="icon-refresh"></i> Manage document synchronization

Since one document can be synchronized with multiple locations, you can list and manage synchronized locations by clicking <i class="icon-refresh"></i> **Manage synchronization** in the <i class="icon-refresh"></i> **Synchronize** sub-menu. This will let you remove synchronization locations that are associated to your document.

> **Note:** If you delete the file from **Google Drive** or from **Dropbox**, the document will no longer be synchronized with that location.

----------


Publication
-------------

Once you are happy with your document, you can publish it on different websites directly from StackEdit. As for now, StackEdit can publish on **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **Tumblr**, **WordPress** and on any SSH server.

#### <i class="icon-upload"></i> Publish a document

You can publish your document by opening the <i class="icon-upload"></i> **Publish** sub-menu and by choosing a website. In the dialog box, you can choose the publication format:

- Markdown, to publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML, to publish the document converted into HTML (on a blog for example),
- Template, to have a full control of the output.

> **Note:** The default template is a simple webpage wrapping your document in HTML format. You can customize it in the **Advanced** tab of the <i class="icon-cog"></i> **Settings** dialog.

#### <i class="icon-upload"></i> Update a publication

After publishing, StackEdit will keep your document linked to that publication which makes it easy for you to update it. Once you have modified your document and you want to update your publication, click on the <i class="icon-upload"></i> button in the navigation bar.

> **Note:** The <i class="icon-upload"></i> button is disabled when your document has not been published yet.

#### <i class="icon-upload"></i> Manage document publication

Since one document can be published on multiple locations, you can list and manage publish locations by clicking <i class="icon-upload"></i> **Manage publication** in the <i class="icon-provider-stackedit"></i> menu panel. This will let you remove publication locations that are associated to your document.

> **Note:** If the file has been removed from the website or the blog, the document will no longer be published on that location.

----------


Markdown Extra
--------------------

StackEdit supports **Markdown Extra**, which extends **Markdown** syntax with some nice features.

> **Tip:** You can disable any **Markdown Extra** feature in the **Extensions** tab of the <i class="icon-cog"></i> **Settings** dialog.

> **Note:** You can find more information about **Markdown** syntax [here][2] and **Markdown Extra** extension [here][3].


### Tables

**Markdown Extra** has a special syntax for tables:

Item     | Value
-------- | ---
Computer | $1600
Phone    | $12
Pipe     | $1

You can specify column alignment with one or two colons:

| Item     | Value | Qty   |
| :------- | ----: | :---: |
| Computer | $1600 |  5    |
| Phone    | $12   |  12   |
| Pipe     | $1    |  234  |


### Definition Lists

**Markdown Extra** has a special syntax for definition lists too:

Term 1
Term 2
:   Definition A
:   Definition B

Term 3

:   Definition C

:   Definition D

	> part of definition D


### Fenced code blocks

GitHub's fenced code blocks are also supported with **Highlight.js** syntax highlighting:

```
// Foo
var bar = 0;
```

> **Tip:** To use **Prettify** instead of **Highlight.js**, just configure the **Markdown Extra** extension in the <i class="icon-cog"></i> **Settings** dialog.

> **Note:** You can find more information:

> - about **Prettify** syntax highlighting [here][5],
> - about **Highlight.js** syntax highlighting [here][6].


### Footnotes

You can create footnotes like this[^footnote].

  [^footnote]: Here is the *text* of the **footnote**.


### SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                  | ASCII                        | HTML              |
 ----------------- | ---------------------------- | ------------------
| Single backticks | `'Isn't this fun?'`            | 'Isn't this fun?' |
| Quotes           | `"Isn't this fun?"`            | "Isn't this fun?" |
| Dashes           | `-- is en-dash, --- is em-dash` | -- is en-dash, --- is em-dash |


### Table of contents

You can insert a table of contents using the marker `[TOC]`:

[TOC]


### MathJax

You can render *LaTeX* mathematical expressions using **MathJax**, as on [math.stackexchange.com][1]:

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> **Tip:** To make sure mathematical expressions are rendered properly on your website, include **MathJax** into your template:

```
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
```

> **Note:** You can find more information about **LaTeX** mathematical expressions [here][4].


### UML diagrams

You can also render sequence diagrams like this:

```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```

And flow charts like this:

```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```

> **Note:** You can find more information:

> - about **Sequence diagrams** syntax [here][7],
> - about **Flow charts** syntax [here][8].

### Support StackEdit

[![](https://cdn.monetizejs.com/resources/button-32.png)](https://monetizejs.com/authorize?client_id=ESTHdCYOi18iLhhO&summary=true)

  [^stackedit]: [StackEdit](https://stackedit.io/) is a full-featured, open-source Markdown editor based on PageDown, the Markdown library used by Stack Overflow and the other Stack Exchange sites.


  [1]: http://math.stackexchange.com/
  [2]: http://daringfireball.net/projects/markdown/syntax "Markdown"
  [3]: https://github.com/jmcmanus/pagedown-extra "Pagedown Extra"
  [4]: http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference
  [5]: https://code.google.com/p/google-code-prettify/
  [6]: http://highlightjs.org/
  [7]: http://bramp.github.io/js-sequence-diagrams/
  [8]: http://adrai.github.io/flowchart.js/




