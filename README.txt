Unit 5 Music Vocabulary Web

Files:
- index.html
- vocabulary.json

How to run:
1. Keep both files in the same folder.
2. Start a local server in that folder:
   python3 -m http.server 8000
3. Open http://localhost:8000

Deploy:
Upload both files to the same root directory of a Render Static Site (or another static host).
The website fetches ./vocabulary.json, so do not rename or move the JSON file unless you also update the fetch path in index.html.
