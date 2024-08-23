---
layout: archive
title: "Gallery"
permalink: /works/
author_profile: true
redirect_from:
  - /photography
---
{% include base_path %}

## USA 2024

<div style="display: flex; flex-wrap: wrap; justify-content: space-around; gap: 10px; padding: 10px; background-color: #f0f0f0; border-radius: 10px;">

  <div style="flex-basis: 28%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/1.jpg" alt="Photo 1" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

  <div style="flex-basis: 23.2%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/2.jpg" alt="Photo 2" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

  <div style="flex-basis: 33.7%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/3.jpg" alt="Photo 3" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

  <div style="flex-basis: 30%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/4.jpg" alt="Photo 4" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

  <div style="flex-basis: 30%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/5.jpg" alt="Photo 5" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

  <div style="flex-basis: 30%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/6.jpg" alt="Photo 6" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

  <div style="flex-basis: 30%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/7.jpg" alt="Photo 7" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

  <div style="flex-basis: 30%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/8.jpg" alt="Photo 8" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

  <div style="flex-basis: 30%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/9.jpg" alt="Photo 9" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

  <div style="flex-basis: 22%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/10.jpg" alt="Photo 10" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

  <div style="flex-basis: 22%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/11.jpg" alt="Photo 11" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

  <div style="flex-basis: 22%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/12.jpg" alt="Photo 12" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

  <div style="flex-basis: 22%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/13.jpg" alt="Photo 13" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

  <div style="flex-basis: 100%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/14.jpg" alt="Photo 14" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

  <div style="flex-basis: 100%; margin: 2px; overflow: hidden; border-radius: 10px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
    <img src="/images/photograph/15.jpg" alt="Photo 15" style="width: 100%; height: auto; display: block; cursor: pointer;" onclick="openModal(this);">
  </div>

</div>

<!-- The Modal -->
<div id="myModal" style="display:none; position:fixed; z-index:9999; left:0; top:0; width:100%; height:100%; overflow:auto; background-color:rgba(0,0,0,0.9); cursor:pointer;" onclick="closeModal(event)">
  <img id="modalImg" style="margin:auto; display:block; width:90%; max-width:1200px; max-height:90vh; object-fit:contain; transition: all 0.3s ease;">
</div>

<script>
function openModal(imgElement) {
  var modal = document.getElementById("myModal");
  var modalImg = document.getElementById("modalImg");
  modal.style.display = "block";
  modalImg.src = imgElement.src;
  modalImg.style.cursor = "default";
  
  // Center the image
  modalImg.style.position = "absolute";
  modalImg.style.top = "50%";
  modalImg.style.left = "50%";
  modalImg.style.transform = "translate(-50%, -50%)";
}

function closeModal(event) {
  var modal = document.getElementById("myModal");
  var modalImg = document.getElementById("modalImg");
  
  // Only close if clicking outside the image
  if (event.target === modal) {
    modal.style.display = "none";
  }
}

// Prevent image from closing when clicked
document.getElementById("modalImg").onclick = function(event) {
  event.stopPropagation();
}
</script>
