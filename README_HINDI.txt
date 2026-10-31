APIMITRA FIREBASE UPDATE

1) GitHub repository me index.html ko is package wali index.html se replace karein.
2) Firebase Console > Firestore Database > Rules me firestore.rules.txt ka content paste karke Publish karein.
3) Firebase Authentication > Settings > Authorized domains me ravi78509.github.io hona chahiye.
4) Authentication > Sign-in method me Phone enabled hona chahiye.
5) GitHub Pages par deploy hone ke baad https://ravi78509.github.io/apimitra/ ko Ctrl+F5 se refresh karein.

IMPORTANT:
- Yeh Firebase Phone Auth (SMS OTP) + Firestore retailer profile ka starter integration hai.
- Firestore Rules ko publish kiye bina real customer data store na karein.
- Firebase Phone Auth me SMS quota, billing/verification limits aur country availability lagu hoti hai. Firebase console me current plan/limits check karein.
- Firebase web apiKey browser config hoti hai, lekin ise security secret na samjhein. Security Firestore Rules aur Auth se hoti hai.
- Wallet balance, payments, commissions, admin/distributor roles aur service APIs abhi implement nahi hain.
