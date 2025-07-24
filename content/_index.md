+++
title = "Presentation template"
outputs = ["Reveal"]

[reveal_hugo]
theme = "black"
+++

# Here it is

Feel free to use this presentation template

(Press "→" to start)

---

### Add some content with markdown

{{< highlight markdown "linenos=inline" >}}

# Headings

**Bold text** and _italic text_ and `inline code`

> This is a blockquote.

- Item 1
  1. First
  2. Second

[This is a link](https://www.example.com)

{{< / highlight >}}

You will find it all in `/content/_index.md`

---

{{% section %}}

### Create some more slides...

{{< highlight markdown "linenos=inline" >}}

# Slide 1 Title

Your content here.

---

# Slide 2 Title

More content on a new slide.
{{< / highlight >}}

(Try pressing "↓")

---

### ...maybe even some vertical ones

{{< highlight markdown "linenos=inline" >}}

{{%/* section */%}}

## Top slide

Some content

---

## Bottom Slide

And some related content

{{%/* /section */%}}

{{< / highlight >}}

{{% /section %}}

---

{{% section %}}

### Include some code snippets...

{{< highlight text "linenos=inline" >}}
{{</* highlight javascript "linenos=inline" */>}}

const msg = "hello world!"
console.log(msg)

{{</* /highlight */>}}
{{< /highlight >}}

---

### ...with full syntax highlighting

{{< highlight javascript "linenos=inline" >}}

const msg = "hello world!"
console.log(msg)

{{< /highlight >}}

{{% /section %}}

---

### Ready to present?

Try adding some notes

{{< highlight markdown "linenos=inline" >}}

Content goes here.

{{%/* note */%}}

- [**firstly**] lets talk about this first point
- [**secondly**] then follow up with the second point
  {{%/* /note */%}}
  {{< / highlight >}}

(Press "S" to enter speaker mode)

{{% note %}}

- [**firstly**] lets talk about this first point
- [**secondly**] then follow up with the second point
  {{% /note %}}
