---
type: PostLayout
title: "Blade Ball Plontium.lua | 3.7.2 \U0001F5C2️"
colors: colors-a
date: '2024-11-11'
author: content/data/team/doris-soto.json
excerpt: The best frequently updated script for blade ball.
featuredImage:
  type: ImageBlock
  url: /images/featured-Image6.jpg
  altText: Post thumbnail image
bottomSections:
  - elementId: ''
    type: RecentPostsSection
    colors: colors-f
    variant: variant-d
    subtitle: Recent posts
    showDate: true
    showAuthor: false
    showExcerpt: true
    recentCount: 2
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
    showFeaturedImage: true
    showReadMoreLink: true
  - type: ContactSection
    backgroundSize: full
    title: Stay up-to-date with my words ✍️
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
&lt;!DOCTYPE html&gt;
&lt;html lang=&quot;en&quot;&gt;
&lt;head&gt;
    &lt;meta charset=&quot;UTF-8&quot;&gt;
    &lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1.0&quot;&gt;
    &lt;title&gt;Blade Ball Script&lt;/title&gt;
    &lt;style&gt;
        body {
            background-color: #121212;
            color: #ffffff;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            background-color: #1e1e1e;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.5);
            max-width: 600px;
            width: 100%;
            text-align: center;
        }
        h1 {
            font-size: 24px;
            margin-bottom: 20px;
        }
        .code-container {
            background-color: #333333;
            padding: 15px;
            border-radius: 5px;
            color: #00ff88;
            text-align: left;
            font-family: monospace;
            font-size: 14px;
            white-space: pre-wrap;
            position: relative;
        }
        button {
            background-color: #00ff88;
            color: #121212;
            border: none;
            padding: 8px 12px;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            position: absolute;
            top: 10px;
            right: 10px;
        }
        button:hover {
            background-color: #00cc70;
        }
    &lt;/style&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;div class=&quot;container&quot;&gt;
        &lt;h1&gt;Blade Ball Script&lt;/h1&gt;
        &lt;div class=&quot;code-container&quot;&gt;
            &lt;pre&gt;&lt;code id=&quot;codeBlock&quot;&gt;loadstring(game:HttpGet(&quot;https://raw.githubusercontent.com/PawsThePaw/Plutonium.AA/main/Plutonium.Loader.lua&quot;, true))()&lt;/code&gt;&lt;/pre&gt;
            &lt;button onclick=&quot;copyToClipboard()&quot;&gt;Copy&lt;/button&gt;
        &lt;/div&gt;
    &lt;/div&gt;

    &lt;script&gt;
        function copyToClipboard() {
            const code = document.getElementById(&#39;codeBlock&#39;).innerText;
            const textArea = document.createElement(&#39;textarea&#39;);
            textArea.value = code;
            document.body.appendChild(textArea);
            textArea.select();
            document.execCommand(&#39;copy&#39;);
            document.body.removeChild(textArea);
            alert(&#39;Code copied to clipboard!&#39;);
        }
    &lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;
