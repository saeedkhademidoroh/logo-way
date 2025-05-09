# LogoWay

**LogoWay** is an open-source framework for designing, testing, and refining generative prompts for animated logos using tools like RunwayML. It helps creators and engineers collaborate around prompt logic, visual feedback, and iteration workflows.

## 🔧 Features

- Prompt iteration workflow
- Feedback-driven refinement system
- Folder-structured prompt versioning
- Google Drive integration (optional)
- RunwayML-ready prompt output

## 📁 Folder Structure

Each prompt lives in its own folder (`01/`, `02/`, ...), containing:
- `input.txt`
- `prompt_v1.txt`, `feedback_v1.txt`, etc.
- `output_v1.jpg`, `output_v2.mp4`, etc.
- `notes.txt` (optional)

## 📊 log.csv

Tracks prompt cycles with version, tags, and output links.

## 📂 Google Drive Sync (Optional)

Runway outputs and version files can be stored externally in a synced folder.

## 📜 License

MIT License
