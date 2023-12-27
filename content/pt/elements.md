---
title: Elements
draft: true
---
{{< brick_title >}}

{{< breadcrumbs >}}

# Elements

Esses são os elementos do site, **meu job-aid**. Ninguém consegue guardar todas as informações na memória. 

{{< /brick_title >}}
{{< brick_wide >}}

Lorem dolor sit amet, consectetur adipiscing elit. Nam non laoreet nisi, ac hendrerit lacus. Sed eget dapibus dui. Phasellus non ante sollicitudin, ultrices ex et, convallis orci. Etiam laoreet justo neque. Aenean nec porta mauris, ut luctus nibh. Morbi sed quam rhoncus felis tempus porttitor a nec nisl. Nulla facilisi. In suscipit velit sed lacus condimentum, at [fermentum](https://www.google.com) nulla faucibus. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. 

## Notice

{{< notice note >}} This is a very good note. {{< /notice >}} 

{{< notice warning >}} This is a warning notice. Be warned! {{< /notice >}}

{{< notice tip >}} This is a very good tip. {{< /notice >}} 

{{< notice info >}} This is a very good info. {{< /notice >}} 

## Footnote

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

  
## Heading 2

Nam elementum bibendum augue quis hendrerit. Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. [Maecenas](https://www.google.com) molestie sodales bibendum. Nullam egestas nulla eget justo cursus, vitae convallis nibh fermentum. Phasellus ornare, purus in dapibus gravida, diam odio feugiat lectus, in efficitur dolor ante ut odio.

### Heading 3

Proin ac *lobortis* tellus, ut [maximus](https://www.google.com) magna. Aliquam facilisis risus sit amet augue congue varius. Duis augue nulla, aliquam vitae efficitur eget, bibendum et tellus. Aenean quis sagittis felis. 

### Heading 3

Donec rutrum felis dignissim nisl tincidunt, sit amet interdum dolor ornare. Cras id hendrerit eros. Curabitur tincidunt est magna, ac commodo quam fringilla id. Nullam at imperdiet justo. Donec **dolor quis** nibh *rutrum facilisis* sed vulputate pellentesque. Vivamus id mollis arcu. Cras porttitor eros erat, at semper ligula ultricies nec. Nam lectus ex, mollis efficitur erat pulvinar, gravida faucibus massa.

---

## Buttons

Buttons are a great way to drive conversion. They are actually links with the class 'button'. Read the [documentation](/docs/shortcodes/button/) for more info.

{{< button "Sobre Lefebvre" "/about/" >}}

{{< button2 "xxxxxx" "xxxxx" >}}

Donec rutrum felis dignissim nisl tincidunt, sit amet interdum dolor ornare. Cras id hendrerit eros.

{{< socialbuttons >}}

Donec rutrum felis dignissim nisl tincidunt, sit amet interdum dolor ornare. Cras id hendrerit eros.

{{< contactbuttons >}}

## PDF

Embed:

<object data="/portfolio/pokepais/pos-projeto.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="/portfolio/pokepais/pos-projeto.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="/portfolio/pokepais/pos-projeto.pdf">Download PDF</a>.</p>
    </embed>
</object>

Adobe:

<div id="adobe-dc-view"></div>
<script src="https://acrobatservices.adobe.com/view-sdk/viewer.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "1c78b662cc9b485e86bec4e44b221ef1", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "/portfolio/pokepais/pos-projeto.pdf"}},
			metaData:{fileName: "pos-projeto.pdf"}
		}, {});
	});
</script>

---

<div id="adobe-dc-view" style="width: 800px;"></div>
<script src="https://acrobatservices.adobe.com/view-sdk/viewer.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "1c78b662cc9b485e86bec4e44b221ef1", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "https://acrobatservices.adobe.com/view-sdk-demo/PDFs/Bodea Brochure.pdf"}},
			metaData:{fileName: "Bodea Brochure.pdf"}
		}, {embedMode: "IN_LINE"});
	});
</script>

---



---

### Checklist

- [ ] Mercury
- [x] Venus
- [x] Earth (Orbit/Moon)
- [x] Mars
- [ ] Jupiter
- [ ] Saturn
- [ ] Uranus
- [ ] Neptune
- [ ] Comet Haley

## Unordered list 

