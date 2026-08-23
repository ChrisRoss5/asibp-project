# ASIBP project

College project (Authentication systems and databases S3): A web app providing as many authentication methods as possible using Google Identity Platform and Firebase. Custom OIDC provider included.

https://asibp.k1k1.dev

![App preview](/preview-images/1.png)

Static Firebase Hosting + Identity Platform / FirebaseUI. No build.

Providers in `public/index.html`: Google, Twitter, Facebook, GitHub, Microsoft, Yahoo, email/password, phone, and custom OIDC `oidc.aaiedu` (AAI@EduHr). Firebase project `test-c3ebf`.

```
firebase deploy --only hosting
```

Open `public/index.html` locally only if you already have the Firebase config in that file.

HR writeup: [project-delivery-hr.pdf](/project-delivery-hr.pdf)
