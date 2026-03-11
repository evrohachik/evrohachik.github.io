---
layout: default
title: Exploring a Hotel Wi-Fi Router (Turkey, Summer 2023)
---
{% include header.html %}

# Exploring a Hotel Wi-Fi Router (2023)

During a summer trip to Turkey with my mother, I had some free time while staying in a hotel.  
Bored and curious about network security, I decided to explore how hotel Wi-Fi systems were configured.

---

## Initial Discovery

I started with **port scanning** on the hotel router, using only an iPad.  
I noticed services such as:

- Moowifi  
- FastPanel  

which appeared to provide web-based administration and billing interfaces.

<style>
/* Scrollable horizontal gallery */
.carousel {
  display: flex;
  overflow-x: auto;
  gap: 10px;
  padding: 10px 0;
}
.carousel img {
  width: 300px;            /* force width */
  flex-shrink: 0;
  cursor: pointer;
  border-radius: 5px;
  transition: transform 0.2s;
}
.carousel img:hover {
  transform: scale(1.05);
}

/* Lightbox overlay */
.lightbox {
  display: none;
  position: fixed;
  z-index: 100;
  left: 0; top: 0;
  width: 100%; height: 100%;
  background-color: rgba(0,0,0,0.85);
  justify-content: center;
  align-items: center;
}
.lightbox img {
  width: auto;
  height: 90vh;            /* almost full screen height */
  max-width: 95vw;         /* almost full screen width */
  border: 3px solid white;
  border-radius: 5px;
  box-shadow: 0 0 20px black;
}

.lightbox:target {
  display: flex;
}
</style>

<!-- Horizontal scrollable gallery -->
<div class="carousel">
  <a href="#img1"><img src="../images/image 1.jpeg" style="width:300px;" /></a>
  <a href="#img2"><img src="../images/image 2.jpeg" style="width:300px;" /></a>
  <a href="#img3"><img src="../images/image 3.jpeg" style="width:300px;" /></a>
  <a href="#img4"><img src="../images/image 4.jpeg" style="width:300px;" /></a>
  <a href="#img5"><img src="../images/image 5.jpeg" style="width:300px;" /></a>
  <a href="#img6"><img src="../images/image 6.jpeg" style="width:300px;" /></a>
  <a href="#img7"><img src="../images/image 7.jpeg" style="width:300px;" /></a>
</div>

<!-- Lightbox previews -->
<div id="img1" class="lightbox"><a href="#"><img src="../images/image 1.jpeg" /></a></div>
<div id="img2" class="lightbox"><a href="#"><img src="../images/image 2.jpeg" /></a></div>
<div id="img3" class="lightbox"><a href="#"><img src="../images/image 3.jpeg" /></a></div>
<div id="img4" class="lightbox"><a href="#"><img src="../images/image 4.jpeg" /></a></div>
<div id="img5" class="lightbox"><a href="#"><img src="../images/image 5.jpeg" /></a></div>
<div id="img6" class="lightbox"><a href="#"><img src="../images/image 6.jpeg" /></a></div>
<div id="img7" class="lightbox"><a href="#"><img src="../images/image 7.jpeg" /></a></div>
---

## Investigation

Using my own email, I was able to register and access the admin panel.  
From there, I could explore the **network structure** and see how devices were organized.  

The hotel network contained **over 1,000 connected devices**.  

At that point I decided to stop the investigation.  
Even though it was technically possible to dig deeper, I was limited by:

- Only having an iPad  
- The overwhelming size of the network  
- Ethical boundaries — I did not access anyone else’s personal data

---

## What I Learned

This experience gave me insight into:

- Network management at scale  
- Router admin interfaces and potential attack surfaces  
- The importance of securing public Wi-Fi networks  
- Practical constraints when investigating large networks with minimal tools  

---

## Key Takeaways

- Curiosity drives learning, but ethical boundaries are essential  
- Public networks often expose more than expected  
- Investigating systems at scale requires both tools and methodical planning  

---


This small hands-on experience strengthened my interest in **network security, Wi-Fi systems, and digital investigation**, which I continue to develop through labs on Hack The Box and independent research projects.

---

You can explore my work in more detail under [Projects](/projects), [Research](/research), and [Notes](/notes).  