SSVM KHANDAHATA - PHASE 3 OFFLINE PORTAL PROTOTYPE

Files:
- index.html: login and role-based portal
- manifest.json: installable web app metadata
- sw.js: offline app-shell cache (works after first successful load on HTTPS hosting)

Demo credentials:
Admin: admin / admin123
Teacher: teacher1 / teach123
Parent: parent1 / parent123
Student: student1 / student123

Admin demo features:
- Add student (admission no, name, class 1-10, guardian)
- View student directory
- Record attendance by admission number and date
- Export/import local JSON backup
- Uses browser IndexedDB for offline records

ANDROID MOBILE STEPS:
1. Download and extract this ZIP using Files / My Files.
2. For a quick test, open index.html in Chrome. Some Android browsers restrict IndexedDB/service workers on file:// URLs.
3. Recommended installable/offline method: publish these files to GitHub Pages over HTTPS.
4. Open the HTTPS website in Chrome, load it once while online, then use Chrome menu > Add to Home screen / Install app.
5. Test airplane mode after the first successful load.

IMPORTANT LIMITATIONS:
- This is a learning prototype, NOT a production-ready school MIS.
- Demo credentials are hard-coded and are NOT secure. No password change, password hashing, server authentication, role permissions enforcement, parent-child linking or teacher-specific access control yet.
- IndexedDB data is local to one browser profile/device; it does not sync to other phones and may be lost if browser/site data is cleared.
- Do not enter real student personal data, phone numbers, fee details or sensitive records.
- Before school-wide use, implement proper authentication, per-role authorization, encryption, secure backups, audit logs, consent/privacy safeguards and tested recovery.
School: SSVM Khandahata
Classes: 1 to 10
Phone provided earlier: 637097584 (appears 9 digits; verify before publishing).
