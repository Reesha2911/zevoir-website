# Zevoir Technologies website

A static, multi-page website for Zevoir Technologies: HTML5, CSS3, JavaScript, Bootstrap and Owl Carousel. It has 14 pages: home, about, services, contact, chatbot, and pages for AI assistants, AI automation, AI governance, cloud migration, data, API integration, ML models, mobile apps and web apps.

Contact details and descriptions on the pages are the company's public website content.

## Run it

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.

## The AI chat button

The chat button opens a pop-up that loads a chatbot from `http://localhost:8000`. It only works while a chatbot server is running on your own computer, such as the Zevoir Genie RAG chatbot. On a hosted copy of the site (for example GitHub Pages) the pop-up will be empty. That is expected.
