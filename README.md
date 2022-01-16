# MindMap
1. Manage my goals in the form of a MindMap
2. Managing the MindMap in git
3. Anyone can view the latest MindMap from a browser

![](test.png)

## Rules
Principle: Arrange in order of importance
Tasks with high urgency are marked with a 🏁 (flag).

## PlantUML
- Compatible with Org-mode
- Generates images from text data and displays the images, making it suitable for git management

https://plantuml.com/ja/mindmap-diagram

## Initial settings
```sh
git clone git@github.com:Ishizuka427/MindMap.git
cd MindMap
brew install plantuml
plantuml test.puml
```

## How to update
```sh
plantuml test.puml
git status
git add test.png test.puml
git commit -m 'update test.png'
git push
```

## PlantUML Viewer
Chrome Extensions  
It will display your PlantUML creations as raw GitHub data in images.  
※ You need to have the chrome feature installed to see it.

https://chrome.google.com/webstore/detail/plantuml-viewer/legbfeljfbjgfifnkmpoajgpgejojooj?hl=en

## Org-mode
※ Unverified
- plantuml-mode
- org-babel

https://joppot.info/2017/10/30/4091
