# Pine City Zoo App

A mobile-style, multi-page web application built for the FNB App Academy (Week 3 assignment) to promote tourism in the fictional Pine City by showcasing its zoo via an interactive, visually engaging interface.

---

##  Features

- **Home / Map Screen**  
  Simulates a zoo entrance with a site map and top/bottom navigation tabs for quick access to Animals, Places, Feedback, and Weather.

- **Animals Directory**  
  Browse animal categories via thumbnail "cards"—Elephants, Giraffes, Koalas, Monkeys, Pandas, Lions, Gemsboks, Gorillas, Warthogs—and navigate to detailed pages for each.

- **Individual Animal Pages**  
  Each includes an image and educational description, with a “Where will you find them?” section to simulate location within the zoo. Examples:
  - **Elephants**: detailed info plus habitat location (pen E22, next to the amphitheatre)
  - **Giraffe**, **Gemsbok**, **Gorilla**, and others follow a similar structure :contentReference[oaicite:0]{index=0}

- **Places & Amphitheatre Pages**  
  Highlight areas within the zoo, such as the amphitheatre featuring daily programs (e.g., *A Bug’s Life* at 09:00, *Penny and her Penguins* at 11:00, *Big Cats of Africa* at 14:00) :contentReference[oaicite:1]{index=1}.

- **Weather Screen**  
  Placeholder for a weather forecast page; visual UI suggests an intention for future dynamic content via icons for conditions like sunny, partly cloudy, rain, etc. :contentReference[oaicite:2]{index=2}

- **Feedback Form**  
  A simple form with fields for **Name**, **Email**, and **Message**, plus a **Submit** button that leads to a confirmation page (message-received.html) :contentReference[oaicite:3]{index=3}.

---

##  Tech Stack

- **HTML5** – Semantic layout for each page and content section
- **CSS3** – Shared styling (via `style.css`) to ensure consistency; includes fixed positioning for top/bottom nav bars, layering with `z-index`, and component-like reusable styles :contentReference[oaicite:4]{index=4}
- **Static Web** – Purely front-end, without JavaScript or backend integration, making deployment straightforward and lightweight

---

##  File Structure

Pine-City-Zoo-App/
├── index.html
├── animals.html
├── amphitheatre.html
├── elephants.html
├── giraffes.html
├── koalas.html
├── monkeys.html
├── pandas.html
├── lions.html
├── gemsboks.html
├── gorillas.html
├── warthogs.html
├── places.html
├── feedback.html
├── message-received.html
├── weather.html
├── style.css
└── images/
├── logo.png
├── map.png / map-blur.png
├── icons (arrows, weather icons)
├── animal thumbnails & full images
└── background textures


---

##  Getting Started

To run the app:

1. Clone the repo:
   ```bash
   git clone https://github.com/Vividflar/Pine-City-Zoo-app.git

2. Navigate to the project folder and open index.html in your browser.
