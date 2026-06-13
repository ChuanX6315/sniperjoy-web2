---
title: "影像作品"
date: 2026-04-06T04:30:00+08:00
draft: false
description: "瀏覽斯奈波喬伊的影像作品，包含商業廣告TVC、政府形象影片、品牌紀錄片與平面攝影作品集。"
---

<div x-data="{ tab: 'video' }">

<!-- Tab 按鈕 -->
<div style="display:flex; gap:0.3rem; margin-bottom:2rem; border-bottom:1px solid #ddd;">
  <button @click="tab='video'"
    :style="tab==='video' ? 'font-weight:700; border-bottom:3px solid #5b5ef4; color:black;' : 'color:gray; border-bottom:3px solid transparent;'"
    style="padding:0.75rem 0; background:none; border:none; font-size:1rem; cursor:pointer; transition:all 0.2s; margin-bottom:-1px;">
    影片作品
  </button>
  <button @click="tab='photo'"
    :style="tab==='photo' ? 'font-weight:700; border-bottom:3px solid #5b5ef4; color:black;' : 'color:gray; border-bottom:3px solid transparent;'"
    style="padding:0.75rem 0; background:none; border:none; font-size:1rem; cursor:pointer; transition:all 0.2s; margin-bottom:-1px;">
    平面攝影
  </button>
</div>

<!-- 影片 Tab -->
<div x-show="tab==='video'" x-transition>
<div style="display:grid; grid-template-columns: repeat(3, 1fr); gap:1.5rem; margin: 1.5rem 0;">

<div>
<p style="font-weight:700; margin-bottom:0.25rem;">威技電器｜變頻冷暖分離式冷氣機</p>
<p style="font-size:0.85rem; color:gray; margin-bottom:0.75rem;">導演、攝影</p>
{{< yvideo DUKyQ8G_ftA >}}
</div>

<div>
<p style="font-weight:700; margin-bottom:0.25rem;">臺南 400｜南夏時刻形象影片</p>
<p style="font-size:0.85rem; color:gray; margin-bottom:0.75rem;">監製、攝影</p>
{{< yvideo ySJMv_DseQs >}}
</div>

<div>
<p style="font-weight:700; margin-bottom:0.25rem;">臺南市政府｜身心障礙者及服務人員形象片</p>
<p style="font-size:0.85rem; color:gray; margin-bottom:0.75rem;">導演、攝影</p>
{{< yvideo bLvjarYcAYg >}}
</div>

<div>
<p style="font-weight:700; margin-bottom:0.25rem;">臺南市政府｜臺南市工業區推動及發展影片</p>
<p style="font-size:0.85rem; color:gray; margin-bottom:0.75rem;">監製、後製</p>
{{< yvideo bdXKwn-iiBg >}}
</div>

<div>
<p style="font-weight:700; margin-bottom:0.25rem;">南方修理聯盟｜維修擴點紀錄片</p>
<p style="font-size:0.85rem; color:gray; margin-bottom:0.75rem;">導演、攝影</p>
{{< yvideo VX_7E7big64 >}}
</div>

<div>
<p style="font-weight:700; margin-bottom:0.25rem;">福壽山｜宋莊新莊宣傳影片</p>
<p style="font-size:0.85rem; color:gray; margin-bottom:0.75rem;">導演、後製</p>
{{< yvideo ajHnsrNkgkc >}}
</div>

</div>
</div>

<!-- 攝影 Tab -->
<div x-show="tab==='photo'" x-transition>

