# CTA Block

A component with text, image and a more visual link style. Use this to help site visitors navigate to more key content and actionable steps.



![](../../../.gitbook/assets/cta-examples.png)

![Schematic shows elements used to create each example.](../../../.gitbook/assets/ui-ctablock-wireframe.png)



### Block Headings

In most use cases, a block will include a heading at the top. It is important to use the right heading level, and not select it just based on visual style.

The Block title will always display as an H2 (heading level 2), so check the hide title box if this is not the intended use. The Title (H3) field will always be an H3.

{% hint style="danger" %}
Add text about proper use of headings, not skipping heading levels.
{% endhint %}

## Text Formats

The  color of the Title (H3) field is set by the color style.

![](../../../.gitbook/assets/UI-cta-block-formats.png)

Change the Text format to Advanced to use heading tags, and apply color to specific text elements. (see Styling Blocks)

## CTA Links

The link shown at the bottom of blocks is easy to configure.

* **URL internal link:**\
  This is an autocomplete field. To link to an internal link (a page that is part of the site), start typing the page title and you will be shown choices that you can select from. Select the intended page and the link will be added automatically.
* **URL external link:**\
  Enter the full URL (including https://) to link to an external website.
* **Link text:** This is the text that will be displayed in the browser.&#x20;

![](../../../.gitbook/assets/UI-cta-block-links.png)

{% hint style="success" %}
**Use descriptive link text that is helpful to the reader.**\
****Learn more about this: **** [https://developers.google.com/style/link-text](https://developers.google.com/style/link-text)
{% endhint %}

\
**Attributes:** Sometimes it is not realistic to include lengthy descriptive link text due to available space in a block. When this happens, you can add the more descriptive text in an `ARIA Label`. For example, if the Link text needs to be something like “Learn More”, then expand the Attributes section and add more descriptive text to the ARIA Label, this is the text that will be read by a screen reader.\


![](../../../.gitbook/assets/UI-cta-block-links-attr.png)

{% hint style="info" %}
Learn more about ARIA Labels: [https://www.w3.org/TR/WCAG20-TECHS/ARIA14.html](https://www.w3.org/TR/WCAG20-TECHS/ARIA14.html)
{% endhint %}

## Selecting Link Styles

Select the visual style of the CTA Link(s) using the Link Styles dropdown. The default is a plain blue hyperlink.&#x20;

![](<../../../.gitbook/assets/Screen Shot 2020-06-20 at 9.05.05 AM.png>)

Note that the Arrow List style will change color based on the background or border color of the block. The CTA Link component is intended to highlight important information for users, but too many on one page can dilute the importance of the links.

![](../../../.gitbook/assets/UI-cta-block-linkstyles.png)

## Block Media

The CTA Block wouldn’t be useful without the option to add an image. But be aware of how tall a card can become with an image and lengthy text.

![](../../../.gitbook/assets/ui-cta-block-media.png)

