# SocialMind

SocialMind is a school platform that helps kids practice real-world social skills using AI and VR. Kids use a VR headset to act out scenarios like joining a group, asking a teacher for help, or handling disagreement, then continue practice in a companion app on their phone with daily missions and a chat helper that reads in three languages.

The platform has two apps:

- **Dashboard** — for school admins, psychologists, teachers, and parents.
- **Companion App** — for the kids.

---

## Dashboard

Staff log in here to see what each child is doing, how they're progressing, and to act on any safety alert the AI raises.

👉 **Open the dashboard:** https://dashboard.social-mind.org

**Who logs in:**
- **School admin** — creates psychologist, teacher, parent, and child accounts; assigns kids to staff and parents; controls 2-step verification per user.
- **Psychologist** — full clinical view of every assigned child: VR session transcripts, helper-chat history, AI safety flags, missions, risk trend over time. Approves mission and scenario requests from teachers and parents. Trains the adaptive safety filter by labelling chat messages.
- **Teacher** — limited view of assigned children. Can request that a mission or VR scenario be added for a child; the psychologist approves.
- **Parent** — read-only view of their own child plus the option to suggest missions.

---

## Companion App (for kids)

Shows a recap of yesterday's VR session, today's missions to try in real life, and an AI Helper the kid can talk to about anything social. Messages the AI flags as concerning go straight to the kid's psychologist.

### Web (any phone, no install)
👉 **https://social-mind.org**

On iPhone: open the link in Safari → Share → "Add to Home Screen". The app shows up like a native icon.

### Android (install the APK)
Download **[`SocialMind.apk`](./SocialMind.apk)** from this branch and tap it on your phone to install. You'll need to allow "Install from unknown sources" the first time.

---

## Languages

English, Hebrew, Russian — picks up the device language by default in the kid app; switchable in the dashboard top bar.

## Sign-in

Email + password (staff) or username + password (kids). If 2-step verification is enabled for the account, a 6-digit code is emailed at every login.
