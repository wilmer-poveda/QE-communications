# QE-communications

Consider the following structure to navigate this repository
```
QE-communications/
│
├── public-images/  -- It will be deprecated in 2026
├── assets/
│   ├── images/
│   │   ├── headers/
│   │   ├── speakers/
│   │   ├── backgrounds/
│   │   └── studio/
│   └── css/
│
├── templates/
│   ├── 2023/
│   ├── 2024/
│   └── 2025/
│       └── templateName.html/
│
└── README.md
```

## How we can you get an image from github.
There are two options to use an image uploaded to GitHub, "Relative Links" or "URL":

### 1. Relative Links
A file path describes the location of a file in a web site's folder structure.

```
<img src="/assets/images/headers/picture.jpg">  The "picture.jpg" file is located in the images folder at the root of the current web
<img src="../../../picture.jpg">                The "picture.jpg" file is located in the folder three level up from the current folder
```

### 2. URL 
1. Identify the folder where the desire image is located into "images" folder, like:
    - /headers
    - /speakers
    - /studio
    - ...
2. Once the image location is identified, complete the image URL (folder/image) to be able to open it in a new tab
    - **{folderName}:** belongs to the folder name differente from root
    - **{image_name}:** belongs to the name of hte image (.png or .jpg)
> [!NOTE]
> - https://raw.githubusercontent.com/wilmer-poveda/QE-communications/refs/heads/main/assets/images/{folder_name/image_name.png}
> - **i.e:** https://raw.githubusercontent.com/wilmer-poveda/QE-communications/refs/heads/main/assets/images/headers/Karate_workshop.png


## How you can access to your template:
1. Identify the template location
2. Once the desired templates has been identified, user the following URL and replace he brakets values.
    - **{year}:** belongs to the current year of the template
    - **{folderName}:** belongs to the folder name differente from root
    - **{templateName.html}:** belongs to the template name you desire to publish. Remember that it should not have blank spaces
> [!NOTE]
> - https://wilmer-poveda.github.io/QE-communications/templates/{year}/{templateName.html}
> - **i.e:** https://wilmer-poveda.github.io/QE-communications/templates/2025/JAN_WORKSHOP_GenIA.html


> [!TIP]
> Remember that the template name should not have spaces in blank.\
> :white_check_mark:	 -> Encuesta_TechTalk_FEB.html\
> :white_check_mark:	 -> EncuestaTechTalkFEB.html\
> :x:  -> Encuesta TechTalk FEB.html
    

## How you can view an HTML page from github.
https://htmlpreview.github.io/?