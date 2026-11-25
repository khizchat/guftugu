# گفتگو (Guftugu)
HelloTalk-style language-exchange PWA. Plain HTML/JS + Firebase Auth + Firestore. No build step.

## Setup
1. Firebase config for project `guftugu-4472d` is already set in `index.html`.
2. Authentication → Sign-in method → enable **Email/Password**. Add your domain under Authorized domains.
3. Firestore Database → create → Rules → paste `firestore.rules` → Publish.
4. Upload these files to the root of a GitHub repo and deploy on Vercel (static, no build).
