# 📖 Telugu Corpuseum App

A Streamlit-based community app designed for Telugu locals to share stories, proverbs, entertainment content, and memes. The interface is in **English**, while all content (titles, descriptions, placeholders) supports **Telugu** to preserve cultural richness.

---

## 🚀 Features

* 📌 **Stories Sharing Section** – Post Telugu stories with titles, descriptions, and optional images.
* 📝 **Proverbs & Entertainment** – Share traditional proverbs, jokes, and entertainment snippets.
* 🎭 **Desi Meme Creator** – Post and view Telugu memes with community interaction.
* 💬 **Comment & Upvote System** – Engage with community posts.
* 🔤 **Dynamic Transliteration** – Uses Aksharamukha to convert English inputs into Telugu script.
* 🎨 **Custom UI Styling** – Modern, minimal, and community-friendly design.

---

## 🛠️ Tech Stack

* **Frontend/UI:** Streamlit
* **Backend:** Python
* **Database:** MongoDB (Atlas or local)
* **Libraries:**

  * `streamlit`
  * `pymongo`
  * `aksharamukha` (for transliteration)
  * `PIL` / `io` (for image handling)

---

## 📂 Project Structure

```
📦 telugucorpuseum
 ┣ 📜 app.py                # Main Streamlit app
 ┣ 📜 requirements.txt      # Dependencies
 ┣ 📜 README.md             # Documentation
 ┣ 📂 assets                # (Optional) Static images/icons
 ┗ 📂 utils                 # Helper functions
```

---

## ⚡ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://code.swecha.org/Naveengembali/telugucorpuseum.git
cd telugu-corpuseum/TeluguCorpuseum
```

### 2️⃣ Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
```



### 3️⃣ Run the App

```bash
streamlit run app.py
```

---

## 🖼️ App Preview

### 📖 Login page

welcome to Telugu corpuseum

![Login page Preview](https://i.ibb.co/V0TxdWVh/image.png)


### 📖 Story Sharing Section

Share and view Telugu stories with titles, descriptions, and images.

![Story Sharing Preview](https://i.ibb.co/5WZdzfxh/image.png)

![Story Sharing Preview](https://i.ibb.co/XrGmP2JK/image.png)


### 📝 Proverbs & Entertainment

Discover and contribute Telugu proverbs, jokes, and cultural snippets.

![Proverbs Preview](https://i.ibb.co/S4zWH09C/image.png)

### 🎭 Desi Meme Creator

Upload and browse Telugu memes created by the community.

![Meme Creator Preview](https://i.ibb.co/yMvPCf6/image.png)

![Meme Creator Preview](https://i.ibb.co/KpWGdYVX/image.png)

---

## 📌 Contribution

Contributions are welcome! 🙌

1. Fork the repository
2. Create a new branch (`feature-newsection`)
3. Commit your changes
4. Push to your fork & create a Pull Request

---



## ❤️ Acknowledgements

* Built with **Streamlit**
* Powered by **MongoDB Atlas**
* Telugu script conversion with **Aksharamukha**
