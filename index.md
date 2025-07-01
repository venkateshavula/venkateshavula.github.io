---
layout: default
title: Your Name
---

<div class="profile-container">
  <img src="your-photo.jpg" alt="Your photo" class="profile-img"/>
  <div class="profile-details">
    <h1>Your Name</h1>
    <p>
      <a href="mailto:your@email.com" class="profile-link">your@email.com</a> <br>
      <a href="https://github.com/venkateshavula" class="profile-link" target="_blank">GitHub</a>
    </p>
  </div>
</div>

## Bio

Short paragraph about yourself, your research, and interests.

---

## Publications

- **Author**, _Title_, **Journal**, Year. [Link](#)
- **Author**, _Title_, **Journal**, Year. [Link](#)

---

## Teaching

- Course Name, Institution, Year

---

## Service

- Role or Activity, Organization, Year

---

<style>
/* Inline CSS so it works with GitHub Pages/Jekyll */
body {
  font-family: 'Segoe UI', 'Helvetica Neue', Arial, sans-serif;
  background: #f8f8f8;
  color: #222;
}
.profile-container {
  display: flex;
  align-items: center;
  background: #fff;
  padding: 20px 30px;
  border-radius: 10px;
  margin-bottom: 30px;
  box-shadow: 0 1px 8px rgba(0,0,0,0.05);
}
.profile-img {
  width: 90px;
  height: 90px;
  border-radius: 50%;
  object-fit: cover;
  margin-right: 28px;
  border: 2px solid #355c7d;
}
.profile-details h1 {
  margin: 0 0 10px 0;
  font-size: 2rem;
  color: #355c7d;
}
.profile-link {
  color: #d7263d;
  text-decoration: none;
  font-weight: bold;
}
.profile-link:hover {
  text-decoration: underline;
}
h2 {
  color: #355c7d;
  border-bottom: 1px solid #eee;
  padding-bottom: 4px;
}
a {
  color: #d7263d;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}
@media (max-width: 600px) {
  .profile-container {
    flex-direction: column;
    align-items: flex-start;
    padding: 15px;
  }
  .profile-img {
    margin-right: 0;
    margin-bottom: 12px;
  }
}
</style>
