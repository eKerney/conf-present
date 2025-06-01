---
theme:
  path: catppuccin-custom.yaml
  override:
    default:
      colors:
        foreground: 74c7ec
---

<!-- alignment: center -->
<!-- new_lines: 6 -->
<!-- font_size: 5 -->
<span style="color: #a6e3a1;">ArcGIS Experience Builder</span>
<!-- font_size: 4 -->
<span style="color: #f9e2af;">For Developers: _Easy Edition_</span>
<!-- font_size: 3 -->
<span style="color: #74c7ec;">IMAGIN/MiCAMP 2025 Conference</span>
<!-- font_size: 2 -->
<span style="color: #74c7ec;">Kalamazoo, MI, Radisson Plaza</span>
<!-- font_size: 2 -->
<span style="color: #74c7ec;">Eric Kerney - Blue Raster</span>
![image:width:20%](blueraster-logo.png)
<!-- end_slide -->



<!-- alignment: center -->
<!-- new_lines: 6 -->
What is Experience Builder???
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. The Builder
<!-- new_lines: 1 -->
2. The Experience
<!-- new_lines: 1 -->
3. How are orgs using it?
<!-- new_lines: 1 -->
4. Why create a Custom Experience?
<!-- end_slide -->


<!-- new_lines: 6 -->
What Tech Do I Need???
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. Modern Web Technologies
	1. HTML
	2. CSS 
	3. JavaScript
2. React
3. TypeScript
4. ArcGIS Maps SDK
5. Terminal & Admin Access
6. Windows Subsystem 4 Linux 
7. OR || MacOS preferred
<!-- speaker_note: May want to mention my stack Mac, brew, ghostty, nvim, tmux, raycast, aerospace -->
<!-- speaker_note: React old Class Components vs Newer Functional Style -->
<!-- speaker_note: jimu exb api interface, jimu interfaces with Maps SDK -->
<!-- end_slide -->


<!-- new_lines: 6 -->
EXB Developer Edition 
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. Terminal: nodeJS - npm - code editor
<!-- new_lines: 1 -->
2. EXB Dev Download 
<!-- new_lines: 1 -->
3. Server & Client Setup
<!-- new_lines: 1 -->
4. Start both Server + Client
<!-- end_slide -->


<!-- new_lines: 6 -->
Setting up with AGO/Enteprise
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. Create Credentials in AGO
<!-- new_lines: 1 -->
2. Enter Creds into EXB
<!-- new_lines: 1 -->
3. Few Notes on Deployment
	1. Deploy to AGO/Enterprise
	2. Deploy to server/cloud
<!-- end_slide -->


<!-- new_lines: 6 -->
Shall we Get Started???
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. Installs 
<!-- new_lines: 1 -->
2. Creds 
<!-- new_lines: 1 -->
3. Start
<!-- speaker_note: https://gis.blueraster.io/portal/home/index.html -->
<!-- speaker_note: Note - ESRI made it more difficult for developers to test custom EXB with limited dev accounts -->
<!-- speaker_note: Run thgrough creating and registering a new application on AGO -->
https://developers.arcgis.com/experience-builder/guide/downloads/
https://developers.arcgis.com/experience-builder/guide/release-versions/
<!-- end_slide -->


<!-- new_lines: 6 -->
Taking a Look Around
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. Familiar EXB Interface
<!-- new_lines: 1 -->
2. File Structure
<!-- new_lines: 1 -->
3. TypeScript
<!-- new_lines: 1 -->
4. React & Components
<!-- new_lines: 1 -->
5. Config Files
<!-- speaker_note: Use VSCode as a file tree viewer -->
<!-- end_slide -->

<!-- new_lines: 6 -->
Custom Widgets
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. Widget File Structure
<!-- new_lines: 1 -->
2. Interface with EXB App
<!-- new_lines: 1 -->
4. Working with Data Sources
<!-- end_slide -->


<!-- new_lines: 6 -->
Exploring Widgets
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. ESRI github examples
<!-- new_lines: 1 -->
2. Any Widget Ideas?
<!-- end_slide -->
 

<!-- new_lines: 6 -->
Deploying Our Widget!
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. Deploying to Enterprise
<!-- speaker_note: Deploy ArcGIS Enterprise OR Developer Edition/webserver -->

![image:width:100%](exb_enter_deploy.png)

<!-- end_slide -->

<!-- new_lines: 6 -->
Deploying Our Widget!
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. Developer Edition Webserver

![image:width:100%](exb_dev_deploy.png)

<!-- speaker_note: Deploy options - S3, Amplify, github pages -->
<!-- end_slide -->
