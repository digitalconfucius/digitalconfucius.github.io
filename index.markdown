---
layout: home
---

<!-- Begin README contents. -->

<img src="{{ '/assets/images/profile.png' | relative_url }}" alt="Profile Image" class="profile-image" width="125" />

**Building AI-powered games and language tools from Hong Kong**

- making games w/ gen-ai 👾
- moved from CA 🇺🇸 → Hong Kong 🇭🇰
- previously Senior SWE @ social media / FAANG
- languages 🇨🇳🇯🇵

Latest updates on [Twitter / X](https://twitter.com/digiconfucius).

# Projects
### Visual Novel Game: "Nepsis" (In Development)
<div class="image-row">
<div class="img-wrapper" onclick="openModal('{{ '/assets/images/nepsis-1.png' | relative_url }}')">
<img src="{{ '/assets/images/nepsis-1.png' | relative_url }}" alt="Nepsis Screenshot 1" class="anchor-top">
</div>
<div class="img-wrapper" onclick="openModal('{{ '/assets/images/nepsis-2.png' | relative_url }}')">
<img src="{{ '/assets/images/nepsis-2.png' | relative_url }}" alt="Nepsis Screenshot 2" class="anchor-top">
</div>
</div>

- Vibe coding a video game using generative AI tools.
- Enjoy a paranormal horror story with 12 friends that takes place in a modern AI-enhanced Hong Kong.
- Godot 3.6 w/ GDScript, assets generated with image tools.
- Reusable, pure game engine with game data loaded via JSON.
- Custom dialogue editor tool for human-readable screenplay editing written in Python.
- [Dev update](https://x.com/digiconfucius/status/1946536710634131847)

### KikuApp: AI Language Exchange Assistant
<div class="image-row">
<div class="img-wrapper" onclick="openModal('{{ '/assets/images/kikuapp-1.png' | relative_url }}')">
<img src="{{ '/assets/images/kikuapp-1.png' | relative_url }}" alt="KikuApp Screenshot 1" class="anchor-top">
</div>
<div class="img-wrapper" onclick="openModal('{{ '/assets/images/kikuapp-2.PNG' | relative_url }}')">
<img src="{{ '/assets/images/kikuapp-2.PNG' | relative_url }}" alt="KikuApp Screenshot 2" class="anchor-top">
</div>
</div>

- [Try KikuApp!](https://kikuapp.xyz)
- Enjoy a hands-free language exchange experience with our AI audio assistant - no more note-taking or being glued to your dictionary.
- Audio transcriptions of mixed language (e.g. Japanese & English) conversations using Whisper API
- AI insights, grammar corrections, and contextual explanations.
- React Native mobile app + responsive web client.
- Local audio capture with server-side processing and LLM integrations.

### Vocabulai: Simplify Chinese Texts
<div class="image-single">
<div class="img-wrapper" onclick="openModal('{{ '/assets/images/vocabulai-1.png' | relative_url }}')">
<img src="{{ '/assets/images/vocabulai-1.png' | relative_url }}" alt="Vocabulai Screenshot" class="anchor-top">
</div>
</div>

- [Try learning with Vocabulai!](https://vocabulai.xyz) • [Example](https://vocabulai.xyz/documents/18)
- No more Duolingo - a Chinese reader for people who prefer to read Confucius and Lao-Tzu in simple language.
- Read at your level - automatically simplifies documents to match your current vocabulary.
- User vocabulary tracking system with HSK-based difficulty levels and 50k+ word mappings
- Rails backend with PostgreSQL for user profiles and document processing

### Railschan: Resurrecting a 15 year old imageboard that I made when I was a kid
<div class="image-single">
<div class="img-wrapper" onclick="openModal('{{ '/assets/images/sschan-1.png' | relative_url }}')">
<img src="{{ '/assets/images/sschan-1.png' | relative_url }}" alt="SSChan Screenshot" class="anchor-center">
</div>
</div>

- [Make a post on sschan.org](https://sschan.org/posts) - Live website!
- Experience life in 2011 with your own eyes by revisiting a website I hacked together for my friends.
- Rails 3 imageboard with posts, comments, and tags.
- Dockerized deployment on Render w/ consistent versions and persistent DB ad hoc SQLite3 storage.
- Preserved original chan-style UI while adding new features (image uploads).
- [Dev update](https://x.com/digiconfucius/status/1765974455300354236) • [Tech deep-dive](https://digitalconfucius.substack.com/p/railschan-resurrection)

### NEEM (Non-Existent Existentialist Memes): 600K+ Followers on FB/IG
<div class="image-single">
<div class="img-wrapper" onclick="openModal('{{ '/assets/images/neem-1.jpg' | relative_url }}')">
<img src="{{ '/assets/images/neem-1.jpg' | relative_url }}" alt="NEEM Meme Example" class="anchor-center">
</div>
</div>

- [Check us out!](https://neemblog.home.blog/memes/)
- Comedy-philosophy meme page.
- We sell T-shirts and other merchandise. (500+ sales)

### 99% Chinese Character Digital Frequency Poster
- [digitalconfucius.github.io/chinese-poster](https://digitalconfucius.github.io/chinese-poster/)
- A "Tim Ferriss" style language-learning poster that you stick to your browser rather than your refrigerator.
- Learn Chinese by staring at characters every day until you learn them.
- View the most common characters covering 99.99% of typical text.

### jianyin 简音
- [Try jianyin!](https://digitalconfucius.com/jianyin/)
- A proof-of-concept of Chinese character transcription without tonal markers.
- Read Chinese like Chinese people would - left-to-right, without tonal awareness.
- [Read the explanation](https://github.com/digitalconfucius/jianyin/)

### Crystal Ball: Rails + OpenAI Boilerplate
- [View the code](https://github.com/digitalconfucius/crystal-ball/tree/main)
- Copy this code and use it forever for any LLM-enhanced Rails app.
- Clean boilerplate Rails implementation of ChatGPT Client.

# Links
- Twitter / X: [@digiconfucius](https://twitter.com/digiconfucius)
- GitHub: [>digitalconfucius](https://github.com/digitalconfucius)
- Blog: [digitalconfucius @ substack](https://digitalconfucius.substack.com/)

<!-- Image Gallery Styles -->
<style>
.image-row {
  display: flex;
  gap: 10px;
  margin: 20px 0;
}

.image-row .img-wrapper {
  width: calc(50% - 5px);
  max-height: 800px;
  overflow: hidden;
  cursor: pointer;
  position: relative;
}

.image-row .img-wrapper img {
  width: 100%;
  height: auto;
  max-height: 800px;
  transition: transform 0.2s;
  object-fit: cover;
  object-position: top;
}

.image-row .img-wrapper img.anchor-center {
  object-position: center;
}

.image-row .img-wrapper img.anchor-bottom {
  object-position: bottom;
}

.image-row .img-wrapper:hover img {
  transform: scale(1.02);
}

.image-single {
  margin: 20px 0;
  text-align: center;
}

.image-single .img-wrapper {
  width: 100%;
  max-height: 800px;
  overflow: hidden;
  cursor: pointer;
  position: relative;
  display: inline-block;
}

.image-single .img-wrapper img {
  width: 100%;
  height: auto;
  max-height: 800px;
  transition: transform 0.2s;
  object-fit: cover;
  object-position: top;
}

.image-single .img-wrapper img.anchor-center {
  object-position: center;
}

.image-single .img-wrapper img.anchor-bottom {
  object-position: bottom;
}

.image-single .img-wrapper:hover img {
  transform: scale(1.02);
}

/* Modal Styles */
.modal {
  display: none;
  position: fixed;
  z-index: 1000;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: auto;
  background-color: rgba(0,0,0,0.9);
}

.modal-content {
  margin: auto;
  display: block;
  max-width: 90%;
  max-height: 90%;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.close {
  position: absolute;
  top: 15px;
  right: 35px;
  color: #f1f1f1;
  font-size: 40px;
  font-weight: bold;
  cursor: pointer;
}

.close:hover,
.close:focus {
  color: #999;
}

/* Mobile responsive scaling */
@media only screen and (max-width: 1200px) {
  .image-row .img-wrapper,
  .image-single .img-wrapper {
    max-height: 600px;
  }
  
  .image-row .img-wrapper img,
  .image-single .img-wrapper img {
    max-height: 600px;
  }
}

@media only screen and (max-width: 900px) {
  .image-row .img-wrapper,
  .image-single .img-wrapper {
    max-height: 500px;
  }
  
  .image-row .img-wrapper img,
  .image-single .img-wrapper img {
    max-height: 500px;
  }
}

@media only screen and (max-width: 700px) {
  .image-row {
    flex-direction: column;
  }
  
  .image-row .img-wrapper {
    width: 100%;
    max-height: 400px;
  }
  
  .image-single .img-wrapper {
    max-height: 400px;
  }
  
  .image-row .img-wrapper img,
  .image-single .img-wrapper img {
    max-height: 400px;
  }
}

@media only screen and (max-width: 500px) {
  .image-row .img-wrapper,
  .image-single .img-wrapper {
    max-height: 300px;
  }
  
  .image-row .img-wrapper img,
  .image-single .img-wrapper img {
    max-height: 300px;
  }
}
</style>

<!-- Modal HTML -->
<div id="imageModal" class="modal" onclick="closeModal()">
  <span class="close">&times;</span>
  <img class="modal-content" id="modalImg">
</div>

<!-- Modal JavaScript -->
<script>
function openModal(src) {
  var modal = document.getElementById("imageModal");
  var modalImg = document.getElementById("modalImg");
  modal.style.display = "block";
  modalImg.src = src;
}

function closeModal() {
  var modal = document.getElementById("imageModal");
  modal.style.display = "none";
}

// Close modal on escape key
document.addEventListener('keydown', function(event) {
  if (event.key === 'Escape') {
    closeModal();
  }
});
</script>

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-JVFVERMTY0"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-JVFVERMTY0');
</script>
