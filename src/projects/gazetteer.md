---
title: "Gazetteer"
summary: "Gathers basic data about countries"
image: /images/Gazetteer.JPG
imageAlt: "Screenshot of gazetteer app"
tech:
  - "jQuery"
  - "php"
  - "api"
  - "leaflets"
siteUrl: "https://samirbetmouni.free.nf/project1/"
repoUrl: "https://github.com/Samir70/samirBetmouni"
---

### Problem Solved

This was a project assigned as part of my `itCareerSwitch` full-stack developer course. The user story was to have the app detect the user's country and display that on a map. The user can also select countries from a drop down. There are five modals which display various data, including one which allows currency conversion.

### Technologies Used

`API` requests were made via `php`, accessed in the `javaScript` via `ajax` calls. `jQuery` was used to update the page after user interaction. `Leaflets` was used to display the map at a useful zoom level. `Easybuttons` were used to make the buttons blend into the map style, with `bootstrap icons` to convey meaning. Markers were added in a layer-group, to mark cities.

### Challenges Faced

This was my first proper project using `php` and leaflets. It made a lot of use of various `apis`, also requiring keeping keys secret -- something I had not done in `php`. 

### Lessons Learned

Think about which boiler-plate code will be used over and over and set up your VSCode snippets early -- it saves time eg: with format of `ajax` calls.