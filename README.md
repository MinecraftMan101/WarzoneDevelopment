[![Build Status](https://jenkins.bennydoesstuff.me/buildStatus/icon?job=TGM)](https://jenkins.bennydoesstuff.me/job/TGM)

# Warzone Development (beta)
Team Oriented Minecraft PVP Suite

## Project Goals

1. **Focusing on the main issues that are currently unsolved.** 


## Local Server Setup
 
1. Start with the latest stable [Paper (PaperSpigot)](https://ci.destroystokyo.com/job/Paper/) build. 
 
2. Create a `maps` folder inside of the server and insert a supported TGM map. You can also just clone our `Maps` repository as a folder. 
 
4. (Optional) Install WorldEdit to enable the Teleport Tool. 
 
5. Start the server.
 
## Developer Tips

1. We use Lombok. Make sure you have the Lombok plugin installed on your preferred IDE.

2. We use maven. Like any other maven project, run `mvn clean install` in the top level folder to generate the required libraries.