- Ut lacinia felis [luctus tincidunt](https://www.google.com) vehicula. 
- Ut eget lacinia enim, non consectetur ligula. 
- Vivamus tincidunt eros tristique, gravida lorem vitae, tempus justo. 
- Maecenas neque mi, dignissim a dignissim a, mollis eu arcu. 
- Pellentesque viverra congue sapien, ut ultricies nibh scelerisque vel. Donec consectetur ullamcorper gravida. Nullam leo felis, sollicitudin eget ex id, congue consequat enim. Morbi et condimentum ex. Donec semper nibh dolor.

---

## Ordered list 

1. Ut lacinia felis luctus tincidunt vehicula. 
1. Ut eget lacinia enim, non consectetur ligula. 
1. Vivamus tincidunt eros tristique, gravida lorem vitae, tempus justo. 
1. Maecenas neque mi, dignissim a dignissim a, mollis eu arcu. 
1. Pellentesque viverra congue sapien, ut ultricies nibh scelerisque vel. Donec consectetur ullamcorper gravida. Nullam leo felis, sollicitudin eget ex id, congue consequat enim. Morbi et condimentum ex. Donec semper nibh dolor.

---

## Image

A normal image:

![Unsplash - Ryan Quintal](/uploads/photos/lego.jpg)

A grayscale (colorized) image:

{{< colorize_image "Photo by S. Tsuchiya on Unsplash" "/uploads/photos/bricks2.jpg" >}}

Galeria:

{{< gallery dir="/portfolio/demo-delegacao/img/" >}}


---

## Map 'brick'

{{< map "/uploads/map2.png" "https://www.google.com/maps/place/52%C2%B022'20.1%22N+4%C2%B054'00.4%22E/@52.372253,4.8991072,18z/data=!3m1!4b1!4m4!3m3!8m2!3d52.372253!4d4.9001?entry=ttu" >}}

---

## Contact form

{{< contactform >}}

---

## Newsletter form

{{< newsletterform >}}

---

## Tabs

Lorem ipsum dolor sit amet, consectetur adipiscing elit.
{{< tabs >}}

## These titles

Nam elementum bibendum augue quis hendrerit. Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. [Maecenas](https://www.google.com) molestie sodales bibendum. Nullam egestas nulla eget justo cursus, vitae convallis nibh fermentum. Phasellus ornare, purus in dapibus gravida, diam odio feugiat lectus, in efficitur dolor ante ut odio.

---
## Are clickable

Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam elementum bibendum augue quis hendrerit. Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. [Maecenas](https://www.google.com) molestie sodales bibendum. Nullam egestas nulla eget justo cursus, vitae convallis nibh fermentum. Phasellus ornare, purus in dapibus gravida, diam odio feugiat lectus, in efficitur dolor ante ut odio.

---
## Tabs

Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Lorem ipsum dolor sit amet, consectetur adipiscing elit. [Maecenas](https://www.google.com) molestie sodales bibendum. Nullam egestas nulla eget justo cursus, vitae convallis nibh fermentum. Phasellus ornare, purus in dapibus gravida, diam odio feugiat lectus, in efficitur dolor ante ut odio. Nam elementum bibendum augue quis hendrerit. Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. [Maecenas](https://www.google.com) molestie sodales bibendum. Nullam egestas nulla eget justo cursus, vitae convallis nibh fermentum. Phasellus ornare, purus in dapibus gravida, diam odio feugiat lectus, in efficitur dolor ante ut odio.

{{< /tabs >}}


---
## Youtube video

Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam elementum bibendum augue quis hendrerit. Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris.

{{< youtube "qtIqKaDlqXo" "/uploads/youtubeposter.jpg" >}}

Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam elementum bibendum augue quis hendrerit. Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris.

---
## Video

Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam elementum bibendum augue quis hendrerit. Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris.

{{< video "/uploads/video/flowers.mp4" >}}

Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam elementum bibendum augue quis hendrerit. Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris.

---
## Audio

Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam elementum bibendum augue quis hendrerit. Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris.

{{< audio "/uploads/audio/jamming.mp3" >}}

Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam elementum bibendum augue quis hendrerit. Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris.

---
## F.A.Q.

Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam elementum bibendum augue quis hendrerit. Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris.

{{< faq 1 >}}

Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam elementum bibendum augue quis hendrerit. Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris.

---
## Gallery

Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam elementum bibendum augue quis hendrerit. Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris.

{{< gallery dir="/uploads/gallery/" >}}

Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris. Aliquam et dictum sem. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam elementum bibendum augue quis hendrerit. Sed lectus neque, efficitur id velit eget, feugiat ultricies mauris.

{{< /brick_wide >}}
