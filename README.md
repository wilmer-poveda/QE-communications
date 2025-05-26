# QE-communications

Consider the Following structure to surface in this repository 
```
my-project/
│
├── public-images/  -- It will be deprecated in 2026
├── assets/
│   ├── images/
│   │   ├── headers/
│   │   ├── photos/
│   │   ├── backgrounds/
│   │   └── speakers/
│   └── css/
│
├── templates/
│   ├── 2025/
│   │   └── templateName.html/
│
├── README.md
└── .gitignore
```

## How we can you get an image from github.
There are two options to use an image uploaded to GitHub.
### 1. Relative Links
A file path describes the location of a file in a web site's folder structure.

```
<img src="/public-images/picture.jpg">  The "picture.jpg" file is located in the images folder at the root of the current web
<img src="../../../picture.jpg">        The "picture.jpg" file is located in the folder three level up from the current folder
```

### 2. URL 
1. Identify the folder where the desire image is located into "public-images" folder, like:
    - /headers
    - /speakers
    - /others
    - ...
2. Once the image location is identified, complete the image URL (folder/image) to be able to open it in a new tab
    - **{folderName}:** belongs to the folder name differente from root
    - **{image_name}:** belongs to the name of hte image (.png or .jpg)
    > https://raw.githubusercontent.com/wilmer-poveda/QE-communications/refs/heads/main/public-images/{filder_name/image_name}
    - **i.e:** https://raw.githubusercontent.com/wilmer-poveda/QE-communications/refs/heads/main/public-images/headers/Karate_workshop.png

## How you can access to your template:
1. Identify the template location
2. Once the desired templates has been identified, user the following URL and replace he brakets values.
    - **{year}:** belongs to the current year of the template
    - **{folderName}:** belongs to the folder name differente from root
    - **{templateName.html}:** belongs to the template name you desire to publish. Remember that it should not have blank spaces
    > https://wilmer-poveda.github.io/QE-communications/templates/{year}/{folderName}/{templateName.html}
    - **i.e:** https://wilmer-poveda.github.io/QE-communications/templates/2024/EncuestaTechTalk_FEBWIL.html

> [!TIP]
> Remember that the template name should not have spaces in blank.\
> :white_check_mark:	 -> Encuesta_TechTalk_FEB.html\
> :white_check_mark:	 -> EncuestaTechTalkFEB.html\
> :x:  -> Encuesta TechTalk FEB.html
    
## How you can view an HTML page from github.
https://htmlpreview.github.io/?