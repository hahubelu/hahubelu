<script>
  document.addEventListener('DOMContentLoaded', function() {
    if (sessionStorage.getItem('redirected')) return;
    var ua = navigator.userAgent || "";
    var target = null;
    if (/android/i.test(ua)) {
      target = "https://play.google.com/store/apps/details?id=com.blu.fidel";
    } else if (/iphone|ipad|ipod/i.test(ua)) {
      target = "https://apps.apple.com/us/app/hahu-speak/id6774989891";
    }
    if (target) {
      sessionStorage.setItem('redirected', '1');
      location.replace(target);
    }
  });
</script>

# ሀሁ በሉ! (HaHu: Speak!)
**“ሀሁ በሉ”** እያንዳንዱን የግዕዝ/የአማርኛ ፊደል እንዴት እንደሚነበብና እንደሚባል ያስተምርዎታል። (HaHu: Speak! teaches you how to read and pronounce every character in the Amharic alphabet.)

---

<a href="https://play.google.com/store/apps/details?id=com.blu.fidel">
  <img src="GOOGLE_PLAY_FINAL.png" alt="Google Play" style="width:220px;">
</a>

# [አንድሮይድ(Android): ማስፈንጠሪያ](https://play.google.com/store/apps/details?id=com.blu.fidel)

---

<a href="https://apps.apple.com/us/app/hahu-speak/id6774989891">
  <img src="APP_STORE_FINAL.png" alt="App Store" style="height:60px;">
</a>

# [አይኦኤስ(iOS): ማስፈንጠሪያ](https://apps.apple.com/us/app/hahu-speak/id6774989891)
