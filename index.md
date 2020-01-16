## ClassHero docs

# Kontoarten
1. Adminkonto (PC-only)
2. Planerkonto (PC-only)
3. Lehrerkonto (PC und Android/iOS/Windows Phone)
4. Studentenkonto (PC und Android/iOS/Windows Phone)
5. Elternteil Konto (PC und Android/iOS/Windows Phone)

## Setup Vorgang

Um komplette Kontrolle und Sicherheit der Konten und Seite zu haben, werden die Konten per Postman von mir persönlich angelegt.

1. Name der Schule und die Stadt werden eingetragen, sowie der "creator key", der nötig ist um im Server ein Konto erstellen zu können.
   Zu dem Schlüssel habe nur ich Zugang. Bei POST an Server wird der Schlüssel gehasht.

    1.1 Aus den Parametern **Schule**, **Stadt** wird ein Adminkonto, Admin Password, Admin Wiederherstellungsschlüssel und Planerkonto         generiert. Die Anmelde Namen haben immer den selben Format 
         **<schule>.<stadt>.<kontoTyp>.<zufällige 3-stellige Zahl>**. Schule und Stadt werden automatisch abgekürzt (Friedrich-                 List-Schule wird zu fls, Kassel wird zu ksl).
    
    ![RegisterAccount](Register.png)


You can use the [editor on GitHub](https://github.com/ClassHero/docs/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ClassHero/docs/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
