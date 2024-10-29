## [Vimeo to Marketo](https://drive.google.com/uc?export=download&id=1ubVWXFsg1IgveHR3fCWDTjKLULGZEhVG) 📺

### Overview 🌟
The "Vimeo to Marketo" tool is designed to simplify the process of extracting and modifying Vimeo video URLs from the BY resources pages. This tool is particularly useful for fetching Vimeo video URLs from a page and formatting the extracted URLs into the format required for Marketo landing pages. Additionally, it extracts video links from Marketo landing pages and displays them along with the section names where each video belongs.

### Purpose 🎯
In many cases, videos hosted on Vimeo need to be embedded in MKTO landing pages. To do this, the original Vimeo video URL, embedded on a resource page, needs to be extracted and altered into a specific URL structure. Manually performing this task can be time-consuming and prone to errors. The tool automates this process, ensuring efficiency and accuracy

### Functionality ⚙️
 1. The tool scans the webpage to find any Vimeo video URLs embedded in the HTML, specifically those starting with the format <br>
 `` https://player.vimeo.com/video/{videoid}?h={hash} ``

 2. Once the Vimeo URLs are identified, the tool extracts the relevant components (the videoid and hash) and converts the URL into the format that can be used in MKTO LPs
 ``https://cdn.blueyonder.com/global/video.html?videoid={videoid}/{hash} ``

<!---
## Tool [installation](https://drive.google.com/uc?export=download&id=1WjxT1bawv8BX_MIzwj9Q2kXwBANxWkwg) steps 📥
1. Click [here](https://drive.google.com/uc?export=download&id=1WjxT1bawv8BX_MIzwj9Q2kXwBANxWkwg) to download the tool.
2. Press ``Ctrl + Shift + O`` to open the Bookmark Manager in Chrome.
3. Click on the three vertical dots (menu) in the upper right corner.
4. Select **Import Bookmarks** from the dropdown menu.
5. Choose the bookmark file you just downloaded.
6. A folder named "Imported" will be created in your bookmarks. Inside this folder, you will find the tool. You can change its location if desired.
--->

## Watch the Installation [Video ▶️](https://drive.google.com/file/d/14rEqr_LyhwSK6aqeFvY6Xg0Wl7UMxx_z/view?usp=sharing) 

## How to use it 🛠️

1. Navigate to the Resource page that contains the Vimeo video you want to embed.
2. Click on the **Vimeo to MKTO** bookmark.
3. Copy the modified URL to your clipboard and use it in MKTO LPs.
 
