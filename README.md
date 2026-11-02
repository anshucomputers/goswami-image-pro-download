# Goswami Image Pro — download

Yeh repo sirf customers ke liye banayi gayi hai. Isme app ka source code, licence
banane wala tool, ya koi key nahi hai — sirf download page aur release files.

App Windows 10 / Windows 11 par chalta hai. Kholte hi welcome page aata hai — chhe kaam
ke button, WhatsApp 7351219361 aur email anshucomputers@gmail.com. Pehle 3 din poora kaam
chalta hai, bas page par `TRIAL VERSION` ka watermark rehta hai. 3 din ke baad sirf print
band hota hai; crop, zoom, rotate, resize, PDF aur preview chalte rehte hain.

## Download page

https://anshucomputers.github.io/goswami-image-pro-download/

## Files

| File | Kya hai |
|---|---|
| `Goswami-Image-Pro-Setup-1.10.44.exe` | Installer — double click, Install, Start menu se khol lein. |
| `Goswami-Image-Pro-Trial-1.10.44.zip` | Bina-install folder — pen drive par copy karke chalane ke liye. |

Dono files har release ke **Assets** me hoti hain:
https://github.com/anshucomputers/goswami-image-pro-download/releases

## Licence key

Key offline banti hai. App me **Activate…** kholiye, wahan hare button se WhatsApp par
apne PC ka Install ID chala jayega, aur badle me aayi hui key wahi paste kar dijiye.
App ko internet se chalne ki zaroorat nahi hoti.

## Naya version kaise daalein

```
gh release create v1.10.45 "Goswami-Image-Pro-Setup-1.10.45.exe" "Goswami-Image-Pro-Trial-1.10.45.zip" \
  --title "Version-1.10.45" --notes "..."
```

Asset ka naam file ke naam se aata hai — isliye setup ki local copy pehle hyphen wale naam se
rakhiye, warna GitHub space ko dot bana deta hai aur download link 404 deta hai.

Iske baad `index.html` me version, size aur SHA-256 badliye aur commit kar dijiye.

> Kabhi bhi source code, `LicenseKeyGen.cs`, key generator tool ya `.key` files is repo
> me mat daaliye. Yeh repo public hai.
