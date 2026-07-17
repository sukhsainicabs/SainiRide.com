SainiRide.com — Website Folder
====================================

IS FOLDER CH KI KI HAI:
------------------------
1. index.html          -> Asli public website (customer eh dekhange). Booking form,
                           fare estimate guide, fleet, about, services, contact — sab ehde ch hi hai.
2. owner-approval.html  -> Sirf tuhade (owner) use lyi hai. Customer nu eh page kite vi
                           link nahi hunda. Booking details paa ke ik click ch WhatsApp
                           confirmation message bana sakde ho (Punjabi/English templates).
3. README.txt           -> Eh file, jehri tuhanu sab samjha rahi hai.

LOCAL TEST KIven KARNI (Laptop te):
------------------------------------
1. Eh sara folder Desktop te rakh lao (jiven "SainiRide-Website" naam naal).
2. index.html te double-click karo — eh apne aap browser (Chrome/Edge) ch khul javega.
3. Booking form bhar ke test karo. Agar internet chalu hai, EmailJS naal email vi
   chali javegi. Agar EmailJS fail ho jaave ya internet na hove, form apne aap
   WhatsApp khol dega booking details de naal (fallback already coded hai).
4. owner-approval.html vi ainvein hi double-click karke khol sakde ho — eh
   booking confirm karan wala tool hai, sirf tuhade lyi.

ZAROORI GALL (IMPORTANT):
--------------------------
- Fonts (Fraunda/Inter) te Google Map, EmailJS — eh sab tan hi load honge jado
  internet chalu hoga. Bina internet vi site khulegi te form kam karega
  (WhatsApp fallback naal), bas fonts/map thoda basic dikhange.
- Rate card (Fare Estimate Guide) di value index.html ch "RATE_CARD" naam de
  JavaScript section ch hai — jado vi rate change karna hove, sirf ohde
  numbers change karo, baaki code touch nahi karna painda.
- Tempo Traveller da koi fixed per-km rate nahi si diya gaya, is lyi ohde lyi
  "Custom Quote — WhatsApp" dikhda hai. Jado rate mil jaave, mainu dass dena,
  main RATE_CARD ch add kar dunga.

AGE KI KARNA (BAAD CH):
-------------------------
- Routes (Popular Routes / Tour Packages) tusi khud website ch add karoge —
  filhaal eh section hata dita gaya hai jiven tusi kiha si.
- Jado local test ho jaave te sab theek lagge, tan eh files GitHub Pages te
  upload kar sakde ho (pehla vaangu — files ik-ik karke upload karna, folder
  drag-drop nahi karna).
- Agar SainiRide.com jaan koi hor domain naal jodna hove, tan sirf DNS/domain
  connect karna painda hai — code ch koi change nahi chahida.

Koi vi sawaal hove ta puch lena — eh sab modular banaya hai taan jo tusi khud
vi text/rate/contact details change kar sako bina puri site tod'e.
