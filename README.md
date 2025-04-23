
# STA-309 Exam  
## **Oasis Lyrics & Sentiment Dashboard**

This project explores the lyrical content and commercial performance of three albums by the legendary British rock band **Oasis**. Using R-based data wrangling, text mining, and visualization techniques, the project analyzes how the emotional tone of lyrics aligns (or doesn't) with a song’s popularity and structure.

It also contextualizes the lyrical evolution of Oasis across a 14-year span — from their explosive Britpop breakthrough to their more experimental later work.

---

## **Albums Analyzed**

### **Definitely Maybe (1994)**  
Oasis's debut album, widely credited with reviving British guitar rock. It was raw, loud, and unapologetically emotional. It marked the band’s entry into mainstream success.

### **(What's the Story) Morning Glory? (1995)**  
This follow-up cemented Oasis’s legacy. With anthems like *Wonderwall* and *Don’t Look Back in Anger*, it became one of the best-selling albums in UK history and propelled the band to global superstardom.

### **Dig Out Your Soul (2008)**  
Released much later in their career, this album features darker tones and more experimental production. While not as commercially dominant, it reflects the band’s shift in creative direction and maturity.

---

## **Key Results of the Analysis**

### 1. **Word Clouds**  
Each album's word cloud visualizes its most frequently used lyrics. Across all three albums, themes like **love**, **time**, **soul**, and **feeling** consistently appear, showing the emotional backbone of Oasis’s songwriting.

Notably, *Definitely Maybe* is filled with confident, high-energy language, while *Dig Out Your Soul* leans more introspective and fragmented — suggesting a lyrical shift over time.

---

### 2. **Sentiment Breakdown**  
A bar chart compares the total positive and negative sentiment word counts for each album. Interestingly, **all three albums skew negative**, particularly *Definitely Maybe*, which contains the highest number of sentiment-tagged words overall.

This result challenges the common assumption that success in popular music is tied to lyrical positivity. Oasis’s style, especially in their early work, leans heavily into emotional realism and frustration — which clearly resonated with fans.

---

### 3. **Sentiment vs. Popularity**  
This scatter plot shows each song’s net sentiment score against its Spotify popularity rating.

**Key finding**: there is **no strong correlation** between positivity in lyrics and a song’s success. Some of the band’s most streamed songs — such as those from *Morning Glory* — have low or even negative sentiment values. This reinforces the idea that emotional impact matters more than sentiment “score” alone.

---

### 4. **Sentiment vs. Duration**  
This second scatter plot compares lyrical sentiment with song length. While no consistent relationship is found across all albums, *Dig Out Your Soul* stands out with **longer songs and more scattered sentiment values**, pointing to a more experimental and diverse emotional structure in their later work.

This aligns with critiques of the album — more atmospheric and less anthemic than earlier releases.

---

## **Repository Contents**

- `lyrics/` — Organized text files of song lyrics per album  
- `spotify_data/` — CSV file with Spotify track popularity & duration  
- `dashboard/` — Final dashboard image (.png)  
- `code/` — R scripts used to analyze and visualize  
- `README.md` — This file  

---

## **Data Sources**

- **Lyrics**: Sourced from [Genius.com](https://genius.com) and stored in `.txt` format for text mining  
- **Popularity & Metadata**: Pulled using the [Spotify Web API](https://developer.spotify.com) and processed via the `spotifyr` package in R

---

## **Summary of Insights**

This project highlights that **Oasis’s success wasn’t based on feel-good lyrics or polished production** — it was built on **raw emotional energy, conviction, and cultural relevance**.

Their first two albums (*Definitely Maybe* and *Morning Glory*) are filled with honest, emotionally dense lyrics — often negative in tone — yet they achieved massive commercial and critical success. This suggests that fans connected deeply with the **vulnerability**, not necessarily the **optimism**.

By contrast, their later work (*Dig Out Your Soul*) shows a stylistic shift: longer songs, more abstract language, and a wider emotional range. But these changes didn’t correspond to increased popularity — reinforcing the **unique cultural moment** captured by their debut era.

