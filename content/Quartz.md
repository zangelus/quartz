
Quartz is a tool to convert .md files such as those create by Obsidian and turn them into .html. 
The goal is to post my information and ideas online. 

Quartz does more than converting, when I run the following command in the quartz repository which contain the folder content associated with the Obsidian content, it converts the .md files and also pushes the changes to the github repository. 

`> npx quartz sync` 


Something I am still not very clear about is how does the file in the repository: .github/workflows/deploy.yaml works; it is definitively used to define two operations : build and and deploy to publish the website. In GitHub is called workflows: https://github.com/zangelus/quartz/actions/runs/15813376592/workflow

![[Pasted image 20250622221531.png]]

