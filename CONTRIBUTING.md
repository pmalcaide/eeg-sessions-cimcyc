# Get involved

The EEG+ Sessions are open to researchers at every stage, whether you are planning a new paradigm, collecting data or in the middle of an analysis.

## Propose a session

We are always looking for:

- **Talks:** present your project or paradigm and get feedback
- **Problem-solving topics:** paradigm design, preprocessing and data quality, analysis and statistics, triggers and recording setup
- **Workshops:** a toolbox or method that is new or not widely used yet
- **Journal club papers:** something you'd like to discuss as a group

<!-- Sustituye [LINK TO FORM] por el enlace del formulario -->
**[Propose a session or topic](mailto:pmalcaide@ugr.es)**

## Found a problem?

A broken link, a notebook that no longer runs, a typo? Open an [issue](../../issues) in this repository, or write to the organisers.

---

## For organisers: adding materials

**A session on a topic that already has a folder** (for example, a second decoding session):

1. Open the topic's `README.md` and add a row to its *Sessions* table.
2. Upload the files to its `slides/` and `code/` folders with the date first, for example `2027-03_talk.pdf`, so sessions don't overwrite each other.
3. Add any new readings, and update the *Sessions* column for that topic in the main [README](README.md).

**A new topic:**

1. Copy [`_template/README.md`](_template/README.md).
2. **Add file → Create new file**, name it `topic-name/README.md` (lowercase, no spaces, for example `time-frequency/README.md`), paste and fill it in.
3. Upload the slides to `slides/` and the notebook to `code/` inside the new folder. From Colab you can also use **File → Save a copy in GitHub**.
4. Add the topic to the *Topics* table in the main [README](README.md).

**Never upload** participant data, raw EEG files or paper PDFs. Notebooks should download data from public sources, and readings should link to a DOI or an open-access version.
