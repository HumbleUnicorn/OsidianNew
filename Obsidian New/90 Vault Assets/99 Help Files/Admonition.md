---
creation date: Thursday October 27 2022 2:46:18 pm
modification date: Friday October 28 2022 10:29:50 am
aliases: ['Admonition'] 
tags: [readme] 
---
> [!toc]+
> - [[#Installation|Installation]]
> - [[#Admonition Settings|Admonition Settings]]
> 	- [[#Admonition Settings#Custom Callout Menu|Custom Callout Menu]]
> - [[#Admonitions & Callouts (Defaults)|Admonitions & Callouts (Defaults)]]
> - [[#Icon Packs|Icon Packs]]
> - [[#Creating Admonitions & Callouts|Creating Admonitions & Callouts]]
> 	- [[#Creating Admonitions & Callouts#Creating a Custom Admonition/Callout Block|Creating a Custom Admonition/Callout Block]]
> 	- [[#Creating Admonitions & Callouts#Inserting an Admonition Block in a Note|Inserting an Admonition Block in a Note]]
> 	- [[#Creating Admonitions & Callouts#Inserting a Callout Block in a Note|Inserting a Callout Block in a Note]]
> 	- [[#Creating Admonitions & Callouts#Obsidian Defaults|Obsidian Defaults]]
> 	- [[#Creating Admonitions & Callouts#Ruth's Favorite Custom Callouts|Ruth's Favorite Custom Callouts]]

---
# Admonition
#rwertz  #plugins/community 

---
## Installation
[Plugin Information Link](obsidian://show-plugin?id=obsidian-admonition)
- Install and enable

## Admonition Settings
Click :obs_gear: ***Settings*** under Community Plugins to: 
- Export Custom Types as CSS: *Ignore this feature*
- Use CSS Snippet for Custom Callouts: `Off`
- Add New: *Click on* :luc_plus_square: *button to add custom callouts*

### Custom Admonition/Callout Menu
- Admonition Type: `type ID`  *This is the name you will use to initiate the admonition block
- Admonition Title: `Title` *This is the default title used for all admonition blocks of this type. 
- No Admonition Title by Default: `Off`
- Show Copy Button: `Off`
- Admonition Icon: *Type a keyword or search term to search for icons. 
- Color: *Click on the color circle to open the color picker and select a custom color.*

## Admonitions & Callouts (Defaults)
- Add Drop Shadow: `On`
- Collapsible by Default: `Off`
- Add Copy Button: `Off`
- Parse Titles as Markdown: `On`
- Set Admonition Colors: `On`
- Hide Empty Admonitions: `Off`

## Icon Packs
- Use Font Awesome Icons: `On` [Font Awesome Free](https://fontawesome.com/search?m=free&o=r)
- Load Additional Icons: *Select* :obs_plus_with_circle: *to load* [Octicons](https://primer.style/octicons/) *and* [RPG Awesome](https://nagoshiashumari.github.io/Rpg-Awesome/)

## Creating Admonitions & Callouts

### Creating a Custom Admonition/Callout Block
- Admonition Type: `cite`  
- Admonition Title: `Quick Cite` 
- No Admonition Title by Default: `Off`
- Show Copy Button: `On` *The purpose of this callout is to store an APA format refernce for easy cut and paste when/where needed.*
- Admonition Icon: `paper-plan=glyph`
- Color:  `RGB: 165,61,145`
- Click the :obs_checkmark: at the bottom of the window to complete setup. 


![](admonitionMenu.png)

### Inserting an Admonition Block in a Note
An admonition block is technically a code block, and is formatted as such. You can quickly insert an admonition into your note with hotkey `Alt+A`. 

The markdown code will look like this: 
````md
```ad-cite
Callout body
```
````

And it will appear in your note like this: 
```ad-cite
Callout body
```

Other formatting options: 
- For other customizations, and options see the Admonition plugin [documentation](obsidian://show-plugin?id=obsidian-admonition)

```ad-warning
title: Important

Recent updates in Obsidian now support **Callout boxes** that use a slightly different syntax. These serve the same function, but use a slightly different syntax. Therefore the rendering of admontions and callouts may appear different in some themes that predated these changes and have not yet been updated. 

```

### Inserting a Callout Block in a Note
A callout block serves the same purpose as the admonition block, and for the most part, will behave the same, and render the same. Fundamentally, however callouts are not code blocks. You can quickly add a callout to your notes with the hotkey `Alt+C`.

The markdown code will look like this: 
```md
>[!cite]
>Callout body
```

And it will appear in your note like this: 
> [!cite]
> Callout body

Other formatting options: 
- For other customizations, and options see the Obsidian callouts [documentation](https://help.obsidian.md/How+to/Use+callouts)

> [!tip] Callouts vs. Admonitions
> Note that with the callout syntax, the copy button does not appear on the right side of the `Quick Cite` callout block with a mouse hover as it does in the admonition block. This is a subtle difference that will not matter much *most* of the time. 
>
>---
>### You might use admonitions when: 
>- You want a copy button to copy and paste block contents (i.e., templates, references, quotes) 
>- You want to exclude links, tasks, tags, or other data from graph view, backlinks, task managers, etc. However, there are also other ways to do this. 
>
> ### Helpful Hint: 
> - You can highlight existing text and use the hotkey `Alt+A` (admonition) or`Alt+C` (callout) to include the highlighted text inside the new block, as opposed to manually adding the appropriate syntax.

### Obsidian Defaults 
```ad-info
title: Obsidian Default Callouts
- :luc_pencil: note 
- :luc_clipboard_list: abstract, summary, tldr 
- :fas_circle_info: info, todo
- :fas_fire_flame_curved: tip, hint, important
- :fas_check: success, check, done
- :obs_question_mark_glyph: question, help, faq
- :fas_triangle_exclamation: warning, caution, attention
- :fas_x: failure, fail, missing
- :fas_bolt: danger, error
- :fas_bug: bug
- :obs_number_list_glyph: example
- :obs_quote_glyph: quote, cite
```

### Ruth's Favorite Custom Callouts 

> [!toc]
> 

> [!source]

> [!cite]
 
> [!link]
> 