<div style="display:grid; grid-template-columns:repeat(3,1fr); gap:1.5rem; margin:1.5rem 0;">

  <div style="position:relative; cursor:pointer; border-radius:0.75rem; overflow:hidden; aspect-ratio:1/1;"
       onclick="toggleAlbum('tai')">
    <img src="/images/portfolio/tai/CYW-5.jpg" style="width:100%; height:100%; object-fit:cover;">
    <div style="position:absolute; inset:0; background:rgba(0,0,0,0.45); display:flex; align-items:flex-end; padding:1.25rem; transition:background 0.2s;"
         onmouseover="this.style.background='rgba(0,0,0,0.25)'"
         onmouseout="this.style.background='rgba(0,0,0,0.45)'">
      <div>
        <p style="color:white; font-weight:800; font-size:1.1rem; margin:0;">戴曉君 GMA36</p>
        <p style="color:rgba(255,255,255,0.7); font-size:0.85rem; margin:0;">5 張照片</p>
      </div>
    </div>
  </div>

  <div style="position:relative; cursor:pointer; border-radius:0.75rem; overflow:hidden; aspect-ratio:1/1;"
       onclick="toggleAlbum('taiwan')">
    <img src="/images/portfolio/taiwan/IMG_7061.JPG" style="width:100%; height:100%; object-fit:cover;">
    <div style="position:absolute; inset:0; background:rgba(0,0,0,0.45); display:flex; align-items:flex-end; padding:1.25rem; transition:background 0.2s;"
         onmouseover="this.style.background='rgba(0,0,0,0.25)'"
         onmouseout="this.style.background='rgba(0,0,0,0.45)'">
      <div>
        <p style="color:white; font-weight:800; font-size:1.1rem; margin:0;">庸俗救星 2025台灣季</p>
        <p style="color:rgba(255,255,255,0.7); font-size:0.85rem; margin:0;">9 張照片</p>
      </div>
    </div>
  </div>

  <div style="position:relative; cursor:pointer; border-radius:0.75rem; overflow:hidden; aspect-ratio:1/1;"
       onclick="toggleAlbum('people')">
    <img src="/images/portfolio/people/IMG_2159.JPG" style="width:100%; height:100%; object-fit:cover;">
    <div style="position:absolute; inset:0; background:rgba(0,0,0,0.45); display:flex; align-items:flex-end; padding:1.25rem; transition:background 0.2s;"
         onmouseover="this.style.background='rgba(0,0,0,0.25)'"
         onmouseout="this.style.background='rgba(0,0,0,0.45)'">
      <div>
        <p style="color:white; font-weight:800; font-size:1.1rem; margin:0;">形象照</p>
        <p style="color:rgba(255,255,255,0.7); font-size:0.85rem; margin:0;">11 張照片</p>
      </div>
    </div>
  </div>

</div>

<!-- 展開的相簿 -->
<div id="album-tai" style="display:none; margin-top:1.5rem;">
{{< gallery title="戴曉君 GMA36" images="/images/portfolio/tai/CYW-5.jpg,/images/portfolio/tai/CYW-6.jpg,/images/portfolio/tai/CYW-7.jpg,/images/portfolio/tai/CYW-8.jpg,/images/portfolio/tai/CYW-9.jpg" >}}
</div>

<div id="album-taiwan" style="display:none; margin-top:1.5rem;">
{{< gallery title="庸俗救星 2025台灣季" images="/images/portfolio/taiwan/IMG_7061.JPG,/images/portfolio/taiwan/IMG_7062.JPG,/images/portfolio/taiwan/IMG_7063.JPG,/images/portfolio/taiwan/IMG_7064.JPG,/images/portfolio/taiwan/IMG_7066.JPG,/images/portfolio/taiwan/IMG_7067.JPG,/images/portfolio/taiwan/IMG_7068.JPG,/images/portfolio/taiwan/IMG_7069.JPG,/images/portfolio/taiwan/IMG_7070.JPG" >}}
</div>

<div id="album-people" style="display:none; margin-top:1.5rem;">
{{< gallery title="形象照" images="/images/portfolio/people/IMG_2159.JPG,/images/portfolio/people/IMG_4447.JPG,/images/portfolio/people/IMG_7247.JPG,/images/portfolio/people/IMG_7251.JPG,/images/portfolio/people/IMG_7253.JPG,/images/portfolio/people/IMG_7254.JPG,/images/portfolio/people/IMG_7255.JPG,/images/portfolio/people/IMG_8831.JPG,/images/portfolio/people/IMG_8833.JPG,/images/portfolio/people/IMG_8834.JPG,/images/portfolio/people/IMG_8835.JPG" >}}
</div>

<script>
function toggleAlbum(id) {
  var albums = ['tai', 'taiwan', 'people'];
  albums.forEach(function(a) {
    var el = document.getElementById('album-' + a);
    if (a === id) {
      el.style.display = el.style.display === 'none' ? 'block' : 'none';
    } else {
      el.style.display = 'none';
    }
  });
  if (document.getElementById('album-' + id).style.display === 'block') {
    document.getElementById('album-' + id).scrollIntoView({ behavior: 'smooth', block: 'start' });
  }
}
</script>

</div>

</div>

---

**有合作需求？**
[立即聯絡我們 →](/contact/)
