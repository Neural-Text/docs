# ➕ Add data to a document

As you could have already noticed, NeuralText is able to extract a lot of data from pages ranking on Google.

Sometimes you might want to add these data to the document.

This article will explain what are the available options to include data in the document.

### Import text from URL

![](<../../.gitbook/assets/image (20).png>)

You can import content from external URLs in this way:

1. Click on the “Import from URL” icon in editor toolbar
2. Insert the URL in the field
3. Click on “Process URL”
4. After a few seconds, you will see a preview of the extracted article
   1. Raw text: the formatted version of the page
   2. Plain text: a simple editor to edit the content of the page
5. Click on “Confirm” button to insert in the editor

<details>

<summary><strong>Why NeuralText is unable to pull data from some URLs?</strong></summary>

Although are doing our best to extract the text content from competitor pages as possible, sometimes we cannot get the data we need.

Below are a few reasons why this might be the case:

* **Several pages lack enough text content.** We use heading tags to evaluate if a page has enough text content to be considered useful to the user. Our extraction algorithms tend to consider the main content of a page, removing all the boilerplate (navbar, sidebar and footer links etc.).
* Blocked Page - Some websites block third parties from programmatically accessing the contents of their site.
* Unstructured Content - There are many parts of a website that aren't part of the main content. For instance, a navigation bar, footer, sidebar, or any advertisements. Whenever we extract content from a page we try to get rid of these unimportant elements. When the page structure looks confusing to our system, it can mean we are unable to identify the content, and therefore can't extract the text from a page.

We are continuously improving our extraction engine. If you need some help, don’t hesitate to contact our friendly support.

</details>

### Insert from Content Analysis elements

NeuralText allows you to explore single paragraphs for each ranking page on Google**.**

Insert elements from your competitors is very useful if you want to give your writers some inspiration or want to give them some examples on how a topic is covered.

#### Insert a paragraph or a question

{% embed url="https://youtu.be/fQJF0nIwGII" %}

#### Insert an example from the topic section

{% embed url="https://youtu.be/bZ2e7c2I_uo" %}
