## Hi, I'm Akshat

Computer Science graduate (BSc) building **local-first desktop software in
Python**: apps that keep people's data on their own computer and stay fast
on ordinary laptops. I'm interested in machine learning, search and
information retrieval, and I like making decisions by measuring rather than
guessing.

### Currently building: [Loci](https://github.com/AzureSky0/Local-Research-Assistant-and-Study-Buddy-Hybrid)

**A private knowledge bank for everything you read.** Import papers, books
and notes once, then find anything in them by words or by meaning, with every
result pointing to its page, entirely offline.

- Hybrid search: SQLite FTS5 (BM25) combined with local embeddings
  (fastembed / ONNX) in sqlite-vec, merged with reciprocal rank fusion
- Benchmarked on 358 research papers: the right paper in the top 5 for 87% of
  test questions
- Staged, resumable background processing; PySide6 (Qt) desktop UI;
  packaged for Windows
- Next: answers from your documents with page citations, using a local AI model

[![Latest release](https://img.shields.io/github/v/release/AzureSky0/Local-Research-Assistant-and-Study-Buddy-Hybrid?label=Loci)](https://github.com/AzureSky0/Local-Research-Assistant-and-Study-Buddy-Hybrid/releases/latest)
[![Licence: AGPL v3](https://img.shields.io/badge/licence-AGPL%20v3-1F6B5C)](https://github.com/AzureSky0/Local-Research-Assistant-and-Study-Buddy-Hybrid/blob/main/LICENSE)

### Other projects

| Project | What it is | Built with |
|---|---|---|
| [VS Appointments](https://github.com/AzureSky0/vs-appointments) | An offline booking app for a makeup studio: installs on a phone's home screen, no login or server, with a calendar, reminders and backups | HTML, JavaScript (PWA) |
| [Dementia Face Assistant](https://github.com/AzureSky0/dementia-face-assistant) | A webcam app that helps people living with dementia recognise who is in front of them: it shows each person's relation and last visit, and keeps track of strangers who return | Python, OpenCV, face_recognition |
| [Gesture Virtual Window](https://github.com/AzureSky0/gesture-virtual-window) | A webcam interface controlled by hand gestures, with face-recognition login, face detection and a touch-your-face game | Python, OpenCV, MediaPipe |
| [CV Mini Projects](https://github.com/AzureSky0/cv-mini-projects) | Small real-time computer vision projects: gesture volume control, object detection and hand tracking | Python, OpenCV, MediaPipe |
| [DipTool](https://github.com/AzureSky0/DipTool) | An interactive app for learning digital image processing by seeing each technique's effect | Python |
| [DSL-Tool](https://github.com/AzureSky0/DSL-Tool) | An interactive app for learning data science concepts through visualisation | Python |
| [Algorithms](https://github.com/AzureSky0/Algorithms) | A collection of algorithms I have studied and implemented | Python |

### Tools I work with

- **Languages:** Python · JavaScript · HTML/CSS · SQL
- **Desktop and UI:** PySide6 (Qt) · Tkinter
- **Data and search:** SQLite (FTS5, sqlite-vec) · SQLAlchemy · Alembic · ONNX Runtime / fastembed
- **Computer vision:** OpenCV · MediaPipe · dlib / face_recognition
- **Quality:** pytest · ruff · mypy · Git and GitHub
